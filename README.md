# Predictive Modelling of Hospital Stay Duration: A Machine Learning Comparative Study

This repository contains code and documentation for an MSc Postgraduate project in Business Analytics at the University of Galway. The project compares multiple machine learning algorithms to predict the **Length of Stay (LOS)** in hospitals and aims to identify the most effective approach for healthcare analytics.

## 📌 1. Introduction
Predicting hospital length of stay is crucial for healthcare providers to efficiently allocate resources and improve patient outcomes. This project uses **Kaggle’s AV Healthcare Analytics II dataset** to build, evaluate, and compare the performance of various machine learning models.

## 🎯 2. Research Objectives
- **Predict LOS**: Forecast the hospital stay duration.
- **Model Comparison**: Evaluate and compare ML algorithms using metrics such as accuracy, precision, recall, and F1-score.
- **Data Preprocessing**: Handle missing values, encode categorical features, scale numerical data, and use SMOTE for class imbalance.
- **Hyperparameter Tuning**: Optimize top models (e.g., CatBoost, XGBoost) for improved performance.

## ⚙️ 3. Methodology

### Data Preprocessing
- Impute missing categorical values using mode.
- Drop irrelevant features.
- Label encode categorical variables.
- Standardize numerical features.
- Apply SMOTE for class imbalance.

### Exploratory Data Analysis (EDA)
- Count plots, distribution plots, and heatmaps to explore data and feature relationships.

### Model Training & Evaluation
- Train models: Logistic Regression, Decision Trees, Random Forest, k-NN, CatBoost, XGBoost, Gradient Boosting, and Neural Networks.
- Evaluate with and without SMOTE.
- Use metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.

## 📁 4. Repository Contents

    ├── Major_Project.ipynb       # Jupyter notebook with project workflow
    ├── major_project.py          # Python script for model training and evaluation
    ├── train_data.csv.zip        # Zipped training dataset (extract before use)
    └── README.md                 # Project overview and instructions

## 🚀 5. Getting Started

### Installation
Make sure Python 3.x is installed, then install required libraries:

    pip install catboost xgboost imbalanced-learn scikit-learn tensorflow numpy pandas matplotlib seaborn

### Usage

1. **Clone the Repository**:
    
       git clone https://github.com/OzzyPyrex/Predictive-Modelling-of-Hospital-Stay-Duration-A-Machine-Learning-Comparative-Study.git
       cd Predictive-Modelling-of-Hospital-Stay-Duration-A-Machine-Learning-Comparative-Study

2. **Extract the Dataset**:
   Unzip `train_data.csv.zip` and ensure `train_data.csv` is in the repository root.

3. **Run the Script**:
    
       python major_project.py

   Or use the interactive **Jupyter Notebook**:
    
       jupyter notebook Major_Project.ipynb

## 👨‍💻 6. Authors
- **Adithya Muralidharan K V** – a.kv1@universityofgalway.ie  
- **Ruben Mathew** – r.mathew8@universityofgalway.ie  
- **Vinod Rajan** – v.rajan2@universityofgalway.ie  

## 📄 7. License
This project is licensed under the [MIT License](LICENSE).

