# Bank_customer_churn
# 🏦 Bank Customer Churn Prediction using Machine Learning  A complete end-to-end Machine Learning project that predicts whether a bank customer is likely to leave the bank (churn) using multiple supervised learning algorithms.  


This project focuses on building a professional machine learning workflow including data analysis, feature engineering, leak-free preprocessing, model comparison, cross-validation, and handling class imbalance using SMOTE.

---

## 📌 Project Overview

Customer churn prediction is one of the most important business applications of Machine Learning. Identifying customers who are likely to leave allows banks to take preventive actions and improve customer retention.

In this project, several Machine Learning models were developed and compared to determine the most effective approach for churn prediction.

---

## 🎯 Objectives

- Perform detailed Exploratory Data Analysis (EDA)
- Understand customer behavior
- Engineer meaningful features
- Build a leak-free preprocessing pipeline
- Compare multiple Machine Learning algorithms
- Evaluate models using Cross Validation
- Handle class imbalance using SMOTE
- Analyze the effect of SMOTE on model performance
- Select the best performing model

---

## 📂 Dataset Information

- **Dataset:** Bank Customer Churn Dataset
- **Task:** Binary Classification
- **Target Variable:** `Exited`
  - 0 → Customer Stayed
  - 1 → Customer Churned

### Dataset Summary

- No missing values
- No duplicate records
- 3 categorical features
- 11 numerical features
- Class imbalance (~79% : 21%)

---

## 🛠 Project Workflow

```
Data Collection
        │
        ▼
Data Understanding
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Engineering
        │
        ▼
Mutual Information Analysis
        │
        ▼
Train-Test Split
        │
        ▼
Leak-Free Preprocessing Pipeline
        │
        ▼
5-Fold Cross Validation
        │
        ▼
Model Comparison
        │
        ▼
SMOTE Experiment
        │
        ▼
Performance Evaluation
```

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset overview
- Missing value analysis
- Duplicate checking
- Numerical feature analysis
- Categorical feature analysis
- Target distribution
- Correlation analysis
- Mutual Information Feature Importance

---

## ⚙ Feature Engineering

Several engineered features were explored, including:

- Age Groups
- Credit Score Groups
- Salary Groups
- Balance per Product
- Balance-to-Salary Ratio
- Active Products
- Loyalty Score

The effectiveness of these engineered features was experimentally evaluated before selecting the final feature set.

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (RBF)
- Random Forest
- XGBoost
- LightGBM
- CatBoost

---

## 🔄 Model Evaluation

Models were evaluated using **5-Fold Cross Validation**.

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Training Time

---

## ⚖ Handling Class Imbalance

The dataset is imbalanced.

An additional experiment was conducted using **SMOTE (Synthetic Minority Oversampling Technique)** to improve the model's ability to detect churned customers.

The project compares:

- Baseline Models
- Models with SMOTE

to analyze the trade-off between:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## 🏆 Best Performing Model

Among all evaluated models:

**CatBoost** achieved the strongest overall performance with the best balance between:

- Accuracy
- Precision
- F1 Score
- ROC-AUC

while SMOTE significantly improved recall for the minority (churn) class.

---

## 📈 Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- XGBoost
- LightGBM
- CatBoost
- imbalanced-learn (SMOTE)

---

## 📁 Repository Structure

```
├── churn_prediction.ipynb
├── README.md
├── requirements.txt
├── figures/
│   ├── correlation_heatmap.png
│   ├── mutual_information.png
│   ├── confusion_matrix.png
│   └── ...
```

---

## 📚 Key Learning Outcomes

Through this project I gained practical experience in:

- End-to-end Machine Learning workflow
- Exploratory Data Analysis
- Feature Engineering
- Leak-free preprocessing pipelines
- Cross Validation
- Ensemble Learning
- Gradient Boosting Models
- Handling imbalanced datasets using SMOTE
- Performance evaluation using multiple metrics
- Model comparison and interpretation

---

## 🚀 Future Improvements

Planned future improvements include:

- Hyperparameter Optimization
- SHAP (Explainable AI)
- Threshold Optimization
- Probability Calibration
- Research paper implementation

---

## 👨‍💻 Author

**Ali Kaisar Saiful**

Department of Computer Science and Engineering (CSE)

State University of Bangladesh

---

⭐ If you found this project useful, consider giving the repository a star.
