# Nanodegree Engenheiro de Machine Learning

## Capstone
Vitor Bona de Faria

April, 2019

### Proposal
This project will build a solution for the "Santander Customer Transaction Prediction" problem. In this problem what is being predicted is the probability of a customer making a specific transaction in the future, regardless of the amount of money transacted.

### Installation	
This project requires Python 3.7.2 and the following libraries:
 - NumPy (1.15.1)
 - Pandas (0.23.4)
 - matplotlib (2.2.3)
 - scikit-learn (0.20.3)
 - scipy (1.1.0)

It's also necessary to have Jupyter Notebook installed.

### Execution
In a terminal or command line, go to the project base directory that contains this README and execute the following command:

    jupyter notebook customer_transaction_prediction.ipynb

This will open the jupyter notebook and the project file in your browser

### Data set 
All data is available in Kaggle (https://www.kaggle.com/c/santander-customer-transaction-prediction) and consists of anonymized data containing only numeric feature variables, the target binary column and a string column corresponding to the customer's ID. The data is composed of 2 files: train.csv, test.csv. Both files contain 200k observations and 201 features, named as:

var 0, var 1, ..., var 199, target.

#### Target
-   probability of executing a specific transaction in the future