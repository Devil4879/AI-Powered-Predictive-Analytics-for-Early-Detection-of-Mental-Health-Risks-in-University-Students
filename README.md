# AI-Powered-Predictive-Analytics-for-Early-Detection-of-Mental-Health-Risks-in-University-Students
# 🧠 AI-Powered Predictive Analytics for Early Detection of Mental Health Risks in University Students

A machine learning–driven system to classify university students into **Mental Health Risk Levels (Low / Medium / High)** using **behavioral, academic, and lifestyle** survey data. The goal is to support **early awareness and preventive intervention** through data-driven insights.

> ⚠️ **Disclaimer:** This project is for educational/research purposes and awareness only. It is **not** a medical diagnostic tool and should not replace professional help.

---

## 👤 Author
**Rahul**

---

## 🚀 Live Demo (Streamlit)
Interactive self-assessment web app (rule-based logic for awareness):

- **Demo:** https://mental-health-risk-self-assessment-demo.streamlit.app/

> ✅ The deployed app uses **AI-inspired rule-based logic** for basic risk awareness.  
> 📌 The **ML models** are documented in notebooks/research materials for analysis and comparison.

---

## 🎯 Project Objective
This project builds a predictive analytics pipeline that:
- Cleans and prepares structured survey data
- Trains multiple ML models for multi-class classification
- Handles class imbalance using SMOTE
- Compares models using Accuracy, F1-score, and Confusion Matrix
- (Optional) Provides explainability using feature importance / SHAP

---

## ✅ Key Features

| Module | Description |
|-------|-------------|
| 🔍 Data Preprocessing | Missing values handling, encoding categorical features, feature scaling |
| 📊 Exploratory Data Analysis | Distribution plots, correlation heatmaps, risk-level insights |
| 🤖 Multi-Model Training | Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost |
| ⚖️ Class Imbalance Handling | SMOTE (Synthetic Minority Oversampling Technique) |
| 🧪 Model Evaluation | Accuracy, F1-score, Confusion matrix, model comparison |
| 🧠 Explainability (Optional) | Feature importance and optional SHAP analysis |

---

## 📂 Dataset
- **Source:** Kaggle – Students Mental Health Assessments  
- **Link:** https://www.kaggle.com/datasets/sonia22222/students-mental-health-assessments  
- **Format:** CSV  
- **Type:** Structured survey dataset  
- **Target Variable:** Mental Health Risk Level (**Low / Medium / High**)

**Feature Examples:**
- Academic pressure
- Sleep patterns
- Anxiety indicators
- Lifestyle habits
- Self-reported stress levels

---

## 📊 Model Performance (After SMOTE)

| Model | Accuracy | F1 Score |
|------|----------|----------|
| **Gradient Boosting ⭐ (Best)** | **0.404** | **0.375** |
| Random Forest | 0.403 | 0.371 |
| Logistic Regression | 0.384 | 0.380 |
| XGBoost | 0.382 | 0.366 |
| Decision Tree | 0.349 | 0.351 |

➡️ **Gradient Boosting performed best overall** in this experimental setup.

> Note: Results may vary depending on preprocessing, random seed, and evaluation split.

---

## 🛠 Tech Stack
- **Language:** Python  
- **Data Handling:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn, XGBoost  
- **Imbalance Handling:** imbalanced-learn (SMOTE)  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git & GitHub  
- **Web App (Demo):** Streamlit  

---

## ▶️ How to Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
