# DIAML Projects (Fall)

This repository contains three projects completed for the **Data, Inference, and Applied Machine Learning (DIAML)** course.

## Projects

### Project 3: Loan Status Prediction (Classification)
Folder: `Project-3-Loan-Status-Prediction/`

What it covers:
- Exploratory data analysis of the **Loan Status Prediction** dataset (variable types, skewness, distribution checks)
- Missing value analysis and outlier detection/handling (IQR / Z-score discussion and boxplots)
- Categorical encoding (Label Encoding vs One-Hot Encoding) and feature scaling discussion
- Feature engineering (including income-related transformed features)
- Training and evaluating linear classifiers:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - SGD Classifier
- Model evaluation with confusion matrix, classification metrics, and ROC/AUC comparisons

Included files:
- Notebook: `Project-3-Loan-Status-Prediction/notebooks/iguygael_DIAML_Assignment3.ipynb`
- Report (PDF): `Project-3-Loan-Status-Prediction/reports/iguygael_DIAML_Assignment3.pdf`

### Project 4: Life Expectancy Regression (Model Comparison + Tuning)
Folder: `Project-4-Life-Expectancy-Regression/`

What it covers:
- Data understanding and preprocessing for the **Life Expectancy Data** dataset
- Missing value analysis and imputation (including country-level median and KNN imputation usage)
- Outlier handling and feature engineering for health/socioeconomic indicators
- Regression model training and comparison:
  - Decision Tree Regressor
  - Random Forest Regressor
  - KNN Regressor
  - Gradient Boosting Regressor
- Hyperparameter tuning with **GridSearchCV** and **RandomizedSearchCV**
- Evaluation with MSE, MAE, R2, and explained variance

Included files:
- Notebook: `Project-4-Life-Expectancy-Regression/notebooks/iguygael_DIAML_Assignment4.ipynb`
- Report (DOCX): `Project-4-Life-Expectancy-Regression/reports/iguygael_DIAML_Assignment4.docx`
- Report (PDF): `Project-4-Life-Expectancy-Regression/reports/iguygael_DIAML_Assignment4.pdf`

### Project 5: Financial Time Series Analysis, PCA, and Forecasting
Folder: `Project-5-Financial-Time-Series-and-PCA/`

What it covers:
- Downloading and analyzing **DJIA stock** data with `yfinance`
- Computing log returns and correlation structure
- **PCA** on stock return correlations (eigenvalues / explained variance / interpretation)
- Correlation-based clustering and dendrogram analysis
- Time-series analysis on a DJIA stock (CVX monthly series in the notebook):
  - Stationarity testing (ADF)
  - Trend/seasonality decomposition and diagnostics (STL, ACF/PACF)
  - Forecasting comparison using SMA vs **ARIMA**
  - **LSTM**-based forecasting with PyTorch

Included files:
- Notebook: `Project-5-Financial-Time-Series-and-PCA/notebooks/iguygael_DIAML_Assignment5.ipynb`
- Report (DOCX): `Project-5-Financial-Time-Series-and-PCA/reports/iguygael_DIAML_Assignment5.docx`

## Notes
- Some notebooks reference local datasets/files that may not be included in this repository.
- Reports and notebooks are preserved in their original submitted formats.
