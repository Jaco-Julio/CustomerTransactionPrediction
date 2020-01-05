# Santander Customer Transaction Prediction Kaggle Challenge

Kaggle Project - In order to practice data science and machine learning techniques.

## Description

This challenge aims to build Classifiers capable to predict a santander customer transaction.  
The dataset contains 201 features and a class with two labels (transaction or non-transaction). PCA has been made for most features and the class is very unbalanced.  
The features are continuous quantitative and The dataset has 200,000 instances.  

## Exploratory Analysis and creating a good classifier

Exploratory analysis and creation of the best classification model will be described step by step.

1. The dataset from hd was loaded. Because of the file size we could not upload it to github.
2. The labels were visualized and the imbalance was noticed. The label "non-transaction" was 89.95% of the dataset, and the label "transaction" was 10.05% of the dataset. This imbalance may result in overfitting or a bad classifier.
3. The dataset was divided into features and label.
4. The balance was done with the SMOTE technique. This technique creates synthetic instances at random just like labels.
5. After the balance, the features and label were concatenated, and it was made a correlation matrix.
6. There was a reduction of features and left only 38 features. Because I could not run the algorithm for lack of memory.
7. The dataset was divided into training set and test set.
8. A new training set and test set were made, but these are normalized.
9. A new training set and test set were made, but these were standardized.
10. The Logistic Regression, AdaBoosting, Random Forest, Naive Bayes Gaussian and XGBoosting algorithms were chosen for classification.
11. The test set was classified and the main metric techniques were used to determine the best classifier. There was also the confusion matrix of the classifiers.

## Analysis of results
