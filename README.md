# 🏥 Health Insurance Cost Prediction using Machine Learning

## 🔍 Project Overview

This project aims to **predict health insurance costs** using various machine learning algorithms. By analyzing demographic and health-related data, the system helps individuals and healthcare providers estimate potential insurance expenses, identify high-risk profiles, and support cost-effective decision-making.

We developed both a **GUI (Tkinter)** and a **Streamlit-based web app** for user-friendly prediction and visualization.

---

## 🎯 Objectives

- Predict individual health insurance costs using ML models.
- Identify high-risk individuals and support risk mitigation.
- Provide an interactive web app for real-time cost estimation.

---

## 🧠 Machine Learning Models Used

| Algorithm                   | Purpose                                              |
|-----------------------------|------------------------------------------------------|
| Logistic Regression         | Classification based on probability                  |
| Support Vector Classifier   | Creates optimal decision boundaries                  |
| Gradient Boosting Regressor | Boosting-based regression for improved accuracy      |
| Random Forest Regressor     | Ensemble learning for robust regression              |

📊 **Result**: Among all, **Gradient Boosting** performed best in terms of accuracy.

---

## 📦 Dataset

- **Source**: [Kaggle Health Insurance Dataset](https://www.kaggle.com/)
- **Size**: 1338 records, 7 attributes (age, sex, BMI, children, smoker, region, charges)
- **Format**: CSV file

---

## 🧹 Data Preprocessing

1. **Duplicate Removal**: Removed duplicate rows.
2. **Missing Values**: Verified and handled missing data.
3. **Feature Separation**:
   - Categorical: `sex`, `smoker`, `region`
   - Continuous: `age`, `bmi`, `children`
4. **Feature Scaling**: Standardized continuous variables.

---

## ⚙️ Methodology

- Load and preprocess dataset.
- Train models: Logistic Regression, SVC, Gradient Boosting, Random Forest.
- Evaluate and compare model performance.
- Build interactive GUI and web app interfaces.

---

## 📈 Accuracy Comparison

| Model                     | Accuracy (%) |
|---------------------------|--------------|
| Logistic Regression       | 0.78         |
| Support Vector Classifier |-0.07         |
| Random Forest Regressor   | 0.86         |
| Gradient Boosting         | **0.877**    |

➡️ **Gradient Boosting** is selected as the final model for deployment.

---

## 💻 Application Interfaces

### 1. 🖥️ Tkinter GUI App
- Desktop application for manual data input.
- Predicts insurance cost using trained model.

### 2. 🌐 Streamlit Web App
- User-friendly web interface.
- Real-time prediction with visual insights.

## 📸 Screenshots

### 🔹 Streamlit Web App

![Streamlit UI Screenshot](steamlit_ui.PNG)

---

## 🚀 How to Run

### Prerequisites
Make sure you have Python 3.8+ installed.

Install required libraries:
```bash
pip install -r requirements.txt
