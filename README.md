# Student-Grade-Prediction
Predicting students' final grades using Machine Learning

# 🎓 Student Grade Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict students' final grades (**G3**) using various Machine Learning regression models. The objective is to compare the performance of different algorithms and identify the model that provides the most accurate predictions.

---

## 📂 Dataset

The project uses the **Student Performance Dataset**, which contains demographic, social, and academic information about students.

**Target Variable:**
- **G3** → Final Grade

To avoid **data leakage**, the intermediate grades (**G1** and **G2**) were removed from the input features because they are not available before predicting the final grade.

---

## 🛠️ Data Preprocessing

The preprocessing pipeline includes:

- Missing value imputation
  - Numerical features → Median
  - Categorical features → Most Frequent Value
- One-Hot Encoding for categorical variables
- ColumnTransformer for applying different preprocessing steps
- Pipeline for combining preprocessing and model training

---

## 🤖 Machine Learning Models

The following regression models were implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

## 📊 Evaluation Metric

The models were evaluated using:

- **Mean Absolute Error (MAE)**

A lower MAE indicates better prediction performance.

---

## 📚 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Google Colab
- Jupyter Notebook

---

