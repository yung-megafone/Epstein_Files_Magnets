# Vision and Principles

## Vision
Build a globally available, evidence-backed document intelligence platform that turns large, messy document dumps into a navigable, auditable research experience.

The platform should:
- make it easy to **find primary evidence** quickly
- support **transparent association mapping** (graphs/timelines) without inventing relationships
- produce **exportable artifacts** that withstand scrutiny (claim cards, workbooks, audit logs)
- scale globally with predictable costs and strong caching

## Principles

### 1) Evidence over inference
- Every graph edge, timeline event, and “association” must be backed by at least one **Evidence Anchor**.
- Inferences may be shown, but only:
  - clearly labeled as inference
  - derived from transparent rules
  - linked to the underlying anchors

### 2) Provenance is a feature
- Every file is hashed and tracked with source URLs, timestamps, and pipeline versions.
- Users can see where a file came from and how it was processed.

### 3) Reproducible pipeline
- Same input + same pipeline version => same output.
- Derived artifacts are versioned and traceable.

### 4) Safety and ethics built in
- Redaction-aware handling (detect patterns, do not “unredact”).
- Guardrails against doxxing and misuse.
- Clear disclaimers: “Mention ≠ guilt.”

### 5) Performance through caching
- Page images and popular documents should load fast globally via CDN.
- Search results should be optimized for faceting and highlight rendering.

### 6) Modularity
- Separate immutable raw storage from derived artifacts and indexes.
- Separate pipeline orchestration from serving APIs.

## Non-goals
- Automatically “deciding guilt” or producing accusatory narratives.
- Building a black-box inference engine that can’t be audited.
- Attempting to reverse redactions or deanonymize victims.

