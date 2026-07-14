# Customer Churn Prediction

A machine learning project that predicts whether a telecommunications customer is likely to leave the company based on demographic, account, and service-related information.

## Project Overview

The project uses the Telco Customer Churn dataset from Kaggle. It includes data cleaning, exploratory data analysis, feature preprocessing, model training, performance comparison, and feature importance analysis.

## Models

The following classification models were evaluated:

- Random Forest
- Gradient Boosting
- Support Vector Machine

## Results

Gradient Boosting achieved the best overall performance:

- Accuracy: 79.5%
- ROC-AUC: 0.841
- F1-score: 0.580

SVM achieved the highest churn recall of 77.8%, meaning it detected the largest proportion of customers who actually left.

## Key Findings

The most influential churn factors included:

- Customer tenure
- Fiber optic internet service
- Electronic check payments
- Contract type
- Monthly and total charges

## Technologies

Python, pandas, NumPy, scikit-learn, Matplotlib, and Google Colab.

## Usage

Open `DM_PROJECT_T6.ipynb` in Google Colab, upload the Telco Customer Churn dataset ZIP file, and run the cells in order.

## Dataset

The project uses the Kaggle Telco Customer Churn dataset containing 7,043 customer records and 21 attributes.
