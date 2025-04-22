# 📊 Regression Models & Dimensionality Reduction – Data Mining Exercises

This repository contains solutions and experiments for advanced regression models, regularization techniques, and dimensionality reduction using Python. The notebooks follow textbook-style exercises to compare model performances on real-world datasets.

---

## 🧪 Included Notebooks

### ✅ `Ex4DM.ipynb`: **Model Evaluation and Selection**

This notebook covers:

- Data cleaning, one-hot encoding, and preprocessing
- Splitting into training and test sets
- Model training and evaluation:
  - **Linear Regression**
  - **Ridge Regression** (with λ tuned via cross-validation)
  - **Lasso Regression** (λ via cross-validation, with non-zero coefficient analysis)
  - **PCR (Principal Components Regression)** (with cross-validation to select optimal M)
  - **PLS (Partial Least Squares Regression)** (cross-validated component selection)
- **Comparison of all model performances based on test MSE**

---

### ✅ `Ex5DM.ipynb`: **Regularization with Real Dataset**

This notebook applies similar techniques on a different dataset, emphasizing the effect of regularization:

- Preprocessing (dropping nulls, standardization)
- **Linear Regression**
- **Ridge Regression** (tuned using cross-validation)
- **Lasso Regression** (with feature selection)
- **PCR and PLS** (dimensionally reduced modeling)
- **Model comparison based on test error and interpretability**

---

### ✅ `Ex6DM.ipynb`: **Comprehensive Regression and Dimensionality Pipeline**

Topics covered:

- One-hot encoding and null handling
- Removing symbols from column names
- Evaluation of:
  - **Linear Model (Least Squares)**
  - **Ridge & Lasso** with cross-validation for hyperparameter tuning
  - **PCR & PLS** with detailed manual component selection process
- **Final comparison of all methods' performance metrics**

---
