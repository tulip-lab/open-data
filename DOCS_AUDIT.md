# Documentation Audit

Audit date: 2026-06-29

## Files inspected

| Area | Files |
| --- | --- |
| Root documentation | `README.md`, `CITATION.md`, `LICENSE`, `LICENSE-CODE`, `DATA-SOURCES.md`, `HUMAN_REVIEW.md` |
| Dataset READMEs | `HK2012-2018/README.md`, `HK-MO2018/README.md`, `Macau2018/README.md`, `ISF-TDF2023/README.md`, `Racism2019/README.md`, `TM2015/README.md` |

## README templates applied

Major dataset README files were standardised toward this structure:

- Banner
- Dataset title
- Metadata table
- `Overview`
- `Files`
- `Source and provenance`
- `Citation`
- `Licence and attribution`
- `Related code`
- `Notes`

Existing data dictionaries, evaluation-method notes, source notes, DOI notes, and disclaimers were preserved where present.

## Dataset README files updated

| File | Summary |
| --- | --- |
| `ISF-TDF2023/README.md` | Added `Files`, renamed release notes to `Source and provenance`, preserved evaluation period, MASE, seasonal naive benchmark notes, fenced BibTeX, and added licence/related-code/notes sections. |
| `HK2012-2018/README.md` | Added standard sections, file list, public-release provenance, fenced BibTeX, licence/attribution, related code, and notes; retained data dictionary. |
| `HK-MO2018/README.md` | Added standard sections, file list, public-release provenance, fenced BibTeX, licence/attribution, related code, and notes; retained data dictionary. |
| `Macau2018/README.md` | Added standard sections, file list, public-release provenance, fenced BibTeX, licence/attribution, related code, and notes; retained DSEC, Google Trends, and Baidu Index source notes. |
| `Racism2019/README.md` | Added standard sections, file list, source/provenance review note, fenced BibTeX, licence/attribution, related-code status, notes, and data dictionary. |
| `TM2015/README.md` | Added standard sections, file list, source/provenance review note, fenced BibTeX, licence/attribution, related-code status, and notes. |

## Citation issues fixed

| Issue | Status |
| --- | --- |
| README citation sections had inconsistent surrounding structure. | Standardised to `## Citation` in the dataset template. |
| Indented BibTeX blocks were inconsistent with the preferred fenced form. | Converted known BibTeX entries to fenced `bibtex` blocks. |
| BibTeX DOI, month, page, and keyword formatting needed normalisation in several entries. | Normalised where metadata was already documented. |
| Dataset-specific citations must remain dataset-specific. | Preserved in dataset README files and summarized in `DATA-SOURCES.md`. |

## Licence wording issues fixed

| Issue | Status |
| --- | --- |
| Dataset README files needed consistent licence/attribution sections. | Added `Licence and attribution` sections. |
| Repository-level CC BY 4.0 must not override dataset-specific source terms. | Preserved in dataset README files, `DATA-SOURCES.md`, and `HUMAN_REVIEW.md`. |
| Code/scripts are licensed separately under MIT unless otherwise stated. | Preserved in root README and `LICENSE-CODE`; no reusable code files were found during this pass. |

## DATA-SOURCES cleanup

`DATA-SOURCES.md` was rewritten to list each major dataset with:

- dataset name;
- path;
- short description;
- source/provenance status;
- citation/DOI status;
- licence status;
- human-review status.

Owner-confirmed public datasets are marked as resolved/owner-confirmed rather than blocking human-review issues.

## Branch-name references

| Issue | Status |
| --- | --- |
| Documentation should refer to `main`, not `master`, for current GitHub URLs and branch references. | Checked; no current README `master` links remain. |
| GitHub remote default branch should be `main`. | Confirmed by `git remote show origin`; no branch migration issue remains. |

## Banner coverage

| Area | Status |
| --- | --- |
| Root README | Covered with `assets/tulip-wordmark.png` |
| Major dataset READMEs | Covered with `../assets/tulip-wordmark.png` |

## HUMAN_REVIEW cleanup

`HUMAN_REVIEW.md` was reorganised into:

- Blocking before public release
- Requires owner confirmation
- Non-blocking documentation cleanup
- Optional future enhancement
- Resolved / owner-confirmed

## Remaining issues requiring owner confirmation

- `Racism2019` source-site terms, privacy constraints, and attribution requirements if selected for future release-sensitive use.
- `TM2015` publisher/source terms for derived bibliographic and collaboration-network data if selected for future release-sensitive use.

## Recommended next actions

- Keep dataset-specific DOI and paper citations current when owners publish updates.
- Add a repository-level archival DOI or `CITATION.cff` later only if desired.
- Expand original source details for owner-confirmed public datasets as a non-blocking documentation enhancement.
