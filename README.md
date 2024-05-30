# Fraud Detection System
!['Transaction_Fraud_Analysis'](https://altair.com/images/default-source/resource-images/financial-fraud-protection-and-data-analytics-jpeg.jpeg?sfvrsn=13b40b5c_0)

## Overview

The Fraud Detection System is a machine learning-based application designed to detect fraudulent transactions in financial data. It utilizes a decision tree model trained on synthetic financial data to predict whether a transaction is fraudulent or not.

## Features

- Predicts whether a transaction is fraudulent based on input parameters such as transaction amount, card type, location, etc.
- Utilizes a decision tree model trained on synthetic financial data.
- Incorporates PCA (Principal Component Analysis) for feature transformation.
- Provides a user-friendly interface for inputting transaction details and viewing predictions.

## Usage

1. Enter the details of the transaction:
    - Transaction ID
    - Customer ID
    - Merchant ID
    - Amount
    - Transaction Date (YYYY-MM-DD)
    - Card Type
    - Location
    - Purchase Category
    - Customer Age
    - Transaction Description
    - Country

2. Click the "Predict" button to view the prediction result.

### App Link [Fraud Detection App](https://huggingface.co/spaces/riyadahmadov/Detect_Fraud_Transaction)

## Data Sources

- Kaggle Dataset : [Transaction Data for fraud analysis](https://www.kaggle.com/datasets/isabbaggin/transaction-fraudulent-financial-syntheticdata/data)

## Dependencies

- Python 3.x
- Pandas
- Gradio
- Scikit-learn
- JSON
- Pickle

## Contributors

- Riyad Ahmadov

## Contact

For any inquiries or feedback, please contact:

- Your Name: riyadehmedov03@gmail.com
