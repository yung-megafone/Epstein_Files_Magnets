# <a id="epstein-files-feb-02-2026"></a>Epstein Files Feb 8, 2026

## <a id="dataset-status-dashboard"></a>Dataset Status Dashboard

Quick availability overview of all currently indexed datasets:

![Release](https://img.shields.io/badge/Release-Jan%2030%2C%202026-black?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Archive%20Index%20%2F%20Mirror-lightgrey?style=for-the-badge)
![Primary](https://img.shields.io/badge/Primary-DOJ%20ZIPs-blue?style=for-the-badge)
![Community](https://img.shields.io/badge/Community-Torrents%20%2B%20Internet%20Archive-purple?style=for-the-badge)

![Data%20Set%201](https://img.shields.io/badge/Data%20Set%201-1.23%20GB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%202](https://img.shields.io/badge/Data%20Set%202-630%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%203](https://img.shields.io/badge/Data%20Set%203-595%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%204](https://img.shields.io/badge/Data%20Set%204-351%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%205](https://img.shields.io/badge/Data%20Set%205-61.4%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%206](https://img.shields.io/badge/Data%20Set%206-51.2%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%207](https://img.shields.io/badge/Data%20Set%207-96.9%20MB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%208](https://img.shields.io/badge/Data%20Set%208-10.67%20GB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%209](https://img.shields.io/badge/Data%20Set%209-143%20GB%20%7C%20~99.89%25%20Reconstructed-orange?style=for-the-badge)
![Data%20Set%2010](https://img.shields.io/badge/Data%20Set%2010-78.6%20GB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%2011](https://img.shields.io/badge/Data%20Set%2011-25.5%20GB%20%7C%20Available-brightgreen?style=for-the-badge)
![Data%20Set%2012](https://img.shields.io/badge/Data%20Set%2012-114%20MB%20%7C%20Available-brightgreen?style=for-the-badge)

---

This repository is a community **mirror + indexing project** for the **Jan 30, 2026** Epstein Files data release published by the **U.S. Department of Justice**.

The original release is distributed across many separate `.zip` archives. Community archivists have since produced **torrent magnets** and **Internet Archive mirrors** to make the data easier to preserve, resume, verify, and distribute long-term.

**Goal:** provide a stable public index of download methods (DOJ + torrent + mirrors), especially if links break, files disappear, or servers throttle/cut off transfers.  
**How to help:** seed torrents, mirror responsibly, and verify hashes when provided.

**Initial Inspiration (DataHoarder):**  
<https://old.reddit.com/r/DataHoarder/comments/1qrk3qk/epstein_files_datasets_9_10_11_300_gb_lets_keep/>

```text
https://old.reddit.com/r/DataHoarder/comments/1qrk3qk/epstein_files_datasets_9_10_11_300_gb_lets_keep/
```

---

## <a id="table-of-contents"></a>Table of Contents

* [Dataset Status Dashboard](#dataset-status-dashboard)
* [How to Use This Repo](#how-to-use-this-repo)
* [How to Help](#how-to-help)
* [Download Options](#download-options)
* [How to Torrent the Magnet Links](#how-to-torrent-the-magnet-links)
* [Hash Verification](#hash-verification)
* [Datasets](#datasets)
  * [Structured Dataset (Mostly Full)](#structured-dataset-full)
  * [Data Sets 1–8, 11–12 (Internet Archive)](#data-sets-1-8-internet-archive)
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
* [Contributors & Acknowledgements](#contributors)
* [Disclaimer](#disclaimer)

---

## <a id="how-to-use-this-repo"></a>How to Use This Repo

This repository is an **index + mirror helper** for the Epstein Files datasets released by the U.S. Department of Justice.

Each dataset entry includes:

* The official DOJ `.zip` download link (when available)
* One or more community torrent magnets (when available)
* Internet Archive mirrors (when available)
* Copy-safe blocks for each link for reliability
* Hashes (when known) for verification

The goal is to make these files easier to:

* download in full
* resume if interrupted
* preserve long-term
* seed back to the community

---

## <a id="how-to-help"></a>How to Help

This repository exists because people stepped in and helped without being asked.
If you want to contribute — whether that’s bandwidth, analysis, missing files, or structure — here’s how to do it in a way that actually moves the project forward.

### Seed Torrents (Huge Help)

If you download any dataset via BitTorrent:

* **Leave your client open**
* Seed as long as you reasonably can
* Even low upload speeds help stabilize the swarm

Preservation only works if files stay available after the initial hype fades.

### Help Recover Missing Files (Especially Data Set 9)

Data Set 9 is the only dataset known to be incomplete at the source.

If you have:

* Missing **PDFs**
* Missing **NATIVEs** (images, audio, video, etc.)
* Partial archives or fragments
* Older copies pulled before DOJ throttling/cutoffs

Please open an **issue** and include:

* File names
* Hashes (if available)
* Original source URL(s)
* How / when you obtained them

Even *partial* information helps — filenames alone can unblock recovery.

### Verify Hashes & Compare Results

If you’ve downloaded datasets:

* Run hash checks (SHA256 preferred)
* Compare results with checksums listed in this repo
* Report mismatches or confirmations in issues

Convergence across independent downloads is how we establish trust.

### Contribute Structure, OCR, or Metadata

High-value technical contributions include:

* OCR improvements
* Text extraction
* Dataset restructuring
* Manifest / index reconstruction
* File deduplication
* Tooling (scripts, validators, analyzers)

If you’re doing work **outside GitHub**, that’s fine — open an issue and share your findings.

### Add or Locate Other Public Releases (Beyond EFTA)

This project is **not limited to EFTA**.

We are also interested in:

* Previously released **FOIA** materials
* Court records and exhibits
* Archived DOJ or PACER documents
* Public releases that are now removed or hard to find

⚠️ Only publicly released material.
No leaks. No hacking. No illicit content.

### How *Not* to Help (Important)

To keep this usable and credible:

* Do not submit speculation without sources
* Do not request or upload illegal material
* Do not submit private data or leaks
* Do not open duplicate issues without checking first

This is an archival and verification effort — not a rumor hub.

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

### <a id="option-3-internet-archive-mirrors"></a>Option 3 — Internet Archive Mirrors

Where possible, datasets are also mirrored to archive.org.

These are helpful if you:

* can’t use BitTorrent
* need a simple HTTP resume
* want a third preservation layer

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
* Data Set 9 historically incomplete

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

#### Status

Efforts are ongoing to enumerate, test, verify, and recover remaining NATIVEs from
public DOJ endpoints and community-provided archives.

Updates will be reflected in these reference files and the associated tracking issue:

* Issue: [https://github.com/yung-megafone/Epstein-Files/issues/4](https://github.com/yung-megafone/Epstein-Files/issues/4)

```text
https://github.com/yung-megafone/Epstein-Files/issues/4
```

---

## <a id="datasets"></a>Datasets

### <a id="quick-jumps"></a>Quick Jumps

* [Structured Dataset (Mostly Full)](#structured-dataset-full)
* [Data Sets 1–8, 11–12 (Internet Archive)](#data-sets-1-8-internet-archive)
* [1](#data-set-1) · [2](#data-set-2) · [3](#data-set-3) · [4](#data-set-4) · [5](#data-set-5) · [6](#data-set-6)
* [7](#data-set-7) · [8](#data-set-8) · [9](#data-set-9-incomplete) · [10](#data-set-10) · [11](#data-set-11) · [12](#data-set-12)

---

### <a id="structured-dataset-full"></a>Structured Dataset _(Mostly Full)_ (206.18 GB)

**Epstein Files — Structured Dataset (Mostly Full) (1-12) 2026-02-04**

##### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:f5cbe5026b1f86617c520d0a9cd610d6254cbe85&dn=epstein-files-structured-full-20250204.tar.zst&xl=221393230690)**

  ```text
  magnet:?xt=urn:btih:f5cbe5026b1f86617c520d0a9cd610d6254cbe85&dn=epstein-files-structured-full-20250204.tar.zst&xl=221393230690
  ```

##### Hashes

**SHA256:** 29acc987cd7fadfbbf94444ed165750b84d82c85af3703bab74308ea9e91e910

##### Notes

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

### <a id="data-sets-internet-archive"></a>Data Sets (Internet Archive)

**Epstein Files Data Sets 1-8, 11-12: [LINK](https://archive.org/download/Epstein-Data-Sets-So-Far)**

```text
https://archive.org/download/Epstein-Data-Sets-So-Far
```


---

<!-- ========================================================= -->

<!-- ====================== DATA SETS ========================= -->

<!-- ========================================================= -->

### <a id="data-set-1"></a>Data Set 1 (1.23 GB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%201.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%201.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[TORRENT MAGNET LINK](magnet:?xt=urn:btih:6bfa388c07dc787e3bbd91df6f4c7c4638a7dc0f&dn=DataSet%201&xl=1327457599&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:6bfa388c07dc787e3bbd91df6f4c7c4638a7dc0f&dn=DataSet%201&xl=1327457599&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/download/data-set-1/DataSet%201.zip)**

  ```text
  https://archive.org/download/data-set-1/DataSet%201.zip
  ```

#### Hashes

**SHA256:** 598F4D2D71F0D183CF898CD9D6FB8EC1F6161E0E71D8C37897936AEF75F860B4

#### Notes

*(optional)*

---

### <a id="data-set-2"></a>Data Set 2 (630 MB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%202.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%202.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:d3ec6b3ea50ddbcf8b6f404f419adc584964418a&dn=DataSet%202&xl=662334369&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:d3ec6b3ea50ddbcf8b6f404f419adc584964418a&dn=DataSet%202&xl=662334369&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/download/data-set-1/DataSet%202.zip)**

  ```text
  https://archive.org/download/data-set-1/DataSet%202.zip
  ```

#### Hashes

**SHA256:** 24CEBBAEFE9D49BCA57726B5A4B531FF20E6A97C370BA87A7593DD8DBDB77BFF

#### Notes

*(optional)*

---

### <a id="data-set-3"></a>Data Set 3 (595 MB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%203.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%203.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:27704fe736090510aa9f314f5854691d905d1ff3&dn=DataSet+3&xl=628519331&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:27704fe736090510aa9f314f5854691d905d1ff3&dn=DataSet+3&xl=628519331&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/download/data-set-1/DataSet%203.zip)**

  ```text
  https://archive.org/download/data-set-1/DataSet%203.zip
  ```

#### Hashes

**SHA256:** 160231C8C689C76003976B609E55689530FC4832A1535CE13BFCD8F871C21E65

#### Notes

*Prior hash was incorrect. Updated hash is verified against current DOJ content **and** the internet archive mirror*

---

### <a id="data-set-4"></a>Data Set 4 (351 MB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%204.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%204.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:4be48044be0e10f719d0de341b7a47ea3e8c3c1a&dn=DataSet%204&xl=375905556&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:4be48044be0e10f719d0de341b7a47ea3e8c3c1a&dn=DataSet%204&xl=375905556&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/download/data-set-1/DataSet%204.zip)**

  ```text
  https://archive.org/download/data-set-1/DataSet%204.zip
  ```

#### Hashes

**SHA256:** 979154842BAC356EF36BB2D0E72F78E0F6B771D79E02DD6934CFF699944E2B71

#### Notes

*(optional)*

---

### <a id="data-set-5"></a>Data Set 5 (61.4 MB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%205.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%205.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:1deb0669aca054c313493d5f3bf48eed89907470&dn=DataSet%205&xl=64579973&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:1deb0669aca054c313493d5f3bf48eed89907470&dn=DataSet%205&xl=64579973&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/download/data-set-1/DataSet%205.zip)**

  ```text
  https://archive.org/download/data-set-1/DataSet%205.zip
  ```

#### Hashes

**SHA256:** 7317E2AD089C82A59378A9C038E964FEAB246BE62ECC24663B741617AF3DA709

#### Notes

*(optional)*

---

### <a id="data-set-6"></a>Data Set 6 (51.2 MB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%206.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%206.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:05e7b8aefd91cefcbe28a8788d3ad4a0db47d5e2&dn=DataSet%206&xl=55600717&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:05e7b8aefd91cefcbe28a8788d3ad4a0db47d5e2&dn=DataSet%206&xl=55600717&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/download/data-set-1/DataSet%206.zip)**

  ```text
  https://archive.org/download/data-set-1/DataSet%206.zip
  ```

#### Hashes

**SHA256:** D54D26D94127B9A277CF3F7D9EEAF9A7271F118757997EDAC3BC6E1039ED6555

#### Notes

*(optional)*

---

### <a id="data-set-7"></a>Data Set 7 (96.9 MB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%207.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%207.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:bcd8ec2e697b446661921a729b8c92b689df0360&dn=DataSet%207&xl=103060624&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:bcd8ec2e697b446661921a729b8c92b689df0360&dn=DataSet%207&xl=103060624&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/download/data-set-1/DataSet%207.zip)**

  ```text
  https://archive.org/download/data-set-1/DataSet%207.zip
  ```

#### Hashes

**SHA256:** 51E1961B3BCF18A21AFD9BCF697FDB54DAC97D1B64CF88297F4C5BE268D26B8E

#### Notes

*(optional)*

---

### <a id="data-set-8"></a>Data Set 8 (10.67 GB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%208.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%208.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:c3a522d6810ee717a2c7e2ef705163e297d34b72&dn=DataSet%208&xl=11465535175&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:c3a522d6810ee717a2c7e2ef705163e297d34b72&dn=DataSet%208&xl=11465535175&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.moeking.me%3A6969%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/details/data-set-8)**

  ```text
  https://archive.org/details/data-set-8
  ```

#### Hashes

**SHA256:** 8cb7345bf7a0b32f183658ac170fb0b6527895c95f0233d7b99d544579567294

#### Notes

*(optional)*

---

### <a id="data-set-9-incomplete"></a>Data Set 9 (~180 GB) _(INCOMPLETE)_

#### Official DOJ (Deprecated)

* **[ORIGINAL JUSTICE DEPARTMENT LINK (Deprecated, returns 404 as of 20260206 @ 1000z)](https://www.justice.gov/epstein/files/DataSet%209.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%209.zip
  ```

#### Sources (Pick One or Combine)

##### Source A — u/FuckThisSite3's _MORE Complete_ DataSet 9 (143 GB / 180 GB)

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:5b50564ee995a54009fec387c97f9465eb18ba00&dn=dataset-9_by_fuckthissite3.tar&xl=148072017920)**

  ```text
  magnet:?xt=urn:btih:5b50564ee995a54009fec387c97f9465eb18ba00&dn=dataset-9_by_fuckthissite3.tar&xl=148072017920
  ```

* **SHA256:** 5ADC043BCF94304024D718E57267C1AA009D782835F6ADBE6AD7FDBB763F15C5 _(ym) pending verification_

* **Notes:** *Contains ~2,308 NATIVES, ~252,169 PDFs

##### Source B — ym's compiled flattened PDFs (VERY SLOW) (94.58 GB / 180 GB)

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:286060d26392042a5e2b5354d09ec7c7c5cee7dc&dn=dataset-09%20%28Incomplete%29&xl=101565025420&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:286060d26392042a5e2b5354d09ec7c7c5cee7dc&dn=dataset-09%20%28Incomplete%29&xl=101565025420&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce
  ```

* **SHA256:** See [checksums-incomplete.zip](/notes/DS09/checksums-incomplete.zip)

* **Notes:**

  * 531,282 PDFs (flattened). **No NATIVEs.**
  * VOL00009.DAT, VOL00009.OPT
  * Early seed; bandwidth limited — please be patient and report issues.


#### Notes

See: [Notes on Data Set 9](/notes/DS09/README.md)

---

### <a id="data-set-10"></a>Data Set 10 (78.65 GB)

#### Official DOJ (Deprecated)

* **[ORIGINAL JUSTICE DEPARTMENT LINK (Deprecated, returns 404 as of 20260206 @ 1000z)](https://www.justice.gov/epstein/files/DataSet%2010.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%2010.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:d509cc4ca1a415a9ba3b6cb920f67c44aed7fe1f&dn=DataSet%2010.zip&xl=84439381640)**

  ```text
  magnet:?xt=urn:btih:d509cc4ca1a415a9ba3b6cb920f67c44aed7fe1f&dn=DataSet%2010.zip&xl=84439381640
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/details/data-set-10)**

  ```text
  https://archive.org/details/data-set-10
  ```

* **Backup (IA):**
  **[LINK](https://archive.org/download/data-set-10/DataSet%2010.zip)**

  ```text
  https://archive.org/download/data-set-10/DataSet%2010.zip
  ```

#### Hashes

**SHA256:** 7D6935B1C63FF2F6BCABDD024EBC2A770F90C43B0D57B646FA7CBD4C0ABCF846

**MD5:** b8a72424ae812fd21d225195812b2502

#### Notes

*(optional)*

---

### <a id="data-set-11"></a>Data Set 11 (27.5 GB)

#### Official DOJ (Deprecated)

* **[ORIGINAL JUSTICE DEPARTMENT LINK (Deprecated, returns 404 as of 20260206 @ 1000z)](https://www.justice.gov/epstein/files/DataSet%2011.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%2011.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:59975667f8bdd5baf9945b0e2db8a57d52d32957&xt=urn:btmh:12200ab9e7614c13695fe17c71baedec717b6294a34dfa243a614602b87ec06453ad&dn=DataSet%2011.zip&xl=27441913130&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.com%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=http%3A%2F%2Fopen.tracker.cl%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.srv00.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filemail.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.dler.org%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-udp.gbitt.info%3A80%2Fannounce&tr=udp%3A%2F%2Frun.publictracker.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.dstud.io%3A6969%2Fannounce&tr=udp%3A%2F%2Fleet-tracker.moe%3A1337%2Fannounce&tr=https%3A%2F%2Ftracker.zhuqiy.com%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.pmman.tech%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.moeblog.cn%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.alaskantf.com%3A443%2Fannounce&tr=https%3A%2F%2Fshahidrazi.online%3A443%2Fannounce&tr=http%3A%2F%2Fwww.torrentsnipe.info%3A2701%2Fannounce&tr=http%3A%2F%2Fwww.genesis-sp.org%3A2710%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:59975667f8bdd5baf9945b0e2db8a57d52d32957&xt=urn:btmh:12200ab9e7614c13695fe17c71baedec717b6294a34dfa243a614602b87ec06453ad&dn=DataSet%2011.zip&xl=27441913130&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.com%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=http%3A%2F%2Fopen.tracker.cl%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.srv00.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filemail.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.dler.org%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker-udp.gbitt.info%3A80%2Fannounce&tr=udp%3A%2F%2Frun.publictracker.xyz%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.dstud.io%3A6969%2Fannounce&tr=udp%3A%2F%2Fleet-tracker.moe%3A1337%2Fannounce&tr=https%3A%2F%2Ftracker.zhuqiy.com%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.pmman.tech%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.moeblog.cn%3A443%2Fannounce&tr=https%3A%2F%2Ftracker.alaskantf.com%3A443%2Fannounce&tr=https%3A%2F%2Fshahidrazi.online%3A443%2Fannounce&tr=http%3A%2F%2Fwww.torrentsnipe.info%3A2701%2Fannounce&tr=http%3A%2F%2Fwww.genesis-sp.org%3A2710%2Fannounce
  ```

* **Internet Archive:**
  **[LINK]()** _(pending)_

#### Hashes

**SHA1:** 574950c0f86765e897268834ac6ef38b370cad2a

**SHA256:** 9714273B9E325F0A1F406063C795DB32F5DA2095B75E602D4C4FBABA5DE3ED80

#### Notes

*(optional)*

---

### <a id="data-set-12"></a>Data Set 12 (114.1 MB)

#### Official DOJ

* **[ORIGINAL JUSTICE DEPARTMENT LINK](https://www.justice.gov/epstein/files/DataSet%2012.zip)**

  ```text
  https://www.justice.gov/epstein/files/DataSet%2012.zip
  ```

#### Sources

* **Torrent Magnet:**
  **[LINK](magnet:?xt=urn:btih:e7477151f8acfbaee3e704bbabd9a7388c7169f9&dn=DataSet%2012.zip&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce)**

  ```text
  magnet:?xt=urn:btih:e7477151f8acfbaee3e704bbabd9a7388c7169f9&dn=DataSet%2012.zip&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce
  ```

* **Internet Archive:**
  **[LINK](https://archive.org/details/data-set-12_202601)**

  ```text
  https://archive.org/details/data-set-12_202601
  ```

#### Hashes

**SHA1:** 20f804ab55687c957fd249cd0d417d5fe7438281

**MD5:** b1206186332bb1af021e86d68468f9fe

**SHA256:** B5314B7EFCA98E25D8B35E4B7FAC3EBB3CA2E6CFD0937AA2300CA8B71543BBE2

#### Notes

*(optional)*

---

## <a id="contributors"></a>Contributors & Acknowledgements

This project exists thanks to community contributions across issues, pull requests,
mirrors, analysis, and verification efforts.

Notable contributors include:

* Community members who reported mirror issues, duplication, and missing files
* Contributors who provided alternative mirrors, torrents, and structured datasets
* Archivists and data hoarders assisting with verification and preservation

For full attribution and discussion history, see the Issues and Pull Requests tabs.

---

## <a id="disclaimer"></a>Disclaimer

This repository does not create or alter any files — it only mirrors publicly available links and community preservation efforts.

If you have additional verified datasets, improved mirrors, or corrected hashes, contributions are welcome.
