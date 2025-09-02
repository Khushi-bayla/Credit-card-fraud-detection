Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, with fraudulent cases being much fewer compared to legitimate transactions. Various preprocessing methods, feature engineering, and ML models are applied to improve fraud detection accuracy.

📌 Features

1.) Data preprocessing (handling imbalance, scaling, feature selection)

2.) Exploratory Data Analysis (EDA) for insights into fraud patterns

3.) Machine Learning models implementation:

    a.) Logistic Regression

    b.) Decision Trees

    c.) Random Forest

    d.) XGBoost

4.) Model evaluation using metrics suitable for imbalanced datasets:

    a.) Precision, Recall, F1-score

    b.) ROC-AUC Curve

    c.) Confusion Matrix

5.) Comparison of model performance

📊 Dataset

The dataset used is the Kaggle Credit Card Fraud Detection Dataset:

1.) Link to Dataset:- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

2.) Total Transactions: 284,807

3.) Fraud Cases: 492 (~0.17% of all transactions)

4.) Fraudulent Transactions: 492 (~0.17% of all transactions)

📈 Results

1.) Precision: 98.7% → very few false alarms

2.) Recall: 79.6% → majority of fraud cases captured

3.) F1-Score: 88.1%

4.) MCC: 0.88 → balanced and reliable prediction even with dataset imbalance

5.) Suggested improvements via oversampling/undersampling (SMOTE, ADASYN) to enhance minority fraud detection.


