# Credit-Card-Scam-Detection
A Python-based machine learning project for detecting fraudulent credit card transactions using classification models.

📊 Dataset Details

Source: Kaggle – Credit Card Fraud Detection Dataset

Dataset Type: Tabular (CSV)

Total Transactions: 284,807

Fraudulent Transactions: 492

Legitimate Transactions: 284,315

Class Distribution: Highly imbalanced dataset

🔹 Features

Time: Seconds elapsed between each transaction and the first transaction in the dataset

V1 – V28: Anonymized features obtained using PCA (Principal Component Analysis)

Amount: Transaction amount

Class:

0 → Legitimate transaction

1 → Fraudulent transaction

🔹 Key Characteristics

Features are already scaled (except Time and Amount)

Severe class imbalance makes fraud detection challenging

Suitable for testing classification models and imbalance handling techniques

🔹 Objective

To build a machine learning model that accurately identifies fraudulent transactions while minimizing false positives, using precision-recall based evaluation metrics.

📌 Dataset Link (optional)

Available on Kaggle under “Credit Card Fraud Detection”
