# 🌾 Precision Farmers: Machine Learning Insights

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This project applies machine learning, statistical modeling, and interpretability tools to a hypothetical farmers dataset. It investigates how technology adoption impacts crop yield and perceived well-being, using regression, classification, and ordinal logistic regression models.

---

## 📚 Table of Contents

- Overview
- Dataset Description
- Installation
- Usage
- Features
- Models Implemented
- Evaluation Metrics
- Visualizations
- Advanced Techniques
- Dependencies
- Results
- License

---

## 📋 Overview

This project explores the intersection of agricultural technology, labor, and well-being through:

- Predictive modeling (crop yield and well-being)
- Classification (ordinal and multi-class)
- Statistical testing (ANOVA, Tukey HSD)
- Model interpretation (SHAP)
- Regression diagnostics (VIF, Durbin-Watson)

---

## 📊 Dataset Description

Input file: `INSS 795 Project Hypothetical Farmers_data.xlsx`

Features include:
- Technology Adoption Level
- Labor Hours
- Financial Investment in Technology
- Environmental Impact Metrics
- Perceived Well-being
- Crop Yield

---

## ⚙️ Installation

1. Clone the repository:
   git clone https://github.com/yourusername/precision-farmers-ml-insights.git

2. Install the required packages:
   pip install -r requirements.txt

---

## 🚀 Usage

1. Ensure your Excel dataset is in the root directory.
2. Run the main script:
   python farmer_analysis.py

You can modify or comment/uncomment sections to test specific blocks (e.g., modeling, SHAP, ANOVA).

---

## ✨ Features

- Data cleaning and transformation (encoding, scaling)
- Ordinal regression (LogisticIT from `mord`)
- Regression models (Linear, Random Forest, XGBoost, Ridge)
- Classification models (Logistic Regression, Random Forest)
- Evaluation with RMSE, R², accuracy, confusion matrix
- Cross-validation and hyperparameter tuning
- ANOVA and Tukey HSD for feature significance
- SHAP explainability for regression output

---

## 🤖 Models Implemented

- Linear Regression
- Random Forest Regressor & Classifier
- XGBoost Regressor
- Logistic Regression
- LogisticIT (Ordinal Logistic Regression)
- Ridge Regression with SHAP Interpretability

---

## 📈 Evaluation Metrics

- **Regression**: RMSE, R², cross-validation
- **Classification**: Accuracy, classification report, confusion matrix
- **Ordinal**: Accuracy, coefficients, threshold estimates
- **Statistical**: F-statistics, p-values from ANOVA

---

## 📊 Visualizations

- Correlation heatmaps
- Boxplots for feature relationships
- Distribution plots for target variables
- SHAP summary plots
- Residual analysis (histograms, Q-Q plots, scatter plots)

---

## 🧪 Advanced Techniques

- Ridge regression with cross-validated alpha
- SHAP values for interpretability
- Assumption checks: Shapiro-Wilk, homoscedasticity, VIF, Durbin-Watson
- ANOVA + Tukey HSD for statistical comparison of groups

---

## 📦 Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost
- mord
- shap
- statsmodels
- scipy
- openpyxl

Install them via:
   pip install -r requirements.txt

---

## 📊 Results

- Regression: R² up to ~0.88 with Random Forest
- Ordinal: Coefficients and thresholds reflect interpretable impact of features on well-being
- Classification: Accuracy over 75% with Random Forest
- SHAP: Financial investment and environmental metrics showed highest influence on crop yield

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.datascienceportfol.io/KehindeAromona)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kehinde-gabriel-aromona-808578119/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/kennycrown7)

