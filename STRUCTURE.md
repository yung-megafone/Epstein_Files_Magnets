STRUCTURE.md

Purpose

This repository indexes and distributes mirrors of the DOJ Epstein Files release. To ensure long-term preservation, verification, and usability, archives are organized into three distinct distribution types:

- raw (canonical preservation archive)
- full (complete extracted archive)
- pdf-only (derived accessibility archive)

These serve different purposes and must remain separate.

---

1. raw — canonical archive (highest priority)

Contains the original dataset zip files exactly as released.

Example:

> epstein-files-doj-YYYY-MM-DD-raw/
> 
>  dataset-01.zip
> 
>  dataset-02.zip
> 
>  ...
> 
>  dataset-12.zip
> 
>  SHA256SUMS.txt

Rules:

- Files must remain completely unchanged
- Do not extract, rename, recompress, or modify
- This archive serves as the authoritative preservation copy
- Checksums should be included when possible

This archive exists to preserve provenance and allow verification against the original release.

---

2. full — complete extracted archive

Contains the fully extracted contents of each dataset.

Example:

> epstein-files-doj-YYYY-MM-DD-full/
> 
>  dataset-01/
> 
>    [all extracted files]
> 
>  dataset-02/
> 
>  ...
> 
>  dataset-12/
> 
>  SHA256SUMS.txt
> 
>  MANIFEST.txt

Rules:

- All files must be preserved (PDF, video, images, .OPT, .DAT, .DAY, etc.)
- Dataset-level directories must be preserved
- Unnecessary nested intermediary directories (0001, 0002, etc.) may be flattened
- File contents must not be modified

This archive improves usability while preserving complete dataset integrity.

---

3. pdf-only — derived accessibility archive

Contains only PDF files extracted from each dataset.

Example:

> epstein-files-doj-YYYY-MM-DD-pdf-only/
> 
>  dataset-01/
> 
>    *.pdf
> 
>  dataset-02/
> 
>    *.pdf
> 
>  ...
> 
>  dataset-12/
> 
>  SHA256SUMS.txt
> 
>  MANIFEST.txt

Rules:

- Only PDF files are included
- Non-PDF support files (.OPT, .DAT, .DAY, video, images, etc.) are excluded intentionally
- Dataset-level directories must be preserved
- Unnecessary nested directories may be flattened
- File contents must not be modified

This archive exists to improve accessibility and reduce download size.

---

Additional derived archives

Additional derived distributions (such as fully flattened or reorganized versions) may be created if clearly labeled and documented.

Derived archives should include:

- MANIFEST.txt describing structure and derivation method
- SHA256SUMS.txt when possible

---

Torrent guidelines

Each archive type should be distributed as its own torrent, using the archive folder itself as the torrent root.

Do not mix raw, full, or pdf-only contents into a single torrent.

---

Summary

raw     = original zip files, unchanged
full    = extracted datasets, all files preserved
pdf-only = extracted PDFs only, dataset grouping preserved

These three archive types ensure preservation, usability, and accessibility.
