# Data Model

This model is designed for auditability and evidence-first UX.

## Core entities

### Document
- `id` (internal UUID)
- `sourceDocId` (e.g., EFTA…)
- `datasetId` (e.g., DataSet 9)
- `sourceUrls[]`
- `sha256`
- `byteSize`
- `mimeType`
- `ingestedAt`
- `provenance` (see below)
- `derivedVersion` (pipeline version used)

### Page
- `documentId`
- `pageNo`
- `imageKey` (object store)
- `thumbKey`
- `nativeText` (optional)
- `ocrText` (optional)
- `ocrConfidence` (0..1)
- `layoutJson` (optional)
- `redactionBlocks[]` (optional)

### EvidenceAnchor
- `id`
- `documentId`, `pageNo`
- `charSpans[]` (on chosen text stream)
- `excerptHash`
- `imageRegion` (normalized coords)
- `confidence`
- `createdBy` (pipeline/manual)

### Entity
- `entityId`
- `canonicalName`
- `entityType` (Person/Org/Place/Email/Phone/Other)
- `aliases[]` (with evidence)
- `identifiers` (emails, phones, etc. with anchors)
- `mergeStatus` (auto/proposed/locked)

### Mention
- link between `Entity` and `EvidenceAnchor`
- includes `mentionText`, `confidence`, `method` (NER/OCR/manual)

### RelationshipEdge (Graph)
- `edgeId`
- `srcEntityId`, `dstEntityId`
- `edgeType` (email, co-mention, introduced, attended, travel, legal-mention, etc.)
- `anchors[]` (>=1 required)
- `timeRange` (optional)
- `confidence`
- `directional` (bool)

**Rule:** An edge cannot exist without anchors.

### Event (Timeline)
- `eventId`
- `title`
- `time` (exact or date-only) OR `timeRange`
- `confidence`
- `eventType`
- `anchors[]` (>=1)

### Provenance
- `origin` (doj/mirror/other)
- `retrievedAt`
- `retrievalMethod`
- `sourceIntegrity` (verified/unverified + details)
- `pipelineVersions` (extractor, OCR, embedder)
- `notes`

## Derived data

### Topic
- `topicId`
- `label`
- `keywords[]`
- `representativeAnchors[]`

### Similarity
- document embeddings stored per doc and per page
- MinHash signatures for near-dup detection

## Audit logging
- Every admin action produces an immutable audit record
- Merges, edge approvals, flags are reversible

