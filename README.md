---

# 📘 Student Performance Prediction using Machine Learning

This project aims to predict students' final exam scores based on multiple features such as attendance, internal assessments, study hours, gender, and parents’ education level. The goal is to help educators identify at-risk students early and take proactive academic support measures.

---

## 🚀 Project Objectives

* Predict final exam scores using machine learning models
* Identify key factors influencing academic performance
* Analyze feature importance to support data-driven decision-making

---

## 📂 Dataset

A synthetic dataset was generated to simulate real-world student data, containing:

* Attendance (%)
* Internal Exam Scores (3 assessments)
* Study Hours per Week
* Gender
* Parent Education Level
* Final Exam Score (Target)

---

## 🧪 Technologies Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## 🛠️ Methodology

1. **Data Generation & Preprocessing**

   * Categorical encoding for gender and parental education
   * Feature engineering: average internal score
   * Standard scaling for numerical values

2. **Exploratory Data Analysis (EDA)**

   * Pairplots and heatmaps to visualize relationships
   * Insights on correlations between features

3. **Model Training**
   Trained and evaluated three regression models:

   * Linear Regression
   * Random Forest Regressor
   * XGBoost Regressor

---

## 📈 Model Performance

| Model             | RMSE | R² Score |
| ----------------- | ---- | -------- |
| Linear Regression | 5.13 | 0.45     |
| Random Forest     | 5.63 | 0.34     |
| XGBoost           | 6.28 | 0.18     |

> 🔎 **Linear Regression outperformed other models** with the best balance of accuracy and interpretability.

---

## 📊 Feature Importance (Random Forest)

![Feature Importance](feature_importance.png)

Top contributing features:

* Average Internal Score
* Attendance
* Study Hours

---

## 📌 Key Insights

* Internal assessment scores and attendance have a strong positive influence on final exam scores.
* Tree-based models underperformed likely due to dataset simplicity or scaling.
* Linear relationships dominated the data, favoring simple models.

---

## 🧾 Future Improvements

* Use real-world datasets for validation
* Hyperparameter tuning for Random Forest & XGBoost
* Incorporate more behavioral features like extracurriculars or classroom engagement

---

## 📜 License

This project is for academic and demonstration purposes only.

---
