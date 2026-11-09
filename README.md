# 🧬 Biomedical Multivariate Analysis & Diabetes Prediction (CCA & SVM)

Statistical and machine learning investigation of the **Pima Indians Diabetes Clinical Dataset**, combining **Canonical Correlation Analysis (CCA)**, **Multivariate Hypothesis Testing**, and **Support Vector Machine (SVM)** classification to uncover latent physiological relationships and improve diagnostic prediction accuracy.

---

## 🔬 Methodology & Highlights

1. **Multivariate Statistical Profiling**:
   - Analyzes joint distributions across clinical predictors (`Glucose`, `Insulin`, `BMI`, `BloodPressure`, `SkinThickness`, `Age`, `DiabetesPedigreeFunction`, `Pregnancies`).
2. **Canonical Correlation Analysis (CCA)**:
   - Models linear combinations of physiological variables (e.g., metabolic indicators vs. demographic/body-mass profiles) that maximize cross-covariance.
3. **Support Vector Machine (SVM) & Classification Pipeline**:
   - Evaluates decision boundaries and diagnostic sensitivity/specificity for early diabetes screening.

---

## 📂 Repository Structure

- `biomedical_diabetes_cca_svm.ipynb` — Full Jupyter Notebook containing exploratory analysis, CCA projections, correlation heatmaps, and predictive modeling.
- `CCA_Biomedical_Diabetes_Report.pdf` — Comprehensive technical paper and statistical interpretation.
- `diabetes.csv` — Clinical dataset (768 patient records, 8 physiological features + diagnostic outcome).

---

## 🚀 Quick Start

```bash
pip install pandas numpy scipy scikit-learn statsmodels matplotlib seaborn jupyter
jupyter notebook biomedical_diabetes_cca_svm.ipynb
```
