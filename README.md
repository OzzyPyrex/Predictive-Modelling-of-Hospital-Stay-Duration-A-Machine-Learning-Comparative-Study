# Predictive Modelling of Hospital Stay Duration: A Machine Learning Comparative Study

A public portfolio version of an MSc Business Analytics group project exploring machine-learning approaches for predicting hospital length of stay (LOS).

> This project is an educational comparison of historical modelling work. It is not a clinical decision-support tool and must not be used to make patient-care decisions.

## Project goals

- Explore factors associated with hospital length of stay.
- Compare a range of machine-learning algorithms.
- Demonstrate preprocessing, class-imbalance handling, model evaluation, and visual analysis.
- Document the scope and reproducibility limits of the original project.

## Methodology

The project works with the AV Healthcare Analytics II dataset from Kaggle. The historical workflow includes exploratory data analysis, missing-value handling, categorical encoding, scaling, SMOTE experiments, model fitting, and evaluation with accuracy, precision, recall, F1 score, and confusion matrices.

The Drive-based project audit confirmed comparisons including Logistic Regression, k-Nearest Neighbours, Support Vector Machines, Decision Trees, Random Forest, Gradient Boosting, XGBoost, and Multiple Linear Regression. The published notebook and script also contain the implementation details for this code snapshot.

Read the [methodology and data-provenance note](docs/methodology-and-provenance.md) before reusing the data or drawing conclusions from historical results.

## Repository contents

- `Major_Project.ipynb` — original exploratory notebook and modelling workflow
- `major_project.py` — Python training and evaluation script
- `train_data.csv.zip` — historical project dataset archive
- `docs/methodology-and-provenance.md` — scope, source, and safe-reuse notes

## Run locally

1. Create a Python environment.
2. Install the packages used by the historical script:

   ```bash
   pip install catboost xgboost imbalanced-learn scikit-learn tensorflow numpy pandas matplotlib seaborn
   ```

3. Extract `train_data.csv.zip` and place `train_data.csv` in the repository root.
4. Run either:

   ```bash
   python major_project.py
   ```

   or open:

   ```bash
   jupyter notebook Major_Project.ipynb
   ```

## Data, privacy, and responsible use

- The source data is third-party material; review the current Kaggle terms before downloading, redistributing, or using it.
- The original co-authored report and Drive artifacts were deliberately not uploaded because they contain collaborators' personal details.
- Results in the historical notebook are not independently reproduced benchmarks.
- Do not use this repository for clinical, triage, diagnosis, or treatment decisions.

## Attribution

This is a group MSc project. The public portfolio version intentionally omits collaborator contact details. Please retain appropriate attribution and obtain any needed permission before republishing shared work.

## License

The repository is released under the existing [MIT License](LICENSE), subject to the data-source and third-party-library terms above.
