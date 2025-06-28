# Heart-Disease-Prediction
Heart Disease Prediction with Logistic Regression Predicting heart disease risk with ML — powered by real medical data, clean code, and smart insights
# 🫀 Heart Disease Prediction with Logistic Regression

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

** Objective**
Predict whether a person is at risk of heart disease using health data like age, cholesterol level, blood pressure, etc.

 **Dataset**
- **Name:** UCI Heart Disease Dataset
- **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **Rows:** 303
- **Columns:** 14 (13 features + 1 target)

**Project Steps**
1.  **Data Cleaning:** Checked for and confirmed no missing values
2.  **EDA (Exploratory Data Analysis):** Visualized distributions, trends, and correlations
3.  **Model Training:** Logistic Regression
4.  **Model Evaluation:**
   - Accuracy Score
   - Confusion Matrix
   - ROC-AUC Curve
5.  **Feature Importance:** Identified key health indicators affecting heart disease risk

** Results**
- **Accuracy:** 81.3%
- **AUC Score:** 0.81
- **Most Important Features:**
  - `cp` (chest pain type)
  - `thal` (thalassemia)
  - `oldpeak` (ST depression induced by exercise)

 **Key Visuals**
- ROC Curve for classification evaluation
- Count plots and heatmaps to explore feature relationships
- Feature importance visualized using coefficients

** Final Insights**
This notebook demonstrates how logistic regression can be applied to medical datasets to help predict disease risk, making it valuable for healthcare data analysis and early detection support systems.

**Tech Stack**
- Python 3.9
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

 **🔓 License**
This project is licensed under the **MIT License**. Feel free to use, modify, or share with credit.
