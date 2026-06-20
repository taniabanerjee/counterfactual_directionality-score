# Counterfactual Directionality Score (CDS)

**MICCAI 2026**

Counterfactual Directionality Score (CDS) is a framework for quantifying directional cell–cell influence in spatial transcriptomics through counterfactual neighborhood perturbations and statistical testing.

## Abstract

Spatial transcriptomics enables measurement of gene expression while preserving tissue architecture, creating new opportunities to study cell–cell interactions within their native spatial context. We introduce a counterfactual framework for directional cell–cell influence analysis in spatial transcriptomics. A Neighborhood Influence Model (NIM) is trained to predict receiver-cell state from spatially weighted neighborhood context. Directional influence is quantified by systematically perturbing sender-cell composition and measuring the resulting displacement in predicted receiver state. To support statistical rigor, counterfactual perturbations are evaluated against matched null models and assessed under strict core-level train/test separation. The proposed Counterfactual Directionality Score (CDS) enables biologically interpretable analysis of directional influence without relying on predefined ligand–receptor interaction databases.

## Paper

📄 **MICCAI 2026 Full Paper**

* [Download PDF](paper/CDS_MICCAI2026.pdf)

## Supplementary Material

* Additional figures and analyses (coming soon)

## Code

Implementation repository:

* [Code Repository](https://github.com/<student-username>/<repository-name>)

## Citation

If you use this work, please cite:

```bibtex
@inproceedings{CDS_MICCAI_2026,
  title     = {Counterfactual Directionality Score for Directional Cell--Cell Influence Analysis in Spatial Transcriptomics},
  author    = {H. Anzum, V. Kochat, S. Satpati, M. I. Mahmud, J. M. R. Dwarampudi, P. Shukla, M. Javle, L. Kwong, K. Rai, T. Banerjee},
  booktitle = {Medical Image Computing and Computer-Assisted Intervention (MICCAI)},
  year      = {2026}
}
```

## Contact

For questions regarding the paper, please contact the authors.
