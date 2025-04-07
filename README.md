# Gestational-Diabetes
# 🤖 Gestational Diabetes Prediction using Machine Learning

This project aims to predict the likelihood of gestational diabetes in pregnant women using a variety of machine learning models. Early detection of gestational diabetes is crucial for ensuring better health outcomes for both the mother and the baby. The system can serve as a support tool for medical professionals, especially in areas with limited access to regular screening.

---

## 🧬 Problem Description

**Gestational diabetes** is a type of high blood sugar that develops during pregnancy. If not detected and managed early, it can cause complications during and after childbirth. The goal of this project is to build and evaluate machine learning models that can accurately predict the risk of gestational diabetes based on clinical data collected from real patients.

---

## 📊 Dataset

- **Source**: Collected from laboratories in the Kurdistan region.
- **Features include**:
  - Number of pregnancies
  - Glucose levels
  - Blood pressure
  - Skin thickness
  - Insulin levels
  - BMI
  - Diabetes pedigree function
  - Age
- **Target**: Whether the patient was diagnosed with gestational diabetes (binary classification)

---

## ⚙️ Models Used

The following machine learning models were trained and compared:

- 🔹 Logistic Regression  
- 🌲 Decision Tree  
- 🌳 Random Forest  
- ⚡ XGBoost  
- 🧠 Neural Network (built with Keras / TensorFlow)

Each model was evaluated using common classification metrics.

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  
- Confusion Matrix  
- Feature importance analysis

---

## 📌 Key Insights

- **22%** of the women in the dataset were diagnosed with gestational diabetes.
- The likelihood of developing the condition increases with:
  - Higher BMI (especially over 50)
  - More pregnancies
  - A strong family history of diabetes
- Ensemble models (like **Random Forest** and **XGBoost**) performed best overall in terms of balanced accuracy and generalization.
