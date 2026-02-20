# Roadmap

## Phase 0: Foundations (2–3 weeks)
**Deliverables**
- ingestion + hashing + provenance DB
- raw file viewer (PDF/image)
- admin dashboard (basic)

**Acceptance**
- every file has SHA-256 and source URL recorded
- doc catalog lists dataset/doc IDs reliably

## Phase 1: MVP Public (6–10 weeks)
**Deliverables**
- page rendering + thumbnails
- text extraction + OCR pipeline (two-pass)
- OpenSearch indexing with highlights + facets
- public search UI + doc viewer with evidence anchors
- exports v1 (claim cards with anchors)

**Acceptance**
- search returns page-level results with visible highlights
- anchors deep-link correctly to page images
- provenance displayed on every doc

## Phase 2: Evidence graph + timeline + workbook (8–12 weeks)
**Deliverables**
- entity profiles + alias system
- evidence-backed graph explorer
- uncertainty-aware timelines
- workbook generator (MD/JSON export)
- topic explorer v1

**Acceptance**
- no graph edge exists without anchors
- edge click always opens the evidence page/region

## Phase 3: Comparator + narrative + derivative datasets (ongoing)
**Deliverables**
- media vs primary comparator
- curated tours / narrative layer
- safe derivative dataset exports
- pattern-of-life analytics (guardrailed)

**Acceptance**
- comparator maps quotes to anchors or explains failure
- derivative exports exclude sensitive raw content by default

## Operational milestones
- WAF + rate limits live before broad launch
- monitoring dashboards and alerts
- incident response runbook

