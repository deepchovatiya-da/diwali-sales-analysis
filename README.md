# Diwali Sales Analysis

## Project Overview
EDA and machine learning analysis on 11,251 Diwali 
festive sales records to predict purchase amounts 
and identify high-value customer segments.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (Linear Regression, Random Forest, 
  Logistic Regression)

## Analysis Performed
- Univariate, bivariate and multivariate EDA
- Missing value treatment using median imputation
- Outlier detection using IQR method
- Correlation and covariance analysis
- Multiple Linear Regression with one-hot encoding
- Random Forest Regression
- High spender classification (83.39% accuracy)
- Overfitting analysis

## Results
- Linear Regression R² = 0.656 (best model)
- Random Forest showed overfitting (Train R²=0.818, 
  Test R²=0.631) — Linear Regression more reliable
- High spender classifier accuracy = 83.39%
- Product category and zone are stronger purchase 
  predictors than age or gender alone
- Southern zone female customers = highest average 
  spend at ₹10,088
