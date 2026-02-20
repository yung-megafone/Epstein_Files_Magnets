# UI and User Flows

## Primary UX modules

### 1) Search
- query box with operators and suggestions
- facets: dataset, doc type, date range, OCR confidence, entities
- results show:
  - snippet with highlights
  - doc ID + dataset
  - confidence badges (native vs OCR, low-confidence warning)

### 2) Document viewer
- page thumbnails sidebar
- main page image with:
  - highlight overlays
  - OCR text layer toggle
  - confidence heatmap toggle (optional)
- evidence anchors are shareable deep-links (docId + page + region)

### 3) Graph explorer
- entity graph with filters:
  - edge types
  - confidence
  - time range
- click edge → open evidence drawer (anchors)
- default mode shows only high-confidence anchored edges

### 4) Timeline explorer
- entity-centric or topic-centric timeline
- uncertainty shown as ranges and bands
- click event → open anchor evidence

### 5) Topic explorer
- list of discovered topics with keywords
- each topic has representative evidence pages
- topic → filtered search / timeline / graph slice

### 6) Claim → Evidence workspace
- paste a claim (structured form)
- system returns:
  - supporting anchors
  - contradicting anchors
  - “context only” anchors
  - confidence score with rubric explanation
- export claim card

### 7) Workbook builder
- choose entities/topics/date range
- auto-curate:
  - top documents
  - key anchors
  - timeline
  - open questions
- export to Markdown/JSON

### 8) Export center
- claim cards (PDF/MD)
- citation bundles (JSON)
- entity packets (CSV)
- safe derivative datasets

## Typical user flow
1. Search → open document
2. Highlight evidence → save to workspace
3. Explore graph around entities
4. Build timeline slice
5. Export a claim card or workbook

## Public-facing guardrails
- clear banners:
  - “Mention ≠ guilt”
  - “Edges require evidence”
- report/flag mechanisms
- sensitive-content gating (as needed)

