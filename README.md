# Credit_Risk_Analysis

## Overview

In this project, we were asked to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate along with the following libraries:

1.imbalanced-learn

2.scikit-learn

3.RandomOverSampler

4.SMOTE algorithms

5.ClusterCentroids algorithm

6.LogisticRegression

7.SMOTEENN algorithm

8.BalancedRandomForestClassifier

9.EasyEnsembleClassifier

# Resources

Data Source: LoanStats_2019Q1.csv

## Results for the six machine learning models including balanced accuracy, precision, and recall scores below:

## Naive Random Oversampling
![Naive Random Oversampling](https://user-images.githubusercontent.com/114125836/231915496-ef6e5c0d-9d12-4ce7-8a1c-0970ca98938c.PNG)

Balanced Accuracy: 0.646602844334948, Precision: The precision shows low for High-risk loans but high for Low-risk loans, Recall: High/Low risk = .74/.55

## SMOTE Oversampling
![SMOTE Oversampling](https://user-images.githubusercontent.com/114125836/231915480-929b7cb4-cf44-4556-a258-6c2de9425baf.PNG)

Balanced Accuracy: 0.662394124702461, Precision: The precision shows low for High-risk loans but high for Low-risk loans, Recall: High/Low risk = .63/.69

## Undersampling
![Undersampling](https://user-images.githubusercontent.com/114125836/231915732-fefc4cc1-ad78-4c3a-8d58-7ad56410cb31.PNG)

Balanced Accuracy: Balanced Accuracy: 0.5442166848817717, Precision: The precision shows low for High-risk loans but high for Low-risk loans, Recall: High/Low risk = .67/.42

## Combination (Over and Under) Sampling
![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/114125836/231916849-c27f134f-4aea-45f7-a8e8-bd68f057d5b1.PNG)

Balanced Accuracy: Balanced Accuracy: 0.6400726134353378, Precision: The precision shows low for High-risk loans but high for Low-risk loans, Recall: High/Low risk = .70/.58

## Balanced Random Forest Classifier
![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/114125836/231917125-2dd9b6cc-353d-4c9c-8723-af24be41c539.PNG)

Balanced Accuracy: Balanced Accuracy: 0.7885466545953005, Precision: The precision shows low for High-risk loans but high for Low-risk loans, Recall: High/Low risk = .70/.87

## Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/114125836/231917251-7ab919d3-18e2-42d8-b9d2-88a213f0504e.PNG)

Balanced Accuracy: Balanced Accuracy: 0.9316600714093861, Precision: The precision shows low for High-risk loans but high for Low-risk loans, Recall: High/Low risk = .92/.94
