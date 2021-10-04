# Fraud_Detection_UseCase

## High-level problem statement
E-commerce websites often transact huge amounts of money. Whenever a huge amount of money is moved, there is a high risk of users performing fraudulent activities, e.g. using stolen credit cards, laundering money, etc. 

## Objective
The goal of this challenge is to build a machine learning model that predicts the probability that the first transaction of a new user is fraudulent.

## Details
Electronica is an e-commerce site that sells wholesale electronics. You have been contracted to build a model that predicts whether a given transaction is fraudulent or not. You only have information about each user’s first transaction on Electronica’s website. If you fail to identify a fraudulent transaction, Electronica loses money equivalent to the price of the fraudulently purchased product. If you incorrectly flag a real transaction as fraudulent, it inconveniences the Electronica customers whose valid transactions are flagged—a cost your client values at $8.

## Notebooks:
- Data_engineering_syntax_assessment.ipynb
- EDA_Data_science_assessment_fraud_data.ipynb [EDA notebook]
- Experimentation_Data_science_assessment_fraud_data.ipynb [Experimentation Notebook]

## Models:
- rf_gvc.pkl : Balanced random forest classifier
- ru_gcv.pkl : RUBoostClassifier
- mlp_gcv.pkl : MLP classifier
- xbg_gcv.pkl: XGBoostClassifier

