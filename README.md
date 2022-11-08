# Credit Risk Analysis

## Overview of the analysis: 
The purpose of this challenge was to determine credit worthiness. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we need to employ different techniques to train and evaluate models with unbalanced classes. Using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier. 

## Results: 
### 1. Using Resampling Models to Predict Credit Risk
Using my knowledge of the imbalanced-learn and scikit-learn libraries, I evaluated three machine learning models by using resampling to determine which is better at predicting credit risk. First, I used the oversampling RandomOverSampler and SMOTE algorithms, and then I used the undersampling ClusterCentroids algorithm. Using these algorithms, I resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generated a classification report.

![Report 1](https://github.com/pladams777/Credit_Risk_Analysis/blob/main/images/Capture1.PNG)

![Report 2](https://github.com/pladams777/Credit_Risk_Analysis/blob/main/images/Capture2.PNG)

![Report 3](https://github.com/pladams777/Credit_Risk_Analysis/blob/main/images/Capture3.PNG)

### 2. Using the SMOTEENN algorithm to Predict Credit Risk
Using my knowledge of the imbalanced-learn and scikit-learn libraries, I used a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms. Using the SMOTEENN algorithm, I resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generated a classification report.

![Report 3](https://github.com/pladams777/Credit_Risk_Analysis/blob/main/images/Capture4.PNG)

### 3. Using Ensemble Classifiers to Predict Credit Risk
Using your knowledge of the imblearn.ensemble library, you’ll train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, you’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

![Report 3](https://github.com/pladams777/Credit_Risk_Analysis/blob/main/images/Capture5.PNG)

![Report 3](https://github.com/pladams777/Credit_Risk_Analysis/blob/main/images/Capture6.PNG)

