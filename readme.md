#  Loan Approval Predictor

## Overview
A machine learning project that predicts whether a loan application 
will be approved or denied based on applicant financial and demographic 
data. Built using a dataset of 20,000 records with features including 
credit score, income, debt-to-income ratio, and employment status.

##  Technologies Used
- Python 3.x
- Pandas & NumPy — data cleaning and preprocessing
- Scikit-learn — machine learning models and evaluation
- Matplotlib & Seaborn — data visualisation

##  Models Built
- **Logistic Regression** — with Recursive Feature Elimination (RFE)
- **K-Nearest Neighbors (KNN)** — with Grid Search hyperparameter tuning
- **Cross Validation** — 5-fold cross validation for robust evaluation

##  Key Steps
1. Cleaned 20,000 records — handled missing values, removed duplicates
2. Applied One-Hot Encoding to categorical features
3. Built and evaluated Logistic Regression model
4. Performed RFE to identify most important features
5. Built KNN model and tuned K using Grid Search
6. Compared Euclidean, L1 and Cosine distance metrics
7. Analysed overfitting by comparing train vs test performance

##  Evaluation Metrics
- Accuracy
- F1-Score
- Confusion Matrix
- Classification Report

##  How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Portfolio_Part_3_Questions.ipynb
```

## Author
Prashant Khanal