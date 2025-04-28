# **Credit Card Fraud Detection**

## Project Overview

This project focuses on developing a classification model to detect fraudulent credit card transactions efficiently.
The dataset includes transaction amount, anonymized variables, timestamps, and merchant-related features.
The main goal is to create a fraud detection system that minimizes false positives while maintaining high accuracy.

## Dataset Access

The dataset used in this project can be accessed here:

Credit Card Fraud Detection Dataset - (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Total Records: 284,807 transactions

Fraudulent Transactions: 492 transactions

Normal Transactions: 284,315 transactions

# Preprocessing Steps

Scaling: Used StandardScaler for transaction amounts.

Handling Class Imbalance: Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the classes.

Train-Test Split: 80% for training, 20% for testing.

# Models Implemented


![image](https://github.com/user-attachments/assets/013f5f6f-f3c3-4bcc-a924-a2f4ab48e107)

# Best Model


![image](https://github.com/user-attachments/assets/de5d80ce-23ea-47d0-b754-b2186b0f9c67)

# Important Observations

SMOTE helped significantly in balancing the dataset and improving recall.

Without balancing, models would have biased towards the majority class (normal transactions).

Ensemble methods like Random Forest performed best in fraud detection scenarios.

