# BDA602 ML FraudBusters: Anti-Money Laundering Transaction Analysis

## Project Overview
This repository hosts our BDA602 final group project, focusing on the detection of money laundering activities using the IBM Transactions dataset. The aim is to develop machine learning models that can identify suspicious financial activities effectively.

## Objectives
- To develop predictive models that can accurately detect patterns of money laundering within financial transactions.
- Enhance financial security systems by implementing robust detection algorithms compliant with AML regulations.

## Datasets Description
**IBM Transactions for Anti Money Laundering (AML)**: This dataset provides synthetic transaction data simulating various financial scenarios, which include illicit activities such as smuggling and illegal gambling. Each transaction is labeled to indicate whether it is associated with money laundering.
- **Source**: [IBM AML Dataset on Kaggle](https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-laundering-aml/data)

### Datasets Used are "HI-Medium_Trans.csv" and "LI-Medium_Trans.csv"
This dataset comprises financial transactions aimed at detecting money laundering activities. Each entry is a transaction record, detailed as explained below.
#### Data Schema
- **Timestamp**: The time at which the transaction occurred, formatted as a string.
- **From Bank**: The identifier for the bank from which the money is sent, represented as an integer.
- **Account**: The account number from which the money is sent, formatted as a string.
- **To Bank**: The identifier for the bank receiving the money, represented as an integer.
- **Account.1**: The account number receiving the money, formatted as a string.
- **Amount Received**: The amount of money received, represented as a float.
- **Receiving Currency**: The currency in which the money was received, formatted as a string.
- **Amount Paid**: The amount of money paid, represented as a float.
- **Payment Currency**: The currency in which the payment was made, formatted as a string.
- **Payment Format**: The method or format of the payment, formatted as a string.
- **Is Laundering**: A binary indicator (0 or 1) where 1 indicates a transaction flagged as potential laundering and 0 as non-laundering.

The dataset consists of over 31 million transaction records, providing a rich source for analysis and model training in detecting suspicious financial activities.
  
## Methodology
- **Data Preprocessing**: Standardization, handling missing values, and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: In-depth analysis to understand underlying patterns and anomalies.
- **Model Development**: Use of Logistic Regression, Decision Trees, and Random Forests for initial models, followed by more complex algorithms like Gradient Boosting Machines (GBM).
- **Model Evaluation**: Utilization of cross-validation and performance metrics (Accuracy, Precision, Recall, F1-Score, and AUC-ROC).

## Tools and Technologies
- **Python**: For data manipulation and model building.
- **Jupyter Notebook**: For interactive data exploration and visualizations.
- **Scikit-Learn, TensorFlow**: For implementing and training machine learning models.

## Team Members
- Sharad Parmar
- Dhrumil Buch
- Aayush Khandelwal
- Dipsy
