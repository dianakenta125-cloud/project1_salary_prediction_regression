# project1_salary_prediction_regression
predicting employee salaries based on year  s of experience using Python, Pandas and Scikit-Learn Simple Linear Regression
# 📈 Project 1: Predicting Employee Salary using Simple Linear Regression

A machine learning project built in Python to analyze the relationship between an employee's years of experience and their salary, and to predict future earnings using a Simple Linear Regression model.

---

## 📌 Project Overview

This project builds and evaluates a Simple Linear Regression model using `scikit-learn` and `pandas`. The goal is to determine how well work experience predicts salary and to make accurate salary forecasts for given levels of experience.

---

## 📊 Dataset Overview

* **Source:** Kaggle (Salary Data)
* **Features:** 
  * `YearsExperience` (Independent Variable / Feature): Number of years of work experience.
  * `Salary` (Dependent Variable / Target): Annual salary in USD.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook
* **Libraries:**
  * `pandas` & `numpy`: Data manipulation and numerical operations
  * `matplotlib`: Data visualization and regression line plotting
  * `scikit-learn`: Linear regression model, data splitting, and evaluation metrics

---

## 🚀 Workflow & Key Steps

1. **Data Inspection:** Loaded the dataset to check shape, missing values, data types, and summary statistics.
2. **Feature & Target Selection:** Defined `YearsExperience` as X and `Salary` as y.
3. **Train-Test Split:** Split the dataset into an **80/20** ratio (80% training set, 20% test set) to prevent overfitting.
4. **Model Training:** Fit a `LinearRegression` model using the training data.
5. **Model Evaluation:** Evaluated performance on the test set using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.
6. **Visualization:** Plotted actual data points alongside the fitted regression line.
7. **Prediction:** Generated a salary prediction for a candidate with **5 years of experience**.

---

## 📈 Results & Performance

* **Fitted Linear Equation:**  
  $$\text{Salary} = 9423.81 \times (\text{YearsExperience}) + 25321.58$$

* **Coefficient Interpretation:**
  * **Slope ($9,423.81):** Each additional year of experience increases the predicted salary by approximately **$9,424**.
  * **Intercept ($25,321.58):** The baseline predicted starting salary for an entry-level candidate (0 years experience) is **$25,322**.

* **Model Accuracy:**
  * **R² Score:** ~0.95 (Over 95% of salary variation is explained by years of experience).
  * **RMSE:** ~$7,000 - $9,000 average error margin on unseen test data.

* **5-Year Prediction Target:**
  * Predicted Salary for 5.0 Years Experience: **$72,440.65**
