# Financial Fraud Analysis

Dataset Link - [Here](https://www.kaggle.com/datasets/sriharshaeedala/financial-fraud-detection-dataset)

# Introduction 

Financial Fraud Detection is the process of monitoring transactions and customer behavior to identify and stop fraudulent activity. In this project we have analysed the Financial data to detect fradulent acivity to curb company financial losses and maintain positive customer relations.

# About the dataset 

The dataset is a synthetic representation of mobile money transactions, usually to carried out real-world financial activities while integrating fraudulent behaviors for research purposes. The dataset encompasses a variety of transaction types including CASH-IN, CASH-OUT, DEBIT, PAYEMENT, and TRANSFER over a simulated period of 30 days.

- The memory usage of the DataFrame is approximately 534.0+ MB.
- The dataset contains 6,362,620 entries.
- It has 11 columns.
- The columns include:
  - **step**: An integer representing the time step of the transaction.
  - **type**: Categorical variable indicating the type of transaction.
  - **amount**: Float value representing the amount of the transaction.
  - **nameOrig**: Object type representing the name of the origin account.
  - **oldbalanceOrg**: Float value indicating the old balance of the origin account before the transaction.
  - **newbalanceOrig**: Float value indicating the new balance of the origin account after the transaction.
  - **nameDest**: Object type representing the name of the destination account.
  - **oldbalanceDest**: Float value indicating the old balance of the destination account before the transaction.
  - **newbalanceDest**: Float value indicating the new balance of the destination account after the transaction.
  - **isFraud**: Binary integer indicating whether the transaction is fraudulent (1) or not (0).
  - **isFlaggedFraud**: Binary integer indicating whether the transaction was flagged as fraudulent (1) or not (0).
