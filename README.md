# Predictive Modelling of Hospital Stay Duration: A Machine Learning Comparative Study

This repository contains the code and documentation for our MSc Postgraduate project in Business Analytics at the University of Galway. The project compares various machine learning algorithms to predict the length of hospital stay (LOS) and determine the most effective method for healthcare analytics.

---

## 1. Introduction

Hospital length of stay prediction is essential for optimizing resource allocation and improving patient care. In this project, we utilize Kaggle’s AV Healthcare Analytics II dataset to develop and compare different predictive models. Our study evaluates traditional machine learning methods (such as Logistic Regression, Random Forest, Decision Trees, and k-NN) alongside advanced techniques (CatBoost, XGBoost, Gradient Boosting, and Neural Networks).

---

## 2. Research Objective

- **Predict LOS:** Accurately forecast the hospital stay duration using multiple machine learning algorithms.
- **Model Comparison:** Evaluate performance metrics such as accuracy, precision, recall, and F1-score to determine the best model.
- **Data Preprocessing:** Implement comprehensive preprocessing including missing value imputation, categorical encoding, feature scaling, and applying SMOTE to address class imbalance.
- **Hyperparameter Tuning:** Optimize top-performing models through RandomizedSearchCV for enhanced predictive performance.

---

## 3. Methodology

**Data Preprocessing:**  
- Missing values in categorical variables are imputed using the mode.
- Irrelevant columns are removed, and categorical variables are label-encoded.
- Numerical features are standardized.

**Exploratory Data Analysis (EDA):**  
- Visualizations (count plots, distribution plots, and correlation heatmaps) are used to understand the data structure and relationships.

**Model Training and Evaluation:**  
- Multiple models are trained on the dataset both with and without SMOTE.
- Performance is compared using confusion matrices, accuracy, precision, recall, and F1-score.
- Hyperparameter tuning is performed on top models (XGBoost and CatBoost).

---

## 4. Repository Contents

├── major_project.py  
├── Research Project - Final Deliverable – Research Manuscript.pdf  
├── train_data.csv          # Dataset file (ensure this is placed in the repository)  
└── README.md

- **major_project.py:** Main Python script implementing data preprocessing, model training, evaluation, and visualization.
- **Research Project - Final Deliverable – Research Manuscript.pdf:** Detailed project manuscript.
- **train_data.csv:** Dataset file required for running the project (place in the repository root).

---

## 5. Getting Started

### Installation

Make sure you have Python 3.x installed. Install the required packages using pip:

    pip install catboost xgboost imbalanced-learn scikit-learn tensorflow numpy pandas matplotlib seaborn

### Running the Project

1. **Clone the Repository:**

       git clone https://github.com/OzzyPyrex/Predictive-Modelling-of-Hospital-Stay-Duration-A-Machine-Learning-Comparative-Study.git
       cd Predictive-Modelling-of-Hospital-Stay-Duration-A-Machine-Learning-Comparative-Study

2. **Place the Dataset:**

   Ensure that the `train_data.csv` file is in the repository root (or update the file path in `major_project.py` if necessary).

3. **Run the Main Script:**

       python major_project.py

Alternatively, you can run the project interactively in Google Colab or Jupyter Notebook.

---

## 6. Authors and Contact

**Project Members:**

- **Adithya Muralidharan K V**  
  Email: a.kv1@universityofgalway.ie
- **Ruben Mathew**  
  Email: r.mathew8@universityofgalway.ie
- **Vinod Rajan**  
  Email: v.rajan2@universityofgalway.ie

---

## 7. License

This project is licensed under the [MIT License](LICENSE).

---

For any questions, feedback, or contributions, please feel free to open an issue or submit a pull request. Enjoy exploring the project!
