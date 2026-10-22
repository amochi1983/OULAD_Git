# Upload-package changes — 22 October 2026

1. Aymen Ochi explicitly identified as software author/maintainer/copyright holder; human contributions documented, tool assistance separate.
2. MIT licence added with the author's express permission; original OULAD CC BY 4.0 attribution retained separately. Software authorship is distinct from tool assistance.
3. README, software citation, upload instructions and validation scope prepared for a public repository. The public baseline URL is documented; no DOI, journal acceptance or institutional ethics exemption is invented.
4. The data downloader now enforces the supplied raw SHA256 manifest before writing acquisition metadata; it cannot silently rebaseline corrupt existing CSVs. The original manifest remains unchanged, with execution metadata written separately. Added regression tests exercise a valid tiny archive and a modified existing CSV, without network access.
5. Numerical model code, configurations, result tables, frozen reference tables and split membership are unchanged. Historical source-copy hashes and training reports remain dated evidence; the changed downloader/docs are distinguished from those original files.
6. Raw bulk, local Git metadata/history, caches, third-party PDFs, compiler binaries and manuscript sources are excluded. The baseline archive was published at https://github.com/amochi1983/oulad-engagement-area-deprivation. The post-audit additions in this snapshot await a public update.

7. Post-audit additions: src/post_audit_checks.py and explicit reproduction flag, adjustment/reference and English-region sensitivity tables, calibration diagnostics and regression tests. Primary model definitions and frozen references remain unchanged. Figure 3 wording is descriptive.
