# <a id="epstein-files-jan-31-2026"></a>Epstein Files Jan 31, 2026

## <a id="dataset-status-dashboard"></a>Dataset Status Dashboard

Quick availability overview of all currently indexed datasets:

![Release](https://img.shields.io/badge/Release-Jan%2030%2C%202026-black?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Archive%20Index%20%2F%20Mirror-lightgrey?style=for-the-badge)
![Primary](https://img.shields.io/badge/Primary-DOJ%20ZIPs-blue?style=for-the-badge)
![Community](https://img.shields.io/badge/Community-Torrents%20%2B%20Internet%20Archive-purple?style=for-the-badge)

![DataSet%201](https://img.shields.io/badge/DataSet%201-1.237%20GB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%202](https://img.shields.io/badge/DataSet%202-630%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%203](https://img.shields.io/badge/DataSet%203-595%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%204](https://img.shields.io/badge/DataSet%204-351%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%205](https://img.shields.io/badge/DataSet%205-61.4%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%206](https://img.shields.io/badge/DataSet%206-51.2%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%207](https://img.shields.io/badge/DataSet%207-96.9%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%208](https://img.shields.io/badge/DataSet%208-9.95%20GB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%209](https://img.shields.io/badge/DataSet%209-94.58%20GB%20%7C%20~99.5%25%20Reconstructed-orange?style=for-the-badge)
![DataSet%2010](https://img.shields.io/badge/DataSet%2010-78.6%20GB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%2011](https://img.shields.io/badge/DataSet%2011-25.5%20GB%20%7C%20Available-brightgreen?style=for-the-badge)
![DataSet%2012](https://img.shields.io/badge/DataSet%2012-114%20MB%20%7C%20Available-brightgreen?style=for-the-badge)

---

This repository is a community **mirror + indexing project** for the **Jan 30, 2026** Epstein Files data release published by the **U.S. Department of Justice**.

The original release is distributed across many separate `.zip` archives. Community archivists have since produced **torrent magnets** and **Internet Archive mirrors** to make the data easier to preserve, resume, verify, and distribute long-term.

**Goal:** provide a stable public index of download methods (DOJ + torrent + mirrors), especially if links break, files disappear, or servers throttle/cut off transfers.  
**How to help:** seed torrents, mirror responsibly, and verify hashes when provided.

**Initial Inspiration (DataHoarder):**  
<https://old.reddit.com/r/DataHoarder/comments/1qrk3qk/epstein_files_datasets_9_10_11_300_gb_lets_keep/>

```text
https://old.reddit.com/r/DataHoarder/comments/1qrk3qk/epstein_files_datasets_9_10_11_300_gb_lets_keep/
````

---

## <a id="table-of-contents"></a>Table of Contents

* [Dataset Status Dashboard](#dataset-status-dashboard)
* [How to Use This Repo](#how-to-use-this-repo)
* [Download Options](#download-options)
* [How to Torrent the Magnet Links](#how-to-torrent-the-magnet-links)
* [Hash Verification](#hash-verification)
* [Notes on Data Set 9](#notes-on-data-set-9)
* [How to Compile a Mostly Complete Data Set 9](#ds9-reconstruction)
* [Datasets](#datasets)
  * [Quick Jumps](#quick-jumps)
  * [Structured Dataset Full](#structured-dataset-full)
  * [Data Sets 1–8 (Internet Archive)](#data-sets-1-8-internet-archive)
  * [Data Set 1](#data-set-1)
  * [Data Set 2](#data-set-2)
  * [Data Set 3](#data-set-3)
  * [Data Set 4](#data-set-4)
  * [Data Set 5](#data-set-5)
  * [Data Set 6](#data-set-6)
  * [Data Set 7](#data-set-7)
  * [Data Set 8](#data-set-8)
  * [Data Set 9 (Incomplete)](#data-set-9-incomplete)
  * [Data Set 10](#data-set-10)
  * [Data Set 11](#data-set-11)
  * [Data Set 12](#data-set-12)
* [Disclaimer](#disclaimer)

---

## <a id="how-to-use-this-repo"></a>How to Use This Repo

This repository is an **index + mirror helper** for the Epstein Files datasets released by the U.S. Department of Justice.

Each dataset entry includes:

* The official DOJ `.zip` download link (when available)
* A torrent magnet link (community preservation)
* A raw copy/paste version of each link for reliability
* Hashes (when known) for verification

The goal is to make these files easier to:

* download in full
* resume if interrupted
* preserve long-term
* seed back to the community

---

## <a id="download-options"></a>Download Options

You can obtain datasets in three main ways:

### <a id="option-1-direct-download-doj"></a>Option 1 — Direct Download (DOJ)

Each dataset includes an official DOJ `.zip` URL.

Example:

```text
https://www.justice.gov/epstein/files/DataSet%2012.zip
```

These links may be slow, rate-limited, or occasionally cut off (as seen with Data Set 9).

---

### <a id="option-2-torrent-magnet-links-recommended"></a>Option 2 — Torrent Magnet Links (Recommended)

Torrent magnets are the most reliable way to:

* avoid server throttling
* resume partial downloads
* preserve long-term availability

A magnet link looks like this:

```text
magnet:?xt=urn:btih:....
```

---

## <a id="how-to-torrent-the-magnet-links"></a>How to Torrent the Magnet Links

### <a id="step-1-install-a-torrent-client"></a>Step 1 — Install a Torrent Client

You need a BitTorrent client that supports magnet links.

Recommended:

* **qBittorrent (Windows/Linux/macOS)**
  [https://www.qbittorrent.org/](https://www.qbittorrent.org/)

* **Transmission (macOS/Linux)**
  [https://transmissionbt.com/](https://transmissionbt.com/)

---

### <a id="step-2-copy-the-magnet-link"></a>Step 2 — Copy the Magnet Link

In this repo, magnets are provided in copy-safe blocks:

```text
magnet:?xt=urn:btih:....
```

Highlight the entire line and copy it.

---

### <a id="step-3-add-the-magnet-to-your-client"></a>Step 3 — Add the Magnet to Your Client

In qBittorrent:

1. Open qBittorrent
2. Click **File → Add Torrent Link**
3. Paste the magnet URI
4. Click **Download**

In Transmission:

1. Open Transmission
2. Click **Open URL**
3. Paste the magnet link
4. Confirm

---

### <a id="step-4-let-it-complete-verify-size"></a>Step 4 — Let It Complete + Verify Size

Some datasets are very large (10 - 80+ GB).

Make sure the completed size matches the dataset label.

Example:

* Data Set 10 ≈ 82 GB
* Data Set 11 ≈ 27.5 GB
* Data Set 9 currently incomplete

---

### <a id="step-5-please-seed-after-downloading"></a>Step 5 — Please Seed After Downloading

Torrent preservation only works if people continue seeding.

After completion:

* leave your torrent client running
* seed back to others
* help keep the archive alive

---

## <a id="hash-verification"></a>Hash Verification

Some datasets include SHA1 / SHA256 / MD5 hashes.

Example:

```text
SHA256: ...
```

Linux/macOS:

```bash
sha256sum DataSet_10.zip
```

Windows PowerShell:

```powershell
CertUtil -hashfile DataSet_10.zip SHA256
```

Compare output to the hash listed in this repo.

---

## <a id="notes-on-data-set-9"></a>Notes on Data Set 9

⚠ **Data Set 9 has historically been incomplete / unstable via DOJ direct download** (many reports of cutoff around ~49 GB / 180 GB).

**Update:** As of early Feb 2026, community reconciliation using the dataset metadata files (`.DAT` / `.OPT`) indicates Data Set 9 is now **~99.5% reconstructable** from currently circulating sources.

### What “~99.9%” means (high-level)

* The dataset appears to contain **~531,307** expected `IMAGES` entries (PDF) based on `.DAT`.
* Current merged sources yield **~531,282** PDF files.
* That implies **~25 PDFs** remain missing.
* Additional missing content is believed to be `NATIVES` (media such as audio/video) — on the order of **~135 files** (estimate may change).
* The remaining “missing size” is therefore likely **not PDFs**, but mostly `NATIVES`.

> **Important:** This repo does not claim Data Set 9 is fully complete or canonical.  
> It documents the best-known public reconstruction status at the time of writing.

**Additional notes:**
* Multiple users report DOJ download failures, HTTP 404s, paginator errors, and IP-based blocking when attempting to retrieve Data Set 9.
* These issues appear to affect multiple regions and are not user-specific.

---

## <a id="ds9-reconstruction"></a>How to Compile a Mostly Complete Data Set 9 (Reconstruction)

This is a **best-effort reconstruction workflow** for building the most complete DS9 currently available from public sources.

### Sources currently used for reconstruction

You may see DS9 in multiple partial forms:

* **DOJ direct ZIP (often cuts off around ~49 GB)**
* **Community “more complete” DS9 tarball (~89.54 GB, deduplicated merge)**
* **Internet Archive mirrors (where available)**
* **Other partial torrents (various sizes, unverified)**

### Recommended approach (practical + reproducible)

1) **Choose a target folder** (example):
   * `dataset-09_reconstructed/`

2) **Extract the most complete archive first**
   * Start with the **largest / deduplicated** DS9 archive you have (e.g., the ~96.25 GB community merge).
   * Extract it into `dataset-09_reconstructed/`

3) **Overlay additional sources**
   * Extract other DS9 variants (including the DOJ partial ZIP if you have it) **on top of** the same folder.
   * When prompted, choose:
     * **Skip existing files** (preferred)
     * or **overwrite only if the incoming file is larger** (optional, manual)

4) **De-duplicate by filename + size**
   * Many files are duplicated across sources. If multiple copies exist, keep one copy only.
   * (Advanced users may de-dupe by SHA256, but filename/size de-dupe is often sufficient for initial cleanup.)

5) **(Optional) Keep a “raw sources” folder**
   * Keep original archives untouched in a separate directory so your reconstruction folder stays clean.

### Verification (recommended)

* If a trusted `SHA256SUMS` manifest is published for a given DS9 reconstruction, verify using:
  * Linux/macOS: `sha256sum -c SHA256SUMS.txt`
  * Windows PowerShell: `Get-FileHash` (see Hash Verification section)

> **Note:** DS9 reconstruction is evolving. Avoid labeling your merged output as “complete” unless you can verify against a known-good manifest.

---

## <a id="datasets"></a>Datasets

### <a id="quick-jumps"></a>Quick Jumps

* [Structured Dataset (Mostly Full)](#structured-dataset-full)
* [Data Sets 1–8 (Internet Archive)](#data-sets-1-8-internet-archive)
* [1](#data-set-1) · [2](#data-set-2) · [3](#data-set-3) · [4](#data-set-4) · [5](#data-set-5) · [6](#data-set-6)
* [7](#data-set-7) · [8](#data-set-8) · [9](#data-set-9-incomplete) · [10](#data-set-10) · [11](#data-set-11) · [12](#data-set-12)

---


## <a id="structured-dataset-full"></a>Structured Dataset (Mostly Full) (207G)

**Epstein Files — Structured Dataset (Mostly Full) (1-12) 2026-02-04 (207G)**

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:f5cbe5026b1f86617c520d0a9cd610d6254cbe85&dn=epstein-files-structured-full-20250204.tar.zst&xl=221393230690)**

  ```text
  magnet:?xt=urn:btih:f5cbe5026b1f86617c520d0a9cd610d6254cbe85&dn=epstein-files-structured-full-20250204.tar.zst&xl=221393230690
  ```

**SHA256:** 29acc987cd7fadfbbf94444ed165750b84d82c85af3703bab74308ea9e91e910

> Verification Status:
> This archive is currently being downloaded and verified by maintainers.
> The published SHA256 hash is provided by the contributor and has not yet been independently verified by this repository at the time of merge.
> 
> Verification is in progress and this note will be updated once complete.

**README.txt**

```text
EPSTEIN FILES - STRUCTURED DATASET
==================================
Last updated: 2026-02-04

STRUCTURE
---------
./
├── checksums.csv
├── README.txt
├── dataset_00001/
│   ├── checksums.csv
│   ├── pdfs/
│   ├── media/
│   └── metadata/
├── ...
└── dataset_00012/

Datasets correspond 1:1 with original DOJ releases (dataset_00001 = DataSet 1, etc.)

FOLDERS
-------
pdfs/      Court documents, depositions, flight logs, and other legal records
media/     Images, videos, and audio files extracted from evidence
metadata/  JSON/text files with extracted text, OCR data, and file metadata

CHECKSUMS
---------
Root checksums.csv     All files across all datasets (for global deduplication/verification)
Dataset checksums.csv  Files within that dataset only (for per-dataset verification)

Format: filename,sha256,dataset,dir

SOURCES
-------
Dataset 01: https://www.justice.gov/epstein/files/DataSet%201.zip
Dataset 02: https://www.justice.gov/epstein/files/DataSet%202.zip
Dataset 03: https://www.justice.gov/epstein/files/DataSet%203.zip
Dataset 04: https://www.justice.gov/epstein/files/DataSet%204.zip
Dataset 05: https://www.justice.gov/epstein/files/DataSet%205.zip
Dataset 06: https://www.justice.gov/epstein/files/DataSet%206.zip
Dataset 07: https://www.justice.gov/epstein/files/DataSet%207.zip
Dataset 08: https://www.justice.gov/epstein/files/DataSet%208.zip
Dataset 09: magnet:?xt=urn:btih:7ac8f771678d19c75a26ea6c14e7d4c003fbf9b6&dn=dataset9-more-complete.tar.zst
Dataset 10: magnet:?xt=urn:btih:d509cc4ca1a415a9ba3b6cb920f67c44aed7fe1f&dn=DataSet%2010.zip
Dataset 11: magnet:?xt=urn:btih:59975667f8bdd5baf9945b0e2db8a57d52d32957&dn=DataSet%2011.zip
Dataset 12: https://www.justice.gov/epstein/files/DataSet%2012.zip

NOTES
-----
- Dataset 09: Original DOJ source incomplete; using a partial community torrent composite
- Dataset 10: Original DOJ source no longer available; using a complete community torrent
- Dataset 11: Original DOJ source no longer available; using a complete community torrent

SOURCE FILE CHECKSUMS (SHA256)
------------------------------
Dataset 01: 598f4d2d71f0d183cf898cd9d6fb8ec1f6161e0e71d8c37897936aef75f860b4
Dataset 02: 24cebbaefe9d49bca57726b5a4b531ff20e6a97c370ba87a7593dd8dbdb77bff
Dataset 03: 1c5587152328bd45a68baefeb5fba1d55677be4ff0b381d721f37c7b3da9055e
Dataset 04: 979154842bac356ef36bb2d0e72f78e0f6b771d79e02dd6934cff699944e2b71
Dataset 05: 7317e2ad089c82a59378a9c038e964feab246be62ecc24663b741617af3da709
Dataset 06: d54d26d94127b9a277cf3f7d9eeaf9a7271f118757997edac3bc6e1039ed6555
Dataset 07: 51e1961b3bcf18a21afd9bcf697fdb54dac97d1b64cf88297f4c5be268d26b8e
Dataset 08: 8cb7345bf7a0b32f183658ac170fb0b6527895c95f0233d7b99d544579567294
Dataset 09: 377cce99ac4fdd64bb8f97a63fc12f63f29adf3c8f1d44679aa0811fcb3e6fd2
Dataset 10: 7d6935b1c63ff2f6bcabdd024ebc2a770f90c43b0d57b646fa7cbd4c0abcf846
Dataset 11: 9714273b9e325f0a1f406063c795db32f5da2095b75e602d4c4fbaba5de3ed80
Dataset 12: b5314b7efca98e25d8b35e4b7fac3ebb3ca2e6cfd0937aa2300ca8b71543bbe2

CREDITS
-------
Restructured by: https://github.com/excoffierleonard
Source repository: https://github.com/yung-megafone/Epstein-Files
```

---

### <a id="data-sets-1-8-internet-archive"></a>Data Sets 1–8 (Internet Archive)

**Epstein Files Data Sets 1-8: [INTERNET ARCHIVE LINK](https://archive.org/details/combined-all-epstein-files/COMBINED_ALL_EPSTEIN_FILES.pdf)**

```text
https://archive.org/details/combined-all-epstein-files/COMBINED_ALL_EPSTEIN_FILES.pdf
```

---

### <a id="data-set-1"></a>Data Set 1

**Data Set 1 (1.23 GB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%201.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%201.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:03d260e3e5d455379d40cd36ded08d5f47228ad7&dn=DataSet%201.zip&xl=1321480300&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:03d260e3e5d455379d40cd36ded08d5f47228ad7&dn=DataSet%201.zip&xl=1321480300&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce
  ```

**SHA256:** 598F4D2D71F0D183CF898CD9D6FB8EC1F6161E0E71D8C37897936AEF75F860B4

---

### <a id="data-set-2"></a>Data Set 2

**Data Set 2 (630 MB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%202.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%202.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:d3ec6b3ea50ddbcf8b6f404f419adc584964418a&dn=DataSet+2&xl=662334369&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:d3ec6b3ea50ddbcf8b6f404f419adc584964418a&dn=DataSet+2&xl=662334369&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

---

### <a id="data-set-3"></a>Data Set 3

**Data Set 3 (595 MB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%203.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%203.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:27704fe736090510aa9f314f5854691d905d1ff3&dn=DataSet+3&xl=628519331&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:27704fe736090510aa9f314f5854691d905d1ff3&dn=DataSet+3&xl=628519331&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

---

### <a id="data-set-4"></a>Data Set 4

**Data Set 4 (351 MB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%204.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%204.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:4be48044be0e10f719d0de341b7a47ea3e8c3c1a&dn=DataSet+4&xl=375905556&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:4be48044be0e10f719d0de341b7a47ea3e8c3c1a&dn=DataSet+4&xl=375905556&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

---

### <a id="data-set-5"></a>Data Set 5

**Data Set 5 (61.4 MB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%205.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%205.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:1deb0669aca054c313493d5f3bf48eed89907470&dn=DataSet+5&xl=64579973&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:1deb0669aca054c313493d5f3bf48eed89907470&dn=DataSet+5&xl=64579973&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

---

### <a id="data-set-6"></a>Data Set 6

**Data Set 6 (51.2 MB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%206.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%206.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:05e7b8aefd91cefcbe28a8788d3ad4a0db47d5e2&dn=DataSet+6&xl=55600717&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:05e7b8aefd91cefcbe28a8788d3ad4a0db47d5e2&dn=DataSet+6&xl=55600717&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

---

### <a id="data-set-7"></a>Data Set 7

**Data Set 7 (96.9 MB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%207.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%207.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:bcd8ec2e697b446661921a729b8c92b689df0360&dn=DataSet+7&xl=103060624&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:bcd8ec2e697b446661921a729b8c92b689df0360&dn=DataSet+7&xl=103060624&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

---

### <a id="data-set-8"></a>Data Set 8

**Data Set 8 (10.67 GB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%208.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%208.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:c3a522d6810ee717a2c7e2ef705163e297d34b72&dn=DataSet%208&xl=11465535175&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:c3a522d6810ee717a2c7e2ef705163e297d34b72&dn=DataSet%208&xl=11465535175&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

---

### <a id="data-set-9-incomplete"></a>Data Set 9 (Incomplete)


* **[ORIGINAL JUSTICE DEPARTMENT LINK (Deprecated, returns 404 as of 20260206@1000z)](https://www.justice.gov/epstein/files/DataSet%209.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%209.zip
  ```

ym's compiled flattened PDFs

* **Torrent magnet (⚠ Incomplete - 94.58 GB / 180 GB ⚠):** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:286060d26392042a5e2b5354d09ec7c7c5cee7dc&dn=dataset-09%20%28Incomplete%29&xl=101565025420&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce)**

Only contains **94.58 GB** of **180 GB**.

Note: This is a VERY early seed. This only contains a compiled and flattened folder of PDF files — NO NATIVES. Bandwith isn't great, so please be patient and report any issues.

  ```text
  magnet:?xt=urn:btih:286060d26392042a5e2b5354d09ec7c7c5cee7dc&dn=dataset-09%20%28Incomplete%29&xl=101565025420&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce
  ```

* **Torrent magnet (⚠ Incomplete - 49 GB / 180 GB ⚠):** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:0a3d4b84a77bd982c9c2761f40944402b94f9c64&dn=DataSet9-incomplete.zip&xl=48995762176&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce)**

Only contains **49 GB** of **180 GB**. Multiple reports of cutoff from DOJ server at offset **48995762176**.

  ```text
  magnet:?xt=urn:btih:0a3d4b84a77bd982c9c2761f40944402b94f9c64&dn=DataSet9-incomplete.zip&xl=48995762176&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce
  ```

**SHA1**: 6ae129b76fddbba0776d4a5430e71494245b04c4

**Note:** A previously circulating "~101" GB Data Set 9 magnet has been removed from this index.
Multiple users report malformed metadata causing torrent clients to stall or crash.

/u/susadmin’s More Complete Data Set 9 (89.54 GB)

* **Torrent magnet (⚠ De-duplicated merger of (45.63 GB + 86.74 GB) versions ⚠):** **[TORRENT MAGNET](magnet:?xt=urn:btih:7ac8f771678d19c75a26ea6c14e7d4c003fbf9b6&dn=dataset9-more-complete.tar.zst&xl=96148724837&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.com%3A1337%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=http%3A%2F%2Fopen.tracker.cl%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Fzer0day.ch%3A1337%2Fannounce&tr=udp%3A%2F%2Fwepzone.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker1.myporn.club%3A9337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.theoks.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.srv00.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qu.ax%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.dler.org%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.bittor.pw%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.alaskantf.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-udp.gbitt.info%3A80%2Fannounce&tr=udp%3A%2F%2Frun.publictracker.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Fopentracker.io%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.dstud.io%3A6969%2Fannounce&tr=https%3A%2F%2Ftracker.zhuqiy.com)**

  ```text
  magnet:?xt=urn:btih:7ac8f771678d19c75a26ea6c14e7d4c003fbf9b6&dn=dataset9-more-complete.tar.zst&xl=96148724837&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.com%3A1337%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=http%3A%2F%2Fopen.tracker.cl%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Fzer0day.ch%3A1337%2Fannounce&tr=udp%3A%2F%2Fwepzone.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker1.myporn.club%3A9337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.theoks.net%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.srv00.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.qu.ax%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.dler.org%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.bittor.pw%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.alaskantf.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-udp.gbitt.info%3A80%2Fannounce&tr=udp%3A%2F%2Frun.publictracker.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Fopentracker.io%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.dstud.io%3A6969%2Fannounce&tr=https%3A%2F%2Ftracker.zhuqiy.com%3A443%2Fannounce
  ```

---

### <a id="data-set-10"></a>Data Set 10

**Data Set 10 (82 GB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK (Deprecated, returns 404 as of 20260206@1000z)](https://www.justice.gov/epstein/files/DataSet%2010.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%2010.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:d509cc4ca1a415a9ba3b6cb920f67c44aed7fe1f&dn=DataSet%2010.zip&xl=84439381640)**

  ```text
  magnet:?xt=urn:btih:d509cc4ca1a415a9ba3b6cb920f67c44aed7fe1f&dn=DataSet%2010.zip&xl=84439381640
  ```

* **[INTERNET ARCHIVE FOLDER](https://archive.org/details/data-set-10)**

  ```text
  https://archive.org/details/data-set-10
  ```

* **[INTERNET ARCHIVE DIRECT LINK](https://archive.org/download/data-set-10/DataSet%2010.zip)**

  ```text
  https://archive.org/download/data-set-10/DataSet%2010.zip
  ```

SHA256: 7D6935B1C63FF2F6BCABDD024EBC2A770F90C43B0D57B646FA7CBD4C0ABCF846

MD5: B8A72424AE812FD21D225195812B2502

---

### <a id="data-set-11"></a>Data Set 11

**Data Set 11 (27.5 GB)**

* **[ORIGINAL JUSTICE DEPARTMENT LINK (Deprecated, returns 404 as of 20260206@1000z)](https://www.justice.gov/epstein/files/DataSet%2011.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%2011.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:59975667f8bdd5baf9945b0e2db8a57d52d32957&xt=urn:btmh:12200ab9e7614c13695fe17c71baedec717b6294a34dfa243a614602b87ec06453ad&dn=DataSet%2011.zip&xl=27441913130&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.com%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=http%3A%2F%2Fopen.tracker.cl%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.srv00.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filemail.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.dler.org%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-udp.gbitt.info%3A80%2Fannounce&tr=udp%3A%2F%2Frun.publictracker.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.dstud.io%3A6969%2Fannounce&tr=udp%3A%2F%2Fleet-tracker.moe%3A1337%2Fannounce&tr=https%3A%2F%2Ftracker.zhuqiy.com%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.pmman.tech%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.moeblog.cn%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.alaskantf.com%3A443%2Fannounce&tr=https%3A%2F%2Fshahidrazi.online%3A443%2Fannounce&tr=http%3A%2F%2Fwww.torrentsnipe.info%3A2701%2Fannounce&tr=http%3A%2F%2Fwww.genesis-sp.org%3A2710%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:59975667f8bdd5baf9945b0e2db8a57d52d32957&xt=urn:btmh:12200ab9e7614c13695fe17c71baedec717b6294a34dfa243a614602b87ec06453ad&dn=DataSet%2011.zip&xl=27441913130&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.com%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=http%3A%2F%2Fopen.tracker.cl%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.srv00.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filemail.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.dler.org%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-udp.gbitt.info%3A80%2Fannounce&tr=udp%3A%2F%2Frun.publictracker.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.dstud.io%3A6969%2Fannounce&tr=udp%3A%2F%2Fleet-tracker.moe%3A1337%2Fannounce&tr=https%3A%2F%2Ftracker.zhuqiy.com%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.pmman.tech%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.moeblog.cn%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.alaskantf.com%3A443%2Fannounce&tr=https%3A%2F%2Fshahidrazi.online%3A443%2Fannounce&tr=http%3A%2F%2Fwww.torrentsnipe.info%3A2701%2Fannounce&tr=http%3A%2F%2Fwww.genesis-sp.org%3A2710%2Fannounce
  ```

SHA1: 574950c0f86765e897268834ac6ef38b370cad2a

---

### <a id="data-set-12"></a>Data Set 12

**Data Set 12 (114.1 MB)**.

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%2012.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%2012.zip
  ```

* **Torrent magnet:** **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:e7477151f8acfbaee3e704bbabd9a7388c7169f9&dn=DataSet%2012.zip&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:e7477151f8acfbaee3e704bbabd9a7388c7169f9&dn=DataSet%2012.zip&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce
  ```

* **[INTERNET ARCHIVE FOLDER LINK](https://archive.org/details/data-set-12_202601)**

  ```text
  https://archive.org/details/data-set-12_202601
  ```

SHA1: 20f804ab55687c957fd249cd0d417d5fe7438281

MD5: b1206186332bb1af021e86d68468f9fe

SHA256: b5314b7efca98e25d8b35e4b7fac3ebb3ca2e6cfd0937aa2300ca8b71543bbe2

---

## <a id="disclaimer"></a>Disclaimer

This repository does not create or alter any files — it only mirrors publicly available links and community preservation efforts.

If you have additional verified datasets, improved mirrors, or corrected hashes, contributions are welcome.
