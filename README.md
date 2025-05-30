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
