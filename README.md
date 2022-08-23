# Alvin-Smart-Money-Management-Classification-Zindi-

## Brief Description
The objective of this competition is to build a machine learning model that classifies each purchase into one of 13 different categories.There are ~400 purchases in train and ~600 in test. These ~1000 transactions have been verified by Alvin as the correctly classified, have a look on :(https://zindi.africa/competitions/alvin-smart-money-management-classification-challenge).

## solution overview:
I found this competition quite joyous. It was really challenging and i've learnt alot of data science techniques.

The competition posed several challenges:

1- Dataset is very small (400 transactions)

2- Imbalance dataset (one of the classes has only 2 instances in the training data)

3- Text, numerical, time series and categarical features

For that i've tried alot of approaches and my final submission contains :

* Feature engineering and aggregations
* Drop outliers (rows with the same data but different categories)
* Oversampling using SMOTE
* StratifiedKFold with 5 split
* NLP features : Automatic clustering using KMeans from CountVectrozer
* Stacking models and use OneVsRestClassifier from sklean


Although I didn't get good rank 30/221, the amount of feature engineering and modeling ideas I got from this competition was a treasure.
