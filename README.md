# Atlas Vivo v0.5.2 – Balanced Early Cognitive Impairment Assessment

## Overview

Atlas Vivo is an open scientific research project focused on reproducible machine learning methods for Alzheimer's disease research using public datasets.

Current stable release: **v0.5.2**

---

## Current Status

- Latest version: **v0.5.2**
- Status: Frozen Release
- Dataset: OASIS-2 Longitudinal

---

## Model

Classifier:
- Logistic Regression (class_weight="balanced")

Features:
- Age
- EDUC
- MMSE
- nWBV
- eTIV

Task:
- CN (CDR=0) vs MCI (CDR=0.5)

---

## Performance (v0.5.2)

- ROC-AUC: **0.8650 ± 0.0035**
- Sensitivity: **71.1%**
- Specificity: **83.8%**

Validation:
- Nested 5-fold Cross Validation
- 10 random seeds

Research use only.

---

## Reproducibility

Notebook:
- AtlasVivo_v0_5_EarlyCI.ipynb

Repository contains:
- notebook
- frozen model (.pkl)
- requirements.txt
- README
- License

---

## DOI

Latest Version DOI

**10.5281/zenodo.20945738**

Concept DOI (all versions)

**10.5281/zenodo.20945737**

---

## Limitations

This model has been internally validated only using the OASIS-2 dataset.

It is not intended for clinical diagnosis.

External validation is planned for future versions.

---

## License

MIT License
