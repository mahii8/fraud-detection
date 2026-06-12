# Fraud Detection — E-commerce & Bank Transactions

## Overview

End-to-end fraud detection system for Adey Innovations Inc., covering
two transaction streams: e-commerce (Fraud_Data.csv) and bank credit
card transactions (creditcard.csv).

## Datasets

- Fraud_Data.csv — E-commerce transactions with behavioral & device context
- IpAddress_to_Country.csv — IP range to country mapping
- creditcard.csv — Anonymized bank credit card transactions (PCA features V1-V28)

## Tasks

| Task   | Description                                       | Branch |
| ------ | ------------------------------------------------- | ------ |
| Task 1 | Data analysis, preprocessing, feature engineering | task-1 |
| Task 2 | Model building and training                       | task-2 |
| Task 3 | SHAP explainability and recommendations           | task-3 |

## Key Metrics

- Primary: AUC-PR, F1-Score (accuracy is misleading on imbalanced data)
- Secondary: Confusion Matrix, ROC-AUC

## How to Reproduce

1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Download datasets and place in data/raw/
4. Run notebooks in order

## Author

Mahlet Adane| 10 Academy x Kifiya | Week 5 | June 2026
