📘 Credit Card Default Prediction (UCI Dataset)

This project builds machine learning models to predict whether a credit card customer will default next month, based on demographic information, payment history, bill statements, and past payments.

🚀 Project Highlights

Full end-to-end data science workflow:

Exploratory Data Analysis (EDA)

Data cleaning and feature engineering

Handling outliers (winsorization)

One-hot encoding for categorical variables

Train/test split with stratification

Logistic Regression baseline

Random Forest main model

Cross-validation (5-fold)

Hyperparameter tuning with GridSearchCV

Threshold optimization (F1-score)

Feature importance analysis

Business insights for real-world use

📊 Main Results

Best model: Tuned Random Forest

AUC score: ~0.78

Key predictors: Recent late payments (PAY_0, PAY_2, PAY_3), credit utilization, bill amounts.

Applications:

risk scoring,

prioritization of collection actions,

credit line management,

early-warning systems.

📝 Notebook

The full analysis is in:
➡️ credit_default_prediction.ipynb

📚 Dataset

UCI Credit Card Default dataset:
[https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset/data)
