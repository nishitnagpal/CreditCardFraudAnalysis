# Credit Card Fraud Analysis: A Data-Driven Approach

## Overview
Digital payments are rapidly evolving, but so are cybercriminals' methods. According to the Data Breach Index, over 5 million records are stolen daily. Fraud is a significant concern for both Card-Present and Card-not-Present transactions.

This project analyzes fraud patterns using a Kaggle dataset of credit card transactions, aiming to effectively uncover insights and patterns to mitigate fraud risk.
Dataset: Credit Card Fraud Dataset

## Problem Statement
The following analyses were conducted to understand and predict fraudulent behavior:

1. Fraud Detection Based on Transaction Location
  - Examined how distances from home and the last transaction affect fraud likelihood. (Unicode bullet)

2. Impact of Transaction Value on Fraud
  - Investigated the relationship between transaction values and fraud risk. (Unicode bullet)

3. Retailer and Fraud Correlation 
  - Analyzed the impact of repeated transactions with the same retailer on fraud. (Unicode bullet)

4. Effect of Chip and PIN Usage on Fraud
  - Studied the effectiveness of chip and PIN authentication in reducing fraud. (Unicode bullet)

5. Online vs. Offline Fraud Patterns
  - Compared fraud occurrences between online and in-store transactions. (Unicode bullet)

## Key Insights
1. Transaction Location
  - No conclusive relationship between fraud and transaction distances from home or the last transaction. (Unicode bullet)

2. Transaction Value
  - No clear patterns found correlating transaction values to fraud risk. (Unicode bullet)

3. Retailer Frequency
  - Fraud is more likely (88%) during repeat transactions with the same retailer. (Unicode bullet)

4. Chip and PIN Usage
  - Transactions using both chip and PIN had the lowest fraud rates (0.009%). (Unicode bullet)
  - Non-chip transactions without PIN authentication accounted for ~74% of fraud cases. (Unicode bullet)

5. Online vs. Offline Transactions
  - 95% of fraudulent transactions occurred in online orders, indicating higher susceptibility in the online payment ecosystem. (Unicode bullet)

## Libraries and Tools Used
- Data Manipulation: pandas, numpy 
- Visualization: matplotlib, seaborn
- Machine Learning Models: 
  - Logistic Regression, Decision Tree, XGBoost
  - Hyperparameter tuning with GridSearchCV
- Evaluation Metrics:
  - Confusion Matrix, ROC-AUC, Classification Report
- Data Preprocessing:
  - Standardization with StandardScaler
  - Oversampling using SMOTE for class imbalance handling

## Results
Detailed findings and visualizations are documented in the Jupyter Notebook. The analysis highlights areas where fraud detection mechanisms can be improved and emphasizes the importance of chip and PIN technology in preventing fraudulent transactions.
