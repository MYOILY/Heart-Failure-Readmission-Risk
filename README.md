# ❤️ Heart Failure Readmission Risk Prediction

## Project Overview

Hospital readmission among heart failure patients is a major challenge in healthcare systems worldwide. Predicting which patients are at high risk of readmission can help hospitals allocate resources more effectively and improve patient care.

This project develops a **machine learning model to predict the likelihood of hospital readmission for patients with heart failure** using clinical and demographic data. The workflow includes data preprocessing, exploratory analysis, feature engineering, model training, and evaluation.

Machine learning approaches are increasingly used in healthcare to identify high-risk patients and support clinical decision-making. ([PMC][2])

---

# Research Objective

The goal of this project is to build a predictive model that can:

* Identify patients with **high risk of hospital readmission**
* Analyze which clinical features contribute most to readmission risk
* Evaluate multiple machine learning models for predictive performance

Key questions:

1. Which patient features are most associated with readmission risk?
2. Can machine learning models accurately predict readmission outcomes?
3. Which algorithm performs best for this dataset?

---

# Dataset

The dataset contains patient information related to heart failure and clinical indicators that may influence hospital readmission risk.

Typical features in heart failure datasets include variables such as:

| Feature             | Description              |
| ------------------- | ------------------------ |
| Age                 | Patient age              |
| Sex                 | Gender of patient        |
| Blood Pressure      | Cardiovascular indicator |
| Serum Creatinine    | Kidney function marker   |
| Ejection Fraction   | Heart pumping efficiency |
| Diabetes            | Presence of diabetes     |
| Anaemia             | Presence of anaemia      |
| High Blood Pressure | Hypertension status      |
| Smoking             | Smoking status           |
| Time                | Follow-up period         |

These features are commonly used in heart-failure prediction studies to model patient outcomes. ([ScienceDirect][1])

---

# Technologies Used

* **Python**
* **Pandas** – data manipulation
* **NumPy** – numerical computing
* **Matplotlib / Seaborn** – visualization
* **Scikit-learn** – machine learning models
* **Jupyter Notebook** – analysis environment

---

# Machine Learning Workflow

## 1 Data Preprocessing

* Handle missing values
* Feature scaling
* Encoding categorical variables

## 2 Exploratory Data Analysis

* Feature distributions
* Correlation analysis
* Identification of important predictors

## 3 Model Development

Several classification models are trained and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine

## 4 Model Evaluation

Models are evaluated using common classification metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

# Example Insights

The analysis investigates relationships such as:

* Impact of **ejection fraction on readmission risk**
* Influence of **age and comorbidities**
* Relationship between **clinical biomarkers and patient outcomes**

These insights can help identify patients who may benefit from early intervention.

---

# Project Structure

```
Heart-Failure-Readmission-Risk
│
├── data
│   └── dataset.csv
│
├── notebooks
│   └── heart_failure_analysis.ipynb
│
├── results
│   └── predictions.csv
│
├── report
│   └── Problem_Statement.pdf
│
└── README.md
```

---

# How to Run the Project

### Clone the repository

```bash
git clone https://github.com/MYOILY/Heart-Failure-Readmission-Risk.git
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the notebook

Open the Jupyter notebook and run all cells.

---

# Potential Improvements

Future enhancements for the project:

* Hyperparameter tuning
* Feature importance analysis
* Explainable AI methods (e.g., SHAP)
* Cross-validation
* Deployment as a web prediction tool

---

# Author
Lok Yiu

GitHub:
[https://github.com/MYOILY](https://github.com/MYOILY)
