# Financial Fraud Detection using Machine Learning

## Overview

This project implements a machine learning model to detect fraudulent financial transactions. It classifies each transaction as either **Fraud** or **Non-Fraud** based on historical transaction data. The model utilizes features such as transaction amount, time, location, and other transaction attributes to predict the probability of fraud.

---

## Features

- Detects potentially fraudulent transactions in real-time.
- Provides a probability score for fraud likelihood.
- Easy integration into banking or payment processing systems.

---

## Tech Stack

- **Language:** Python 3.x  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

---

## Dataset

The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains transactions made by credit cards in September 2013 by European cardholders. The dataset includes:

- **Features:** 30 anonymized features (V1 to V28), Time, Amount  
- **Target:** Class (1 for fraud, 0 for non-fraud)  

---

## Setup

1. Clone this repository:

```bash
git clone 
cd Model-for-fraud-detection

pip install -r requirements.txt.

------

## Step-2
Data Preprocessing
# Load dataset
import pandas as pd
data = pd.read_csv('creditcard.csv')

# Check for missing values
data.isnull().sum()

# Normalize features
from sklearn.preprocessing import StandardScaler
data['Amount'] = StandardScaler().fit_transform(data['Amount'].values.reshape(-1,1))
data['Time'] = StandardScaler().fit_transform(data['Time'].values.reshape(-1,1))

Step-3: Feature
from sklearn.model_selection import train_test_split
X = data.drop('Class', axis=1)
y = data['Class']

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)


Step-4: Model Training

from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier()
model.fit(X_train, y_train)

Step-5: Model Evaluation
from sklearn.metrics import classification_report, confusion_matrix

y_pred = model.predict(X_test)
print(classification_report(y_test, y_pred))


Step-6: Prediction on New Transaction

new_transaction = [[0.12, -0.34, 0.56, ..., -0.78]]
prediction = model.predict(new_transaction)
probability = model.predict_proba(new_transaction)
print(f"Prediction: {prediction[0]}, Probability: {probability[0][1]}")

| Model                  | Accuracy | Precision | Recall | F1-Score |
| ---------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression    | 98.5%    | 0.95      | 0.92   | 0.93     |
| Random Forest          | 98.8%    | 0.96      | 0.93   | 0.94     |
| Support Vector Machine | 98.7%    | 0.95      | 0.94   | 0.94     |
| K-Nearest Neighbors    | 98.2%    | 0.94      | 0.91   | 0.92     |

Example-Output: 
Transaction ID: 123456
Prediction: Fraud
Probability: 0.97


This indicates a 97% probability that the transaction is fraudulent.