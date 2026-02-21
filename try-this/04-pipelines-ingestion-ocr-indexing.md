# Pipelines: Ingestion, OCR, Indexing

## Pipeline overview (stages)

1) **Fetch**
- pull from authoritative sources first
- store raw bytes + metadata
- compute SHA-256
- record provenance

2) **Unpack & classify**
- archive expansion (zip/rar/tar)
- detect file type (pdf, image, txt)
- standardize naming (preserve original)

3) **Render pages**
- PDF → per-page images (PNG/WebP)
- store thumbnails (e.g., 256px) + medium (e.g., 1280px) + optional full-res on demand
- capture page geometry for coordinate mapping

4) **Extract text**
- if PDF includes text layer → extract
- else OCR required

5) **OCR**
- baseline: Tesseract (cheap) with language models
- optional premium OCR for low-confidence pages (Textract/Vision)
- store OCR tokens + confidence when available

6) **Layout analysis (optional but recommended)**
- columns, tables, headers, footers
- improves highlight alignment + entity extraction accuracy

7) **Redaction detection**
- detect black bars / whiteouts at image level
- store bounding boxes and repetition patterns

8) **Entity extraction (strict)**
- NER over native/OCR text
- generate `Mention` objects only
- do not create edges without strong evidence rules

9) **Relationship extraction (evidence-backed)**
- edge creation rules:
  - Email header: From/To/CC => explicit communication edge with anchors
  - Calendar invite: attendees => attendance edge
  - Flight log co-passengers => co-travel edge
  - Otherwise default to co-mention edge (low confidence)
- all edges must include anchors; low confidence edges hidden by default

10) **Indexing**
- OpenSearch:
  - per-page text with highlight offsets
  - facets: datasetId, docType, date, entity mentions
- Graph DB:
  - entities and anchored edges
- Analytics (optional):
  - co-occurrence matrices
  - time-series aggregates

11) **Embeddings & similarity**
- per-page and per-doc embeddings for similarity explorer
- MinHash for near-dup detection
- store similarity pairs above thresholds

## Orchestration
Use Temporal/Airflow/Step Functions to:
- run stages idempotently
- retry safe steps
- isolate failures per doc
- emit metrics (pages processed, OCR confidence distribution, failure rates)

## Quality controls
- OCR confidence thresholds
- sampling-based validation (human spot checks)
- “low confidence” UI warnings
- tie-breaking: prefer native text; fall back to OCR

## Data retention & lifecycle
- raw files: keep indefinitely
- full-res images: optional lifecycle policy (hot for 30–90 days, then cold)
- thumbnails/medium: keep hot for UI responsiveness

