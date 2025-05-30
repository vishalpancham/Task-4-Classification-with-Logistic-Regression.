# Task-4-Classification-with-Logistic-Regression.
# 🧠 Breast Cancer Prediction using Logistic Regression

This project applies **Logistic Regression** to classify breast cancer tumors as **Malignant (1)** or **Benign (0)** based on features extracted from cell images. The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Data Set** from Kaggle.

---

## 📁 Dataset

- Source: [Kaggle – Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Total samples: 569
- Target variable: `diagnosis`  
  - `M` → Malignant (1)  
  - `B` → Benign (0)

---

## ✅ Workflow

1. **Data Cleaning**  
   - Dropped `id` and `Unnamed: 32` columns  
   - Encoded `diagnosis`: M → 1, B → 0

2. **Train-Test Split**  
   - 80% train, 20% test

3. **Feature Scaling**  
   - StandardScaler used for normalization

4. **Model Used**  
   - `LogisticRegression()` from sklearn

5. **Evaluation Metrics**  
   - Confusion Matrix  
   - Precision, Recall, F1-Score  
   - ROC Curve and AUC Score

---

## 📊 Results

### 📌 Confusion Matrix
## ✅ Model Evaluation Summary

- **Accuracy:** 97%
- **Precision (Malignant):** 0.98
- **Recall (Malignant):** 0.95
- **F1 Score:** 0.96
- **ROC-AUC Score:** 0.997

### 🔍 Insights:
- Very high model performance with minimal false negatives and positives
- Excellent classifier for medical diagnosis of breast cancer
- Model can be considered production-ready with proper clinical validation

### 📈 Visuals:
- Confusion Matrix and ROC Curve show reliable classification capability

