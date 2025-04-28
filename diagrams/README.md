# TRIM Framework Diagrams

This folder contains official diagram files (.tikz) used in the Trustworthiness Research Index Methodology (TRIM) Framework publication.

All diagrams are created using the TikZ package for LaTeX and are intended for modular insertion into Overleaf, LaTeX papers, GitHub documentation, and supplementary archives.

---

## Contents

### 1. `TRIM_Audit_Flowchart.tikz`

- **Description**:  
  Visualizes the complete TRIM audit process from research paper input to final Trustworthiness Index (TI) certificate issuance.
  
- **Flowchart Stages**:
  - Input Research Paper
  - AI + Manual Feature Extraction
  - Pillar-wise Scoring (Methods, Reporting, Reproducibility, Bias, Incentives)
  - Weighted TI Aggregation
  - Human Reviewer Validation
  - Final Certificate Output

- **Usage**:  
  Use `\input{diagrams/TRIM_Audit_Flowchart.tikz}` inside your main LaTeX document.

---

### 2. `TRIM_Operational_Flowchart.tikz`

- **Description**:  
  Visualizes the TRIM-AI operational machine learning pipeline from feature extraction to final TI scoring.

- **Flowchart Stages**:
  - Input Research Paper
  - AI/NLP Feature Extraction
  - Supervised ML (Random Forest, XGBoost)
  - Unsupervised ML (Autoencoders, Isolation Forests)
  - Combined AI Analysis
  - Explainable AI (SHAP, LIME Interpretations)
  - Human Reviewer Validation
  - Final TI Score Output

- **Usage**:  
  Use `\input{diagrams/TRIM_Operational_Flowchart.tikz}` inside your main LaTeX document.

---

## Licensing and Attribution

All diagrams and associated methodology are © 2025 Kapodistrian Academy of Science.

Use of the TRIM Framework diagrams requires citation and attribution to:

- Dr. Ioannis Adamopoulos (University of West Attica, Hellenic Open University)
- Antonios Valamontes (Kapodistrian Academy of Science)

License: CC BY 4.0 International

---

## Contact for Inquiries

- Dr. Ioannis Adamopoulos: [adamopoulos.ioannis@ac.eap.gr](mailto:adamopoulos.ioannis@ac.eap.gr)
- Antonios Valamontes: [avalamontes@kapodistrian.edu.gr](mailto:avalamontes@kapodistrian.edu.gr)
