# project1_salary_prediction using Simple Linear Regression
   A machine learning project built in Python to analyze the relationship between an employee's years of experience and         their salary using a Simple Linear Regression model.
##Source:  Salary Data

## Features:
  `YearsExperience` (Independent Variable / Feature): Number of years of work experience.
  `Salary` (Dependent Variable / Target): Annual salary in usd
  
  # libraries
     `pandas` & `numpy`: Data manipulation and numerical operations
     `matplotlib`: Data visualization and regression line plotting
     `scikit-learn`: Linear regression model, data splitting, and evaluation metrics

## Workflow & Key Steps

1. Data Inspection:
    Loaded the dataset to check shape, missing values, data types, and summary statistics.
2. Determine features:
    Defined `YearsExperience` as X and `Salary` as y.
3. Train-Test Split: 
    Split the dataset into an **80/20** ratio (80% training set, 20% test set) to prevent overfitting.
4. Model Training:
    Fit a `LinearRegression` model using the training data.
5. Model Evaluation:
    Evaluated performance on the test set using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.
6. Generate prediction:
    Tested how the model can be used to estimate outcomes for new data
7.  Visualization:
    Plotted actual data points alongside the fitted regression line.
8. Prediction:
     Generated a salary prediction for a candidate with **5 years of experience**.

##6_Year Prediction Target:
  predicted salary for 6 years is $81864.47

 ## fitted regression equation
    SALARY = intercept+(Slope* YearsExperience)
    salary=25321.58+9423.82*YearsExperience
  slope indicates the salary increases by approximately 9423.82 for every additional year of experience.
  intercept indicates that the predicted salary for an emloyee with zero years of experience is approximately 25321.58.
    
    
