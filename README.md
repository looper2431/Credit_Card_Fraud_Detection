# Credit Card Fraud using R

Abstract Overview:

It  is  vital  that  credit  card  companies  are  able  to identify  fraudulent credit  card  transactions  so that  customers are  not  charged  for  items  that  they  did  not  purchase.  Such problems can be tackled with Data Science and its importance, along  with  Machine  Learning,  cannot  be  overstated. 

The aim of this R project is to build a classifier that can detect credit card fraudulent transactions. We will use a variety of machine learning algorithms that will be able to discern fraudulent from non-fraudulent one. By the end of this project, you will learn how to implement machine learning algorithms to perform classification.

The Credit Card Fraud Detection Problem includes modelling past credit card transactions with the data of the ones that turned out to be fraud. This model is then used to recognize whether a new transaction is fraudulent or not. Our objective here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications. Credit Card Fraud Detection is a typical sample of classification. In this process, we have focused on analysing and pre-processing data sets as well as the deployment of multiple machine learning algorithms such as Decision Trees, Logistic Regression, Artificial Neural Networks and finally, Gradient Boosting Classifier.

This model is just an execution of the above ideology on a much smaller scale.

# About the Dataset
- The dataset contains transactions made by credit cards in September 2013 by European cardholders.
- This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive     class (frauds) account for 0.172% of all transactions.
- It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Dowload Dataset from Kaggle (*Link Given Below*) :
https://www.kaggle.com/datasets/bikrambanerjee/credit-card-fraud

# Regarding the R code file
- R Studio is required for this project
- The dataset is to be uploaded in R Studio in the enviornment section.
- If you are using any other platform like Microsoft VS Code, Jupyter Notebook etc then simply open the .R file.