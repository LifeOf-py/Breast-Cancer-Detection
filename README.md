# 🧬 Breast Cancer Prediction

This project focuses on predicting whether a breast tumor is **malignant or benign** using the classic UCI Breast Cancer dataset. It compares multiple models using **nested cross-validation** and selects **Logistic Regression** as the final model based on performance.

---

## 📌 Project Overview

- **Task**: Binary classification
- **Target**: Diagnosis (Malignant = 1, Benign = 0)
- **Dataset**: UCI Breast Cancer Dataset
- **Final Model**: Logistic Regression
- **Modeling Workflow**:
  - Data loading and preprocessing
  - Nested Cross-Validation for model selection
  - Hyperparameter tuning
  - Final evaluation on a holdout test set

---

## ⚙️ Tools & Libraries

- Python
- `scikit-learn`
- `matplotlib`, `seaborn`

---

## ✅ Results Summary

- **Best Model**: Logistic Regression
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1 Score
  - ROC AUC
- Comprehensive performance reported on holdout data

---

## 💼 Business Value

Accurate classification of tumor malignancy supports early diagnosis and treatment planning in healthcare, showcasing the value of interpretable models like logistic regression for sensitive domains.

> 📂 Explore the notebook: `breast_cancer_detection.ipynb`
