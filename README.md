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

## 📈 Results Summary

Each notebook ends with a tabulated or visual comparison of model performance using **Mean Squared Error (MSE)** on test data.

| Model              | Tuned Parameter (λ / M) | Test MSE | Notes |
|-------------------|-------------------------|----------|-------|
| Linear Regression | —                       | ✅        |       |
| Ridge             | λ via CV                | ✅        | Reduced variance |
| Lasso             | λ via CV                | ✅        | Sparse model |
| PCR               | M via CV                | ✅        | Uses PCA |
| PLS               | M via CV                | ✅        | Targets response directly |

---

## 📦 Technologies Used

- Python 3.10+
- NumPy, Pandas, Scikit-Learn
- Matplotlib / Seaborn for visualization
- PCA / PLS from `sklearn.decomposition` and `sklearn.cross_decomposition`

---

## 📚 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/regression-dm-exercises.git
   cd regression-dm-exercises
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open any notebook:
   ```bash
   jupyter notebook Ex4DM.ipynb
   ```

---

## 👨‍🎓 Author

**Dipen Prajapati**  
Full Stack Developer | Machine Learning & Quant Finance Enthusiast  
🔗 [GitHub](https://github.com/dip1406) | [LinkedIn](https://linkedin.com/in/dipen-prajapati)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
