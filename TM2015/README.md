<p align="center">
  <img src="../assets/tulip-wordmark.png" alt="TULIP Lab" width="900">
</p>

# TM2015

| Field | Value |
| --- | --- |
| Title | TM2015 |
| Type | Dataset |
| Language | English |
| Licence | CC BY 4.0 unless otherwise stated |
| Data Status | Static |
| Update Frequency | NO |
| Date Published | 2019-10-07 |
| Date Updated | 2019-10-08 |
| Portal | https://github.com/tulip-lab/open-data |
| URL | https://github.com/tulip-lab/open-data/tree/main/TM2015 |
| Publisher | [TULIP Lab](http://www.tulip.academy/) |
| Point of Contact | [Prof. Gang Li](https://github.com/tuliplab) |

## Overview

This dataset is in Matlab matrix format and contains collaboration-network matrices and researcher publication data for two collaboration networks. Networks are constructed from research articles published in `Tourism Management` from 1982 to 2015. The dataset has been preprocessed.

## Files

- `TM2015_raw_collaboration_network.mat`
- `TM2015_research-article_collaboration_network.mat`

## Source and provenance

The dataset was constructed from `Tourism Management` research articles and used in Fan, Li, and Law (2020). Publisher/source terms for the derived bibliographic and collaboration-network data are not fully documented in this README.

## Citation

If you use this dataset for a scientific publication, please include a reference to the following paper.

> Wei Fan, Gang Li, and Rob Law (2020). [*Analyzing Co-authoring Communities of Tourism Research Collaboration*](https://doi.org/10.1016/j.tmp.2019.100607). *Tourism Management Perspectives*, Vol 33, January 2020.

`BibTeX` information:

```bibtex
@article{FANCollaboration2020,
  title = {Analyzing co-authoring communities of tourism research collaboration},
  volume = {33},
  doi = {10.1016/j.tmp.2019.100607},
  journal = {Tourism Management Perspectives},
  author = {Fan, Wei and Li, Gang and Law, Rob},
  month = jan,
  year = {2020},
  keywords = {Research collaboration, Network analysis, Co-authoring community, Centrality measure, Tourism research},
  pages = {100607}
}
```

## Licence and attribution

Dataset files and dataset documentation are licensed under CC BY 4.0 unless otherwise stated. Dataset-level provenance and citation notes remain part of the attribution record and are not overridden by repository-level licence wording.

Suggested attribution:

> TULIP Lab. *TULIP Lab Open Data Repository*. https://github.com/tulip-lab/open-data. Licensed under CC BY 4.0. Also cite Fan, Li, and Law (2020).

## Related code

No single related open-code subproject is documented in this dataset README.

## Notes

- Matrix files contain connection information among researchers.
- Each cell in the publication list contains publication indicators of a researcher.
- Publisher/source terms remain a non-blocking owner-confirmation item if this dataset is selected for future release-sensitive use.
