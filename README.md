# 🩺 PCOS Prediction using Machine Learning

This project aims to develop predictive models for the early detection of **Polycystic Ovary Syndrome (PCOS)** based on medical and biological features using various machine learning algorithms.

---

## 📌 Problem Statement

**Polycystic Ovary Syndrome (PCOS)** is a common hormonal disorder affecting women's reproductive health. Early detection can help with timely treatment and better quality of life. In this project, we use clinical data and machine learning techniques to build models that can predict whether a patient has PCOS.

---

## 📊 Dataset

- **Source**: `pcos_dataset.csv`
- **Target variable**: `PCOS_Diagnosis` (0 = No, 1 = Yes)
- **Number of features**: Medical and hormonal attributes like:
  - BMI
  - Testosterone level
  - Menstrual irregularity
  - Insulin resistance
  - etc.

---

## 🧹 Data Preprocessing

- Handling missing values (`median` imputation)
- Removing duplicates
- Standardizing features with `StandardScaler`
- Balancing classes using **SMOTE** (Synthetic Minority Oversampling Technique)
- Exploratory Data Analysis (histograms, boxplots, correlation heatmap)

---

## 🧠 Models Used

| Model                  | Description                        |
|------------------------|------------------------------------|
| Logistic Regression    | Simple, interpretable baseline     |
| Random Forest          | Ensemble of decision trees         |
| Support Vector Machine | High-dimensional classifier        |
| K-Nearest Neighbors    | Distance-based lazy learning       |
| XGBoost                | Powerful boosting-based algorithm  |
| Decision Tree          | Simple tree-based classification   |

---

## ⚙️ Evaluation Metrics

For each model, we calculated:

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve and AUC

---

## 📈 Results Summary

A comparison table and ROC curves are generated to assess the performance of each model. The best performing model (in terms of AUC and F1-score) is typically **XGBoost**, followed by **Random Forest**.

---

By Eya Azzabi

