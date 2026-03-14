# medical-insurance-cost-prediction-Medical_insurance_prediction_regression_models.ipynb-README.md
This project predicts medical insurance costs using multiple machine learning regression models. It includes data preprocessing, handling categorical variables with one-hot encoding, and comparing models such as Multiple Linear Regression, Polynomial Regression, SVR, Decision Tree, and Random Forest to evaluate their performance.

# Medical Insurance Cost Prediction

This project predicts medical insurance costs using multiple machine learning regression models. The goal is to analyze how different features affect insurance charges and compare the performance of several regression algorithms.

## Dataset

The dataset contains information about individuals such as age, BMI, number of children, smoking status, region, and medical insurance charges.

Source:
[https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv](https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv)

## Features

* age
* sex
* bmi
* children
* smoker
* region
* charges (target variable)

## Data Preprocessing

* Handling missing values using **SimpleImputer**
* Encoding categorical variables using **One-Hot Encoding**
* Splitting dataset into training and testing sets
* Feature scaling when required

## Machine Learning Models Used

* Multiple Linear Regression
* Polynomial Regression
* Support Vector Regression (SVR)
* Decision Tree Regression
* Random Forest Regression

## Model Evaluation

Models were evaluated using the **R² Score** to compare prediction performance.

## R-squared Scores:
* Multiple Linear Regression (MLR): 0.7623
* Polynomial Regression: 0.8626
* Support Vector Regressor (SVR): 0.8629
* Decision Tree Regressor: 0.7329
* Random Forest Regressor: 0.8513


## Conclusion:
Based on the R-squared scores, the Support Vector Regressor (SVR) achieved the highest performance, explaining approximately 86.29% of the variance in insurance charges. Polynomial Regression also performed exceptionally well, closely matching the SVR's performance. This suggests that the relationships between the features and insurance charges are largely non-linear, which these models were better able to capture compared to the simpler Multiple Linear Regression or Decision Tree models.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Google Colab

## Project Goal

To practice machine learning regression techniques and compare different models on a real dataset.

