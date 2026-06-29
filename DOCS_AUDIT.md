# Documentation Audit

Audit date: 2026-06-29

## Files inspected

| Area | Files |
| --- | --- |
| Root documentation | `README.md`, `CITATION.md`, `LICENSE`, `LICENSE-CODE`, `DATA-SOURCES.md`, `HUMAN_REVIEW.md` |
| Dataset READMEs | `HK2012-2018/README.md`, `HK-MO2018/README.md`, `Macau2018/README.md`, `ISF-TDF2023/README.md`, `Racism2019/README.md`, `TM2015/README.md` |

## Root README issues found

| Issue | Status |
| --- | --- |
| Banner placement and README section order needed alignment with the open-code repository. | Fixed |
| Repository scope was implicit rather than a named section. | Fixed |
| Human-review and docs-audit links were missing. | Fixed |

## Dataset README issues found

| Issue | Status |
| --- | --- |
| Major dataset README files did not include the standard TULIP Lab banner. | Fixed with `../assets/tulip-wordmark.png` |
| Dataset metadata licence cells used long repository-level wording. | Standardised to `CC BY 4.0 unless otherwise stated` |
| Dataset-level provenance and citation notes needed to remain intact. | Preserved |

## Citation inconsistencies found

| Issue | Status |
| --- | --- |
| Legacy BibTeX spelling was inconsistent. | Standardised to `BibTeX` |
| Citation headings used plural `Citations` in several files. | Standardised to `## Citation` |
| Some BibTeX DOI fields included `https://doi.org/` instead of DOI values. | Fixed where the DOI was already documented |
| Some BibTeX month and page-range fields used non-preferred formatting. | Fixed where metadata was already documented |

## Licence inconsistencies found

| Issue | Status |
| --- | --- |
| Long dataset table licence cells were inconsistent with the concise root README wording. | Fixed |
| Repository-level CC BY 4.0 must not override dataset-specific source terms. | Preserved in root README, `LICENSE`, and dataset notes |
| Code/scripts are licensed separately under MIT unless otherwise stated. | Preserved in root README and `LICENSE-CODE` |

## Branch-name references found

| Issue | Status |
| --- | --- |
| Documentation links referenced `tree/master`. | Replaced with `tree/main` where they referred to current repository URLs |
| No local or remote `master` branch exists. | Confirmed |
| `origin/HEAD` points to `origin/main`. | Confirmed; no branch migration issue recorded |

## Banner coverage

| Area | Status |
| --- | --- |
| Root README | Covered with `assets/tulip-wordmark.png` |
| Major dataset READMEs | Covered with `../assets/tulip-wordmark.png` |

## Changes applied

- Added standard README banner placement and repository scope section.
- Added standard banner to major dataset READMEs.
- Standardised branch-name links from `master` to `main`.
- Standardised citation headings and `BibTeX` spelling.
- Standardised dataset metadata licence cells.
- Created this audit report.

## Issues requiring human confirmation

- `Racism2019` source-site terms, privacy constraints, and attribution requirements remain future-review items if selected for assessment use later.
- `TM2015` publisher/source terms for derived bibliographic and collaboration-network data remain future-review items if selected for assessment use later.

## Recommended next actions

- Keep dataset-specific DOI and paper citations current when owners publish updates.
- Add a repository-level archival DOI later only if desired.
