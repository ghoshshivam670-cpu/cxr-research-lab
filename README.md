# CXR-Research Lab
### Explainable & Reliable AI for Chest X-ray Analysis

An independent research project investigating the **generalization, calibration, and explainability of deep learning models** for multi-label chest X-ray classification.

> Can a model trained on one chest X-ray dataset generalize to another dataset, and can calibration and explainability help us understand its limitations?

## 🔬 Research Overview

Deep learning has shown promising results in medical image analysis. However, strong performance on a single dataset does not necessarily mean that a model will perform reliably on data from a different source.

CXR-Research Lab aims to investigate this challenge through controlled experiments and transparent evaluation.

### Research Objectives

- Develop baseline deep learning models for chest X-ray classification.
- Compare custom CNNs with transfer-learning architectures.
- Investigate performance changes across datasets.
- Evaluate model confidence and probability calibration.
- Explore model explanations using Grad-CAM.
- Document limitations, failure cases, and reproducibility.

## 🎯 Research Questions

1. How well do different CNN architectures classify chest X-ray findings?
2. Does model performance decrease when evaluated on an external dataset?
3. Can probability calibration improve the reliability of model confidence?
4. How consistent and meaningful are visual explanations produced by Grad-CAM?

## 🧪 Planned Research Methodology

| Stage | Planned work |
|---|---|
| 01 | Dataset exploration and quality analysis |
| 02 | Patient-level data splitting and preprocessing |
| 03 | Custom CNN baseline |
| 04 | ResNet and DenseNet experiments |
| 05 | External dataset evaluation |
| 06 | Calibration analysis |
| 07 | Grad-CAM explainability |
| 08 | Results, limitations and research report |

## 🗂️ Planned Datasets

- **NIH ChestX-ray14** — primary dataset.
- **CheXpert** — external evaluation dataset, subject to access approval and permitted use.

Dataset access, label harmonization, and patient-level separation will be documented before experiments.

## 🧠 Technologies

- Python
- PyTorch
- NumPy and Pandas
- Scikit-learn
- Matplotlib
- Google Colab
- Grad-CAM

## 📊 Evaluation Metrics

Planned evaluation includes:

- AUROC
- AUPRC
- Sensitivity and specificity
- F1-score
- Brier score
- Expected Calibration Error (ECE)
- Patient-level bootstrap confidence intervals

## 🤝 Collaboration

I'm looking to collaborate with motivated students, developers, and researchers interested in:

- Medical AI and biomedical engineering
- Deep learning and computer vision
- Python and PyTorch
- Explainable AI
- Medical image analysis

Contributions to experimentation, data engineering, model development, evaluation, literature review, and research documentation are welcome.

**Interested in collaborating?** Open an issue in this repository or reach out through GitHub.

## ⚠️ Research Disclaimer

This is an experimental research project, not a clinically validated medical device.

It is not intended for diagnosis, treatment decisions, or patient care. Results will be interpreted with attention to dataset limitations, label uncertainty, bias, and external validity.

## 📌 Project Status

**Current stage:** Repository setup and research planning.

Experiments, benchmark results, and conclusions have not yet been established. Progress and methodology will be documented transparently as the project develops.

---

Built as an independent research initiative.

**Research. Experiment. Evaluate. Improve.**
