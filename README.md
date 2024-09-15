# Appreciate-Wealth-Data-Science
This project demonstrates a machine learning approach to fraud detection using a Random Forest Classifier. The goal is to predict fraudulent transactions in a financial dataset. The dataset contains various features related to transactions. The analysis includes data preprocessing, feature engineering, model training, and evaluation.

# Features
Data preprocessing: Handling missing values, feature extraction, and encoding categorical variables.

Exploratory Data Analysis (EDA): Visualizations to understand the distribution of transaction amounts and fraud occurrences.

Model Building: Training a Random Forest Classifier to predict fraudulent transactions.

Model Evaluation: Metrics including precision, recall, F1-score, ROC curve, and confusion matrix.

# Dataset
The dataset used for this analysis is fraudTrain.csv, which includes the following columns:

amt: Transaction amount
is_fraud: Indicator of whether the transaction is fraudulent (1) or not (0)
trans_date_trans_time: Timestamp of the transaction
merchant, category: Categorical features
Additional columns with information such as customer details and transaction IDs.

# Usage

Load and preprocess the data:
The script performs initial data loading, cleaning, and feature engineering.

# Model Training and Evaluation:
A Random Forest Classifier is trained on the processed data, and its performance is evaluated using metrics such as classification report, confusion matrix, and ROC-AUC score.

# Visualization:
The script generates plots for:
Distribution of transaction amounts
Fraud vs. legitimate transactions
Confusion matrix

![download](https://github.com/user-attachments/assets/3f59c67d-f815-4416-9854-9096cf188540)

ROC curve

![download](https://github.com/user-attachments/assets/16485ea7-b397-47a0-8323-4822c91638b3)

View results: The results are saved and displayed, including a table showing the actual vs. predicted values.




# CreditCardAppreciateWealth
