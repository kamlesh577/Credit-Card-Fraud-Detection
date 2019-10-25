# Credit-Card-Fraud-Detection

Credit card fraud is increasing considerably with the development of modern technology and the global superhighways of communication. Credit card fraud costs consumers and the financial company billions of dollars annually, and fraudsters continuously try to find new rules and tactics to commit illegal actions. Thus, fraud detection systems have become essential for banks and financial institution, to minimize their losses. 

![Webp net-resizeimage (3)](https://user-images.githubusercontent.com/38343027/67157586-c4b7fe00-f34b-11e9-94f4-eccbd5e98c8a.jpg)

The most commonly techniques used fraud detection methods are Naïve Bayes (NB), Support Vector Machines (SVM), K-Nearest Neighbor algorithms (KNN). These techniques can be used alone or in collaboration using ensemble or meta-learning techniques to build classifiers. But amongst all existing method, ensemble learning methods are identified as popular and common method, not because of its quite straightforward implementation, but also due to its exceptional predictive performance on practical problems.

## Credit card fraud can happen in a variety of ways:

• Lost Card: used by the people who finds it.
  
• Card Number,CVV, etc : Seen by other person.
  
• Fake phone call convincing you to disclose your details.
  
• High level hacking from bank accounts.
    
• Credit card cloning is a form of identity theft in which scammers create a fake credit card by using data stolen from a        person's actual card.
  
Although incidences of credit card fraud are limited to about 0.1% of all card transactions, they have resulted in huge financial losses as the fraudulent transactions have been large value transactions. 

Throughout the financial sector, machine learning algorithms are being developed to detect fraudulent transactions. In this project, we are going to the same. Using a dataset of of nearly 28,500 credit card transactions and multiple unsupervised anomaly detection algorithms, we are going to identify transactions with a high probability of being credit card fraud. In this project, we will build and deploy the following machine learning algorithms:

## • Decision tree

## • logistic regression

## • Auto-Encoders

## • Local Outlier Factor (LOF)

## • Isolation Forest Algorithm
 
•  Out of these algorithm we cannot use Decision trees because Decision trees does not give importance to specific features and generalize to each and every feature.

•  Similarly we cannot use logistic regression as incidences of credit card fraud are limited to about 0.1% of all card transactions which is very low. Hence there is imbalance dataset.

• Auto Encoders cannot be used due to less accuracy and efficiency.
   
• So we will be using:     

• Local Outlier Factor (LOF)

• Isolation Forest Algorithm


In addition, we will explore the use of data visualization techniques common in data science, such as parameter histograms and correlation matrices, to gain a better understanding of the underlying distribution of data in our data set.

## Dataset
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.






