# Regression Project (Linear, Lasso and Ridge)

## Overview
This project involves predicting median house values in California districts using linear regression applied to the California_Houses.csv dataset. The dataset contains various features such as median income, population, and geographical information. The goal is to build and evaluate linear regression models and explore Lasso and Ridge regression for potential improvement.

![image](https://github.com/SaadElDine/House-Price-Prediction-Gradient-Descent/assets/113860522/73e137f1-6f7d-4b30-89f4-e7b4ede3aa7e)


## Steps

### 1. Data Loading and Visualization
- Loaded data comprising 20,640 examples and 14 features.
- Explored relationships between features and the target variable (median house value) through scatter plots.

### 2. Data Preprocessing
- Identified skewed features and applied log transformation for normalization.
- Performed Z-Score normalization.
- Checked for missing values (none found).
- Explored correlations between features and the target after preprocessing.
- Created new features, such as combining distance and age.

### 3. Data Splitting
- Divided the data into training (70%), validation (15%), and testing (15%) sets.

### 4. Linear Regression
- Applied linear regression to the training data.
- Evaluated model performance on the validation set (MSE: 0.1013, MAE: 0.2339).

### 5. Lasso Regression
- Utilized Lasso regression with hyperparameter tuning.
- Evaluated the best Lasso model on the validation set (MSE: 0.1013, MAE: 0.2340).

### 6. Ridge Regression
- Employed Ridge regression with hyperparameter tuning.
- Assessed Ridge model performance on the validation set (MSE: 0.1013, MAE: 0.2339).

### 7. Performance Visualization
- Plotted MSE and MAE for the validation set across different regression models.

### 8. Test Set Evaluation
- Evaluated model performance on the test set.
- Compared MSE and MAE between validation and test sets.

## Results
- Linear Regression:
  - Validation MSE: 0.1013, MAE: 0.2339
  - Test MSE: 0.0907, MAE: 0.2276
- Lasso Regression:
  - Validation MSE: 0.1013, MAE: 0.2340
  - Test MSE: 0.0907, MAE: 0.2277
- Ridge Regression:
  - Validation MSE: 0.1013, MAE: 0.2339
  - Test MSE: 0.0907, MAE: 0.2276

## Conclusion
All models showed similar performance on both the validation and test sets, suggesting that linear regression provides a reasonable baseline for predicting median house values. Further fine-tuning or exploring more complex models might be considered for potential improvements.
