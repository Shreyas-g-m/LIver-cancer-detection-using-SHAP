
# SHAP-Guided Multi-Modal Liver Cancer Classification

A deep learning framework for patient-level liver cancer classification from CT scans using a multi-modal fusion of 2D CNN features and 3D radiomics descriptors. The pipeline performs DICOM preprocessing, Hounsfield Unit normalization, entropy-based slice selection, EfficientNet-B0 feature extraction, PyRadiomics feature extraction, attention-based fusion, and SHAP-guided regularization to improve both predictive performance and interpretability.

The model was evaluated on approximately 790 patients from the TCGA-LIHC and HCC-TACE-Seg cohorts, achieving an AUC-ROC of **0.912**, **F1-score of 0.845**, **MCC of 0.732**, and **Brier Score of 0.134**, while demonstrating robust cross-cohort generalization through strict patient-level evaluation.

