# 📊 Exploratory Data Analysis (EDA) with SHAP

This repository showcases an Exploratory Data Analysis (EDA) project enriched with **SHAP (SHapley Additive exPlanations)** to interpret the impact of features on model predictions. The project demonstrates both classic EDA techniques and model explainability.

## 📁 Files

- `EDA.ipynb`: Main notebook performing the EDA, modeling, and SHAP analysis.
- `README.md`: Project overview and documentation.

---

## 🎯 Objectives

- Understand the structure and quality of the dataset
- Uncover relationships, trends, and outliers using visual and statistical methods
- Train a baseline machine learning model
- Use **SHAP** to explain feature importance and individual predictions

---

## 🛠️ Tools & Libraries Used

- `Python 3.x`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `shap`

---

## 🔍 EDA Workflow Overview

### 1. Data Preprocessing
- Handling missing values and duplicates
- Data type conversions

### 2. Exploratory Data Analysis
- Summary statistics
- Univariate and bivariate plots
- Correlation analysis

### 3. Baseline Modeling
- Feature selection
- Model training (e.g., RandomForest, XGBoost)

### 4. Explainable AI with SHAP
- SHAP summary plot (global feature importance)
- SHAP dependence plots (individual feature behavior)
- Force plots (individual prediction explanation)

---

## 📊 Sample Visualizations

- 📉 Histograms, boxplots, and heatmaps
- 🔍 SHAP Summary Plot
- 🧠 SHAP Force Plot
- 📈 SHAP Dependence Plot

---

## 📌 How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/eda-shap-project.git
cd eda-shap-project
