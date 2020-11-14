# Credit Card Fraud Detection

## OBJECTIVE
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## DATASET USED
The datasets contains transactions made by credit cards in September 2013 by european cardholders. You can download the same from [link](https://www.kaggle.com/mlg-ulb/creditcardfraud). This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## TOOLS
Python - TensorFlow, Keras, K Neighbors, Decision Tree, SVM Regression and Logistic Regression classfiers, Scikit learn, Numpy, Pandas, Seaborn 

## TECHNIQUES
I have used TensorFlow, Keras, K Neighbors, Decision Tree, SVM Regression and Logistic Regression classfiers to predict fraudulent credit card transactions.

The evaluation of a classifier's prediction performance is of great importance in order to be able to judge its usefulness, also in comparison to competing methods. Commonly used measures of classifier performance in the phase of model construction are accuracy, error rate, and the Area under the Receiver Operating Characteristics (ROC) curve (AUC). Given the class imbalance ratio, I have used Area Under the Precision-Recall Curve (AUPRC) to measure the accuracy of the model. Confusion matrix accuracy is not meaningful for such unbalanced classification.
- Precision-Recall curves: shows the tradeoff between precision and recall for different threshold. 
- F-Measure or F1 score: calculates the harmonic mean of the precision and recall. 
- Area Under Curve: summarizes the integral or an approximation of the area under the precision-recall curve.
