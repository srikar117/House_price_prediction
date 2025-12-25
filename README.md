House Price Prediction on California Housing Dataset from Kaggle

Overview
This repository contains a machine learning project focused on predicting house prices using the California Housing dataset from Kaggle. The aim is to build, evaluate, and compare regression models to estimate median house values based on demographic and geographic features.

Dataset
The dataset includes features such as:
median income
number of rooms
population
housing median age
proximity to the ocean
Target variable: median house value

Dataset source: California Housing Dataset on Kaggle

Project Workflow
Data loading and initial inspection
Handling missing values
Exploratory data analysis (EDA)
Log transformation to reduce skewness
One-hot encoding of categorical variables
Train–test split
Feature scaling where required
Model training and evaluation

Models Implemented
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor

Results
Linear Regression served as a baseline model
Random Forest showed strong predictive performance but required tuning to reduce overfitting
Tuned Gradient Boosting Regressor achieved the best overall performance
Final metrics (approximate):
R² ≈ 0.82
RMSE ≈ 49,000

Key Insights
Nonlinear ensemble methods outperform simple linear models
Median income and location-based features are strong predictors of house prices
Feature engineering and hyperparameter tuning significantly improve pe