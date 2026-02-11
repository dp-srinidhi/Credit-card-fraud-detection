Credit Card Fraud Detection

📌 Dataset Overview

This dataset contains transactions made by credit cards in **September 2013 by European cardholders** and is used for detecting fraudulent credit card transactions.

- The dataset is highly **imbalanced** — the positive class (frauds) accounts for **only 0.172%** of all transactions.
- It contains only **numerical input features** resulting from a PCA transformation (to protect confidentiality).  
- The class label is stored in the `Class` column (0 = legitimate, 1 = fraud).

## 🧠 Attribute Information

| Feature | Description |
|---------|-------------|
| Time    | Seconds elapsed between this transaction and the first transaction in the dataset |
| V1–V28  | Principal components obtained with PCA (anonymized) |
| Amount  | Transaction amount |
| Class   | Target variable (0 = Legitimate, 1 = Fraud) |

Total Instances: **284,807**  
Fraudulent Transactions: **492** (~0.17%)

### 1. Download the Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
Extract the ZIP file — you should have a file called:

