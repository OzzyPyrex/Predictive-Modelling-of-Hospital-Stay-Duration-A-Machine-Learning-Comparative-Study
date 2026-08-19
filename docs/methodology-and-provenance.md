# Methodology and data provenance

## Purpose

This public portfolio repository documents an MSc Business Analytics comparison of machine-learning approaches for predicting hospital length of stay (LOS). It is intended as an educational and technical portfolio artifact, not as a clinical decision-support system.

## Evidence recovered from the original project archive

A private project record was reviewed during the 2026 refresh. It confirms that the work used the AV Healthcare Analytics II dataset hosted on Kaggle and compared several supervised-learning approaches, including:

- Logistic Regression
- k-Nearest Neighbours
- Support Vector Machines
- Decision Trees
- Random Forest
- Gradient Boosting
- XGBoost
- Multiple Linear Regression

The code snapshot also contains additional exploratory and modelling work. Treat the notebook and script as the authoritative implementation record for the version published here.

## Workflow

1. Explore distributions, missingness, and relationships in the source data.
2. Clean categorical and numerical features, then encode and scale inputs where appropriate.
3. Address class imbalance using SMOTE for selected experiments.
4. Train and compare candidate models.
5. Assess model behaviour with accuracy, precision, recall, F1 score, and confusion matrices.

## Data-use and reproducibility boundary

- The dataset is third-party material. Before downloading, redistributing, or using it, review the current Kaggle dataset terms and any applicable institutional requirements.
- The archival project report was not copied into this repository. It is a group-authored document and contains collaborators' personal details.
- The repository's included dataset archive is a historical project artifact. It should not be assumed to be the latest source version or suitable for any production or clinical use.
- Historical project outputs are not an independent validation, a medical recommendation, or a claim of generalisation beyond the source data and evaluation design.

## Recommended refresh

For a modern reproduction, obtain the dataset directly from its licensed source, document an immutable train/validation/test split, check for duplicate or leaked records, track preprocessing in a pipeline, and report uncertainty and per-class performance on a locked test set.
