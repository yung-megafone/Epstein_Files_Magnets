# Output Specifications (All 14 Deliverables)

This document specifies how each output is produced, its data requirements, and UI/API surfaces.

## 1) Claim → Evidence engine
**Inputs:** structured claim (S/P/O + timeframe) or free-text claim  
**Process:** retrieval + evidence classification + scoring  
**Output:** claim card with supporting/contradicting/context anchors  
**UI:** Claim workspace + export  
**API:** `POST /claims/evaluate`

## 2) Provenance + tamper-evidence layer
**Process:** hash + source URL + timestamp + pipeline versions  
**Output:** provenance panel for every document/artifact  
**UI:** Document sidebar  
**API:** `GET /docs/{id}/provenance`

## 3) Graphs that don’t hallucinate
**Rule:** no edges without anchors  
**Output:** graph slices; click edge → anchors  
**UI:** Graph explorer  
**API:** `GET /graph/neighborhood?entityId=…`

## 4) Uncertainty-aware timeline
**Model:** exact date or range + confidence  
**Output:** timelines for entity/topic  
**UI:** Timeline explorer  
**API:** `GET /timeline?entityId=…`

## 5) Topic modeling / hidden clusters
**Process:** embeddings + clustering + topic labeling  
**Output:** topics with representative anchors  
**UI:** Topic explorer  
**API:** `GET /topics`

## 6) Rhetoric fingerprint tool
**Process:** stylometric features + similarity clustering  
**Output:** “style similarity” reports with caveats  
**UI:** Author/style view  
**API:** `GET /style/cluster?docId=…`

## 7) Cross-dataset de-dup + alias resolution
**Process:** probabilistic matching + evidence-based merges  
**Output:** canonical entities with alias trails  
**UI:** Entity profile  
**API:** `POST /entities/merge-proposal`

## 8) Redaction-aware reconstruction (ethical)
**Process:** detect redaction blocks; repetition patterns  
**Output:** redaction maps (no deanonymization)  
**UI:** Redaction overlay + analytics  
**API:** `GET /docs/{id}/redactions`

## 9) Document similarity explorer
**Process:** MinHash + vector similarity  
**Output:** near-duplicates + forwarding trees  
**UI:** Similar docs panel  
**API:** `GET /docs/{id}/similar`

## 10) Narrative layer
**Process:** evidence-cited summaries + curated tours  
**Output:** exhibit pages with anchors  
**UI:** Tours section  
**API:** `GET /tours`

## 11) Pattern-of-life analytics (guardrailed)
**Process:** aggregates, hubs, seasonality, anomalies  
**Output:** charts + maps with guardrails  
**UI:** Analytics section  
**API:** `GET /analytics/patterns?entityId=…`

## 12) Media vs primary-source comparator
**Inputs:** news URLs + extracted quotes/claims  
**Process:** map quotes to anchors; context loss scoring  
**Output:** accuracy/clipping reports  
**UI:** Comparator section  
**API:** `POST /compare/media`

## 13) Investigative workbook generator
**Process:** auto-curation + open questions  
**Output:** workbook MD/JSON  
**UI:** Workbook builder  
**API:** `POST /workbooks`

## 14) Safe derivative release mechanism
**Process:** publish metadata-only exports, co-occurrence matrices, hashes  
**Output:** downloadable datasets + documentation  
**UI:** Datasets page  
**API:** `GET /exports/datasets`

