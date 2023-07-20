# credit-card-fraud-analysis
Credit Card Fraud Analysis project is based on detecting a particular pattern in which most of the fraud happens in the banking industry. A Machine Learning technique Logistic Regression has used in this project which classifies a transaction as legit or fraud. The coding part is done in Python Jupyter notebook.
Dataset link - https://rb.gy/iy0t7
Libraries used - numpy, pandas, sklearn for train_test_split, LogisticRegression and accuracy_score
  The dataset contains 284807 rows and 31 columns. The column names have been kept secret due to privacy issues because the data is related to customers' transaction.
There are only few transactions which are fradulent and others are legit. For model building purpose, the legit transaction is coded as 0 and fraud transaction as 1.
  Data pre-processing is done using several techniques.
Then the data is seperated on the basis of fraud and legit transactions.
Since there are only 0.17% of transactions are fraud, the data id undersampled.
So, under-sampling technique has used in this project in order to deal with highly unbalanced data.
In this technique, a sample of size equal to fraud transactions is drawn such that number of fraud transaction should be equal to the number of legit transactions.
  In order to develop a logistic regression model, the dependent variable is seperated out from independent variables.
The dependent variable is the status of the transaction, a legit or a fraud one?
  Then the crucial stage of the project comes, splitting of the data. Here, the dataset is splitted into training dataset and testing dataset. The size of training dataset is 80% and rest 20% is that of testing dataset.
The purpose of splitting the dataset is to develop a model on training dataset and and comapre its output with the testing dataset. 
This allows us to check the accuracy of the model which is very important model evolution parameter.
Higher the accuracy score, better is the model and simultaneously its chances to predict correct outcomes are also higher.
So, after model fitting, its accuarcy score came out to be 93.52% which is quite good.
