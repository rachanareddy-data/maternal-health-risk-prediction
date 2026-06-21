# 🏥 Maternal Health Risk Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting maternal health risk levels (Low, Mid, High) using machine learning models based on medical parameters such as age, blood pressure, blood glucose, body temperature, and heart rate.

The goal is to assist early risk detection and support healthcare decision-making using data-driven insights.

---

## 🎯 Problem Statement
Maternal health is a critical area in healthcare. Early identification of risk levels can help reduce complications during pregnancy. This project builds a classification system to predict risk levels using patient health data.

---

## 📊 Dataset
- Source: UCI / Maternal Health Dataset
- Records: 1014 samples
- Features:
  - Age
  - SystolicBP
  - DiastolicBP
  - Blood Sugar (BS)
  - Body Temperature
  - Heart Rate
- Target:
  - Risk Level (Low / Mid / High)

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🤖 Machine Learning Models
- Logistic Regression
- Random Forest Classifier

---

## 📈 Model Performance

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression | ~62%     |
| Random Forest       | ~86%     |

👉 Random Forest performed best for classification.

---

## 🔍 Key Insights
- Blood pressure and blood glucose are strong indicators of maternal risk.
- Random Forest handles non-linear relationships better than Logistic Regression.
- Feature scaling improves Logistic Regression performance.

---

## 📊 Workflow
1. Data Collection
2. Data Preprocessing
3. Feature Scaling
4. Model Training
5. Evaluation
6. Visualization (Confusion Matrix, Feature Importance)

---

## 🚀 How to Run This Project
```bash
# Clone repository
git clone https://github.com/rachanareddy-data/maternal-health-risk-prediction.git

# Open project folder
cd maternal-health-risk-prediction

# Open Jupyter Notebook
jupyter notebook
