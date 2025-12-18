# House Price Prediction using Linear Regression
This project implements a linear regression model to predict house prices using a real-world U.S. housing dataset containing approximately 5,000 observations and 7 features.

The work was carried out for research-driven learning, with emphasis on understanding regression assumptions, model performance, and interpretability rather than model complexity

## Dataset
Real-world U.S. housing dataset
~5,000 rows, 7 input features
Target variable: house price
Includes numerical housing attributes

## Methodology
Data cleaning and basic preprocessing
Train–test split
Linear regression model fitting
Model evaluation using standard regression metrics

## Model Performance
MAE: 79,983
MSE: 10,028,148,309
RMSE: 100,141
R²: 0.9206

## Key Insights
Linear regression captured a large proportion of price variance (R² ≈ 0.92).
Feature quality had a stronger impact than increasing model complexity.
Error metrics highlighted sensitivity to high-priced outliers.

## Tools & Libraries
Python
NumPy
Pandas
Scikit-learn
Matplotlib 

## Limitations & Future Work
Assumes linear relationships between features and target variable.
Future work may include regularization or non-linear models for comparison.
