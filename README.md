Atlas Vivo v0.4 – OASIS-2

Overview

Atlas Vivo is an open scientific research project focused on reproducible machine learning methods for Alzheimer's disease research using public datasets.

This repository contains the frozen v0.4 pipeline developed and internally validated using the OASIS-2 Longitudinal dataset.

The objective of this project is to build a transparent, reproducible and incrementally validated research pipeline.

---

Current Status

Project status: Frozen (v0.4)

Version frozen on: 2026-06-25

Development strategy:

- v0.1 — Synthetic prototype
- v0.2 — First validation with OASIS-2
- v0.3 — Addition of Clinical Dementia Rating (CDR)
- v0.4 — Addition of normalized Whole Brain Volume (nWBV)

Each version introduces only one methodological modification to preserve reproducibility.

---

Dataset

This project uses the OASIS-2 Longitudinal public dataset under its official Data Use Agreement.

The dataset was used exclusively for academic research.

---

Internal Validation Results

Main results obtained for the frozen v0.4 pipeline:

- Mean ROC-AUC (10 random seeds): 0.9970 ± 0.0073
- Cross-validation demonstrated high reproducibility.
- The model remained stable across multiple random initializations.

These results correspond to internal validation only.

---

Methodological Principles

The Atlas Vivo project follows four development principles:

1. One methodological change per version.
2. Full reproducibility.
3. Transparent validation.
4. Version freezing before introducing new variables.

---

Repository Contents

- Source notebooks
- Frozen validation pipeline
- Figures
- Documentation
- Model files

---

Limitations

The current model has been evaluated only through internal validation using the OASIS-2 dataset.

These results do not constitute external validation and must not be interpreted as clinical diagnostic performance.

Independent validation using additional public datasets is planned for future versions.

---

Future Work

- External validation
- Comparison with additional public datasets
- Model interpretability analyses
- Scientific manuscript preparation

---

License

MIT License.

---

Citation

Citation information and DOI will be added after the first public release.
