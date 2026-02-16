# ARCHIVAL RECORD — Epstein Files Corpus (WIP)

This document is the **historical ledger** for the Epstein Files corpus.

It preserves:

* historical and deprecated sources
* community reconstruction efforts
* dataset anomalies and structural divergences
* NATIVEs analysis and recovery progress
* verification artifacts and manifests
* checksum lineage
* contributor transparency
* context intentionally excluded from the main README

The **main README** is concise and forward-facing.
This document is archival and explanatory.

Nothing documented here is removed once recorded (append-only by design).

If this corpus must be understood **years later**, this is the record.

---

## ⚖️ Archival Philosophy

This repository distinguishes between two structural tiers:

### 1. Canonical Corpus

* Preserves original DOJ release structure
* Prioritizes least-redacted verified copies
* Maintains original ZIP hash lineage
* Avoids structural reinterpretation
* Separates source material from derivative normalization

### 2. Reference / Reconstruction Sets

* Community composites
* Flattened or normalized structures
* Superseded torrents
* Partial reconstructions
* Aggregated structured builds

Reference sets are preserved for transparency but are **not authoritative**.

This separation protects provenance integrity.

---

# Table of Contents

1. [Overview](#overview)
2. [Canonical vs Reference Classification](#canonical-vs-reference-classification)
3. [Structured Dataset (Mostly Full) — 2026-02-04](#structured-dataset-mostly-full--2026-02-04)
4. [Data Set 9 (DS09) — Detailed Notes, History, and Reconstruction](#data-set-9-ds09--detailed-notes-history-and-reconstruction)
5. [Historical Sources & Magnets (DS09)](#historical-sources--magnets-ds09)
6. [Reconstruction Methodology (DS09)](#reconstruction-methodology-ds09)
7. [NATIVEs Analysis & Recovery Status](#natives-analysis--recovery-status)
8. [Redaction Divergence Notes](#redaction-divergence-notes)
9. [Timeline of Availability](#timeline-of-availability)
10. [Relationship to Main README](#relationship-to-main-readme)
11. [Maintenance Policy](#maintenance-policy)

---

# Overview

The Epstein Files corpus consists of Data Sets 1–12 originally released under EFTA.

While most datasets are structurally stable, **Data Set 9 (DS09)** is historically:

* the largest
* the most unstable
* the most fragmented across community sources
* the only dataset requiring major reconstruction

This document preserves how the corpus evolved from aggregation to provenance-focused archival.

---

# Canonical vs Reference Classification

### Canonical

* Original DOJ ZIP structure maintained
* Verified original ZIP hashes
* Least-redacted known copies preserved
* No normalization applied

### Reference

* Structured dataset builds
* Community composite torrents
* Deduplicated merges
* Flattened navigational reorganizations
* Superseded magnets

Reference materials remain documented to preserve checksum and magnet lineage.

---

# Structured Dataset (Mostly Full) — 2026-02-04

Contributor:
[https://github.com/excoffierleonard](https://github.com/excoffierleonard)

Release Title:
**Epstein Files — Structured Dataset (Mostly Full) (1-12)**
Release Date: 2026-02-04
Size: 206.18 GB

---

## Torrent Magnet

```
magnet:?xt=urn:btih:f5cbe5026b1f86617c520d0a9cd610d6254cbe85&dn=epstein-files-structured-full-20250204.tar.zst&xl=221393230690
```

---

## Archive Hash

**SHA256:**
29acc987cd7fadfbbf94444ed165750b84d82c85af3703bab74308ea9e91e910

---

## Status

Preserved for transparency and historical reference.

Not designated canonical due to:

* Incomplete DS09
* Inclusion of later redacted file variants
* Structural normalization differing from original DOJ layout
* Use of community composites for DS10 and DS11

This dataset materially assisted early aggregation and reconciliation efforts.

---

# Data Set 9 (DS09) — Detailed Notes, History, and Reconstruction

This section is the **authoritative deep-dive for DS09**.

It preserves:

* historical magnets
* reconstruction efforts
* NATIVEs analysis
* verification artifacts
* context excluded from the main README

---

## Current Status (February 2026)

* ~99.9% reconstructable by file count
* ~25 PDFs unresolved
* 2,327 / 2,542 NATIVEs recovered (~91.6%)

Completeness measured by file presence, not byte-for-byte parity.

This repository does not claim canonical completeness — only best verifiable public reconstruction.

---

## Reconstruction Completeness (~99.9%)

### IMAGES (PDFs)

* Expected: ~531,307
* Recovered: ~531,282
* Missing: ~25 PDFs

### NATIVEs (Media Files)

* Expected: ~2,542
* Recovered: 2,327
* Recovery rate: ~91.6%

Remaining NATIVEs fall into:

* `HEAD 200` → `GET 404`
* Unresolvable Bates numbers

---

# Historical Sources & Magnets (DS09)

Preserved for archival and forensic context.

---

### Early Partial Community Magnet (~45 GB)

```
magnet:?xt=urn:btih:0a3d4b84a77bd982c9c2761f40944402b94f9c64&dn=DataSet9-incomplete.zip&xl=48995762176
```

Status: Deprecated
Severely incomplete
No NATIVEs

---

### Deduplicated Community Composite (~89.5 GB)

```
magnet:?xt=urn:btih:7ac8f771678d19c75a26ea6c14e7d4c003fbf9b6&dn=dataset9-more-complete.tar.zst&xl=96148724837
```

Status: Superseded

---

### ym Compiled PDFs (~94.58 GB)

```
magnet:?xt=urn:btih:286060d26392042a5e2b5354d09ec7c7c5cee7dc&dn=dataset-09%20%28Incomplete%29&xl=101565025420
```

Status: Historical reference

---

### Larger Community Archive (~140 GB)

```
magnet:?xt=urn:btih:5b50564ee995a54009fec387c97f9465eb18ba00&dn=dataset-9_by_fuckthissite3.tar&xl=148072017920
```

Status: Historical reference

---

# Reconstruction Methodology (DS09)

Earlier efforts involved:

* merging partial archives
* deduplicating by filename and size
* validating against `.DAT` manifests
* identifying placeholder NATIVEs

Current methodology prioritizes:

* direct endpoint recovery
* HEAD-before-GET validation
* incremental verification
* manifest reconciliation

---

# NATIVEs Analysis & Recovery Status

### Placeholder Sizes Observed

* 4670 bytes
* 2433 bytes

Likely upstream stubs or redactions.

---

### Observations

* Office documents often 0-byte stubs
* Two SQLite databases password protected
* Some `.avi` files sequential frame segments
* Significant jail footage present

---

# Redaction Divergence Notes

Datasets 1–8 exist in:

* Earlier less-redacted versions
* Later redacted DOJ reuploads

Canonical corpus preserves least-redacted verified variants where available.

Structured or community builds may contain later redacted copies.

This divergence is intentional and documented.

---

# Timeline of Availability

1. DOJ publishes Data Sets 1–12
2. DS09 unstable / incomplete
3. Early partial magnets (~45 GB)
4. Deduplicated composites (~89.5 GB)
5. Larger community reconstructions (~140 GB)
6. Structured dataset aggregation (Leonard)
7. Provenance-first canonical corpus established

---

# Relationship to Main README

Main README:

* Clean
* Minimal
* Current recommended downloads

Archival Record:

* Exhaustive
* Historical
* Magnet lineage preserved
* Append-only

---

# Maintenance Policy

* Append-only
* No historical deletions
* Superseded magnets retained
* Corrections documented inline
* Canonical designation explicitly stated

This document ensures the Epstein Files corpus retains a verifiable paper trail.
