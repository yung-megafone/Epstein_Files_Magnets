# Evidence-Backed Document Intelligence Platform (PR Plan)

Date: **2026-02-20**

This folder is a PR-ready proposal for building a globally available UI + backend platform to ingest large public document dumps (e.g., DOJ releases), verify provenance, OCR/index content, and provide evidence-backed search, graphs, timelines, analytics, and exports.

## What this proposal includes
- Architecture and component breakdown
- Ingestion + OCR + indexing pipeline design
- Evidence-first data model (no hallucinated edges)
- UI modules and user workflows
- Output specifications for all 14 deliverables
- Global deployment plan (CDN, caching, scaling)
- Cost model with levers and scenarios
- Phased roadmap with milestones + acceptance criteria
- Safety/ethics guardrails and redaction-aware handling

## Audience
- Engineering / product leadership
- Investigative newsroom partners / researchers
- Funders / stakeholders

## How to read
1. `01-vision-and-principles.md`
2. `02-system-architecture.md`
3. `03-data-model.md`
4. `04-pipelines-ingestion-ocr-indexing.md`
5. `05-ui-and-user-flows.md`
6. `06-outputs-specs.md`
7. `07-deployment-and-ops.md`
8. `08-security-safety-ethics.md`
9. `09-cost-estimates.md`
10. `10-roadmap.md`

## Glossary (quick)
- **Doc ID**: Source document identifier (e.g., EFTA…)
- **Evidence Anchor**: A reference to a precise location in a doc: `(docId, pageNo, charSpan(s), excerptHash)`
- **Derived Artifact**: Any pipeline output (OCR text, thumbnails, embeddings, entities, edges)
- **Strict Evidence Mode**: UI defaults to only showing claims/edges backed by anchors

