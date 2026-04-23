# Calories Burnt Prediction using Machine Learning

## 📌 Overview

This project predicts the number of calories burned during physical activity using machine learning.

The model uses features such as age, gender, duration, heart rate, and body temperature to estimate calorie expenditure.

---

## 🎯 Objective

The goal is to build a regression model that can accurately predict calories burned based on physiological and activity-related inputs.

---

## 📂 Dataset

The dataset is created by merging two files:

* **exercise.csv** → contains user and activity data
* **calories.csv** → contains calories burned

Both datasets are combined using a common identifier.

### Features:

* Age
* Gender
* Height
* Weight
* Duration
* Heart Rate
* Body Temperature

### Target:

* Calories burned

---

## ⚙️ Machine Learning Workflow

1. Data loading and merging
2. Data preprocessing
3. Exploratory Data Analysis
4. Feature selection
5. Train-test split
6. Model training (XGBoost Regressor)
7. Model evaluation
8. Feature importance analysis

---

## 📊 Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## 📈 Results

The model predicts calories burned with good accuracy.

Important features influencing prediction:

* Duration of exercise
* Heart rate
* Body temperature

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn

---


## 👨‍💻 Author

Mridul Karar
