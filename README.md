# kidney-tkv-haste-revision

Frontiers in Bioengineering and Biotechnology revision package (third revision, 23 November 2026) for:

> "Automated total kidney volume from coronal T2-HASTE MRI in healthy participants and patients with chronic kidney disease: same-session repeatability, slice-region segmentation error, and cross-protocol label requirements"

## Contents

| Path | Contents |
|---|---|
| 01_稿件/ | Revised_Manuscript_clean_R3.docx (clean full manuscript), Revised_Manuscript_tracked_R3.docx (tracked changes of this round only, revision author "Revision"), Revised_Supplementary_material.docx (Tables S1-S11, Fig S1) |
| 02_回复信/ | Response_to_Reviewers_R3.docx (point-by-point response to the Reviewer 2 second-round report, 23 November 2026) |
| 03_supplementary_code/ | Supplementary_Code.zip — pipeline, revision-analysis and figure scripts with a README (environment, exact run order, all seed definitions), pinned requirements, fold definitions and the scan-to-file mapping |
| 06_PDF_preview/ | PDF renders of the clean manuscript (25 pp), the tracked manuscript (25 pp) and the response letter |

## Data

Both datasets analysed in the manuscript are public:

- Nottingham coronal T2-HASTE kidney MRI archive: Zenodo DOI 10.5281/zenodo.5153568 (CC BY 4.0)
- CHAOS combined healthy abdominal organ segmentation (T2-SPIR): Zenodo DOI 10.5281/zenodo.3362844

No raw or patient-identifiable data are redistributed in this repository. Supplementary_Code.zip downloads both archives from Zenodo and reproduces every number, table and figure whose data source is these public collections (Python 3.10+, PyTorch 2.5.1, all random seeds fixed at 42).

## Status

The manuscript is under peer review. The archived repository DOI promised in the manuscript's Code availability statement will be inserted at acceptance.
