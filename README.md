# CreditCard_FraudDetection

PHASE 1️⃣: DEFINE PROBLEM
Problem Statement
Objective: Build a machine learning model to detect fraudulent credit card transactions

Business Context:

Financial institutions process millions of transactions daily
Fraudsters use stolen/compromised cards to make unauthorized purchases
Need accurate detection to prevent losses and protect customers
Key Challenges:

Class Imbalance: Fraud cases are extremely rare (~0.17% of all transactions)
False Positives: Blocking legitimate transactions harms customer experience
False Negatives: Missing fraud cases results in financial losses
Success Metrics:

Accuracy: > 85%
ROC-AUC: > 0.80 (good discrimination ability)
Recall: High sensitivity to catch fraud cases
Precision: Minimize false fraud alerts
Dataset Features:

Time: Seconds elapsed since first transaction
V1-V28: PCA-transformed numerical features (anonymized for privacy)
Amount: Transaction amount in dollars
Class: Target variable (0 = legitimate, 1 = fraudulent)
