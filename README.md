Advanced Regression Assignment – Surprise Housing

**Problem Statement**

A US-based housing company, Surprise Housing, plans to enter the Australian real estate market. The company aims to purchase houses priced below their actual market value and resell them at a profit. To support this strategy, the company has collected historical housing data from Australia.

The objective of this assignment is to build a robust regression model using regularization techniques to accurately predict house prices and identify the key factors influencing them.

**Business Objectives**

The company wants to understand:

Which variables significantly influence house prices

How well these variables explain price variations

The optimal regularization parameters (lambda/alpha) for Ridge and Lasso regression

**Approach & Methodology**

The analysis is divided into two parts:

**Part I – Model Building**

Data Cleaning & Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Log transformation of the target variable

Feature Selection

Recursive Feature Elimination (RFE) to reduce dimensionality

Identification of the most relevant predictors

Model Development

Multiple Linear Regression (baseline)

Ridge Regression (L2 regularization)

Lasso Regression (L1 regularization)

Optimal lambda (alpha) selected using cross-validation

Bias–variance trade-off analysis

Ensuring train–test performance gap is within acceptable limits

Model Evaluation

R² and Adjusted R²

RMSE and MAE

Cross-validation scores

Feature importance analysis

**Part II – Subjective Analysis**

Interpretation of Ridge and Lasso results

Comparison between Ridge and Lasso models

Impact of regularization strength

Model robustness and generalization

**Technologies Used**

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn

**Conclusion**

Regularization techniques such as Ridge and Lasso helped control overfitting, improve generalization, and identify key predictors influencing house prices. The final model provides actionable insights for Surprise Housing to strategically enter the Australian market.
