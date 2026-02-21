# System Architecture

## High-level components

1. **Ingestion**
   - Download datasets from authoritative sources and/or mirrors.
   - Validate integrity (hashes, manifests).
   - Store raw bytes immutably.

2. **Processing Pipeline**
   - PDF/image rendering → per-page images
   - Native text extraction (when available)
   - OCR for scanned pages
   - Confidence scoring and quality metrics
   - Entity extraction (strict + audit-friendly)
   - Embeddings + similarity indexing
   - Redaction detection (pattern-level)
   - Derived artifact generation (thumbnails, overlays)

3. **Storage & Indexing**
   - Object store for raw + derived artifacts
   - Relational DB for metadata, provenance, audit logs
   - Full-text search index for page text + highlights
   - Graph store for entity networks (evidence-backed)
   - Optional analytics store for heavy aggregates

4. **APIs**
   - Search API (faceting, highlighting, filters)
   - Document viewer API (page images + OCR overlay)
   - Graph API (edges with anchors)
   - Timeline API (uncertainty-aware events)
   - Export API (claim cards, workbooks, datasets)
   - Admin API (curation, flags, quality review)

5. **Frontend UI**
   - Search + filters
   - Doc viewer with page highlight overlays
   - Graph explorer (click edge → open evidence)
   - Timeline explorer with confidence bands
   - Topic explorer
   - Workbook builder
   - Export center

6. **Operations**
   - Orchestration (Temporal/Airflow/Step Functions)
   - Observability (logs, tracing, metrics)
   - WAF + rate limiting
   - Global CDN & caching

## Reference architecture diagram (text)

User → CDN (static + images) → UI (Next.js)
UI → API Gateway / Load Balancer → App Services
App Services → Postgres (metadata) + OpenSearch (search) + Graph DB
Pipelines → Object Store (raw/derived) + Indexes

## Technology choices (recommended defaults)

### Backend
- **Python** for pipelines (OCR, extraction, NLP) + FastAPI for internal services
- **Node/TypeScript** for public API gateway (optional)
- **Temporal** for orchestration (strong retries, visibility)

### Datastores
- **Object store:** S3 / Cloudflare R2 (cost-sensitive) with lifecycle policies
- **Relational:** Postgres
- **Search:** OpenSearch/Elasticsearch (with kNN/vector capability if needed)
- **Graph:** Neo4j Aura or Postgres + Apache AGE (depending on budget/ops)
- **Analytics:** ClickHouse (optional)

### Frontend
- Next.js + React
- Cytoscape/D3 for graph
- MapLibre for maps
- Custom page viewer with OCR overlay canvas

## Evidence Anchor contract
All “derived insights” must reference anchors of this shape:

```json
{
  "docId": "EFTA01234567",
  "pageNo": 12,
  "charSpans": [[105, 162]],
  "excerptHash": "sha256:…",
  "imageRegion": {"x": 0.21, "y": 0.33, "w": 0.41, "h": 0.06},
  "textConfidence": 0.92,
  "source": {"origin": "doj", "url": "…", "ingestedAt": "…"}
}
```

UI must be able to open the page image and highlight the region immediately from the anchor.

