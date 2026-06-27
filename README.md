Atlas Vivo v0.5.2 – Balanced Early Cognitive Impairment Assessment

Overview

Atlas Vivo is an open scientific research project focused on developing transparent, reproducible and incrementally validated machine learning methods for Alzheimer's disease research using public datasets.

Current stable release: v0.5.2

This repository preserves the frozen v0.5.2 pipeline to ensure full reproducibility of the reported results.

---

Current Status

- Latest Version: v0.5.2
- Status: Frozen Release
- Release Date: 2026-06-26
- Dataset: OASIS-2 Longitudinal

---

Research Objective

Develop a reproducible machine learning pipeline capable of discriminating:

CN (CDR = 0) versus MCI (CDR = 0.5)

This project is intended exclusively for scientific research.

---

Model

Classifier

- Logistic Regression (class_weight="balanced")

Features

- Age
- EDUC
- MMSE
- nWBV
- eTIV

---

Validation Strategy

- Nested 5-Fold Cross Validation
- 10 Random Seeds
- Frozen reproducible pipeline

---

Performance (v0.5.2)

- ROC-AUC: 0.8650 ± 0.0035
- Sensitivity: 71.1%
- Specificity: 83.8%

These results correspond to internal validation using the OASIS-2 Longitudinal dataset.

---

Repository Contents

- AtlasVivo_v0_5_EarlyCI.ipynb
- Frozen trained model (.pkl)
- requirements.txt
- README.md
- LICENSE

---

Reproducibility

This repository contains the complete frozen pipeline used to generate the published results.

All reported metrics can be reproduced from the notebook included in this repository.

The project follows a version-freezing strategy in which each release preserves a stable and reproducible scientific record.

---

DOI

Version DOI (v0.5.2)

https://doi.org/10.5281/zenodo.20945738

Concept DOI (All Versions)

https://doi.org/10.5281/zenodo.20945737

---

Citation

If you use Atlas Vivo in academic work, please cite:

Atlas Vivo v0.5.2 – Balanced Early Cognitive Impairment Assessment.

DOI:

https://doi.org/10.5281/zenodo.20945738

Concept DOI:

https://doi.org/10.5281/zenodo.20945737

---

Limitations

- Internal validation only.
- OASIS-2 Longitudinal dataset.
- Not intended for clinical diagnosis.
- External validation is planned for future releases.

---

Future Work

- External validation using independent public datasets.
- Model interpretability analysis.
- Scientific manuscript preparation.
- Incremental methodological improvements while preserving reproducibility.

---

License

MIT License

---

Disclaimer

This software is provided exclusively for research purposes.

It is NOT intended for clinical diagnosis, medical decision making, or patient care.

Clinical use requires independent validation and appropriate regulatory approval.
