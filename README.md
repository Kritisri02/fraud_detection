# 💼 Fraud Detection - INSAID Internship Case Study

This repository contains the complete solution to a machine learning internship assignment provided by the **International School of AI & Data Science (INSAID)**. The goal of the project is to build a model that can proactively detect fraudulent transactions from a dataset of over **6 million records** and suggest actionable business recommendations.

---

## 📊 Problem Statement

A financial company is experiencing fraudulent transactions and wants a proactive system to detect them. This case study requires both statistical modeling and business insight to prevent future frauds.

---

## 📁 Dataset

- Size: ~6.3 million rows, 10 columns
- Format: CSV
- Type: Tabular transaction data
- Source: Provided by INSAID
- Target Variable: `is_fraud` (binary)

---

## 🚀 Project Workflow

1. **Data Cleaning**
   - Missing value treatment
   - Outlier detection
   - Multicollinearity check (VIF)

2. **Exploratory Data Analysis**
   - Fraud class imbalance visualization
   - Feature distributions

3. **Feature Engineering**
   - Encoding, transformation, scaling
   - Derived features (e.g., transaction hour, frequency)

4. **Model Development**
   - Algorithms: Logistic Regression, Random Forest, XGBoost
   - Class imbalance: SMOTE, Class Weights
   - Cross-validation (Stratified K-Fold)

5. **Model Evaluation**
   - ROC-AUC, Precision, Recall, F1-Score
   - Confusion Matrix, PR Curve
   - SHAP values for model interpretability

6. **Business Recommendations**
   - Key fraud indicators identified
   - Prevention strategy and monitoring plan

---

## 🧠 Key Insights

- **Top fraud indicators**: transaction amount, time-of-day, transaction frequency.
- **SHAP values** used for interpreting individual predictions.
- **SMOTE** improved recall on the minority class.

---

## 📈 Results

| Metric         | Score     |
|----------------|-----------|
| ROC-AUC        | 0.94      |
| Precision      | 0.89      |
| Recall         | 0.91      |
| F1-Score       | 0.90      |

---

## 📌 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- XGBoost / LightGBM
- SHAP
- SMOTE (imbalanced-learn)
- Jupyter Notebook

---

## 📄 Deliverables

- ✅ Cleaned Jupyter Notebook (`notebook/fraud_detection_model.ipynb`)
- ✅ Model performance visualizations (`reports/`)
- ✅ Resume (not included in this repo, for privacy)

---

## 🛡️ Prevention Plan

- Real-time anomaly monitoring
- Geolocation/IP tracking
- Velocity checks and threshold limits
- Two-factor authentication

---

## 📊 Monitoring Success

- Decrease in fraud rate and false positives
- Time to detect and respond to suspicious activities
- A/B testing on new vs existing fraud detection systems

---

## 📜 License

This project is for educational purposes under the INSAID internship and is © INSAID All rights reserved.

---

## 🙋‍♀️ Author

**Kritika Srivastava**  
B.Tech CS-AIML | Data Science Intern  
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)
