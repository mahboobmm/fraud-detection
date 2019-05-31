# Fraud-Detection
Detect behavioural anomalies to identify fraudulent users

## Performs One-Class Classification
Final Version.ipynb contains all the updated code
1. Encode labels for categorical data -> Assigns numbers to categories
2. Extracts more features from dates
3. Merge fraudsters data with the transactions they have done to derive a pattern for each transaction
4. Since this is one class classification, OneClassSVM is perfect for this situation, derives a pattern for fraud transactions
5. Save all the users whose transactions were tagged by the SVM as fraudster
