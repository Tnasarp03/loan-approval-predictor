# Portfolio Part 3 (2024 S2): Data Science Model Implementation

This portfolio showcases an incomplete attempt to build and evaluate machine learning models using various techniques. The focus of this section is on model training, feature selection, and hyperparameter tuning.

## Dataset Overview

The project revolves around a dataset used for binary classification tasks. The target variable represents whether a loan application was approved (`LoanApproved`). The features include:
- **Numerical and Categorical Features** (e.g., loan amount, credit score, income level, etc.)

## Key Tasks

### 1. Data Preprocessing
- **Handling Missing Data**: Imputation of missing values using modes for categorical columns.
- **One-Hot Encoding**: Transforming categorical variables into binary features for model input.

### 2. Model Training
- **Logistic Regression**: A logistic regression model is trained to predict loan approval using the cleaned and prepared dataset.

### 3. Model Evaluation
- **Performance Metrics**: The notebook evaluates the model performance using:
  - **Accuracy**: The proportion of correct predictions.
  - **F1-Score**: The balance between precision and recall.

### 4. Overfitting Analysis
- A justification is provided based on the comparison of performance metrics between training and testing datasets to determine whether the model is overfitting.

## Current Status

This portfolio is **incomplete** and focuses on initial data processing, basic model implementation, and preliminary evaluation. Further tasks such as feature selection, hyperparameter tuning, and performance visualization remain unfinished.

## How to Run
1. Install the required libraries:
   ```
    install pandas numpy scikit-learn

## Conclusion

This portfolio showcases the initial steps of building a binary classification model for predicting loan approval. Key processes like data cleaning, model training using logistic regression, and preliminary performance evaluation were successfully implemented. 

However, the portfolio remains incomplete, with several important steps still pending. These include recursive feature elimination for feature selection, hyperparameter tuning via grid search, and analysis of different distance metrics.
