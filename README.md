# Credit_Risk_Analysis

## Overview of Analysis:

The purpose of this analysis was to create a supervised machine learning model that can be used to accurate predict whether someone is a credit risk. Credit risk is an unbalanced classificiation problem because there are plenty of good loans to outnumber all the risky loans. Therefore, different techniques will be needed to evaluate and train the models with unbalanced classes.

Imbalanced-learn and scikit-learn librariers will be used to build the models and evaluate them as well, by resampling. For this analysis, 6 different models will be used:

1. RandomOverSampler oversampling
2. SMOTE oversampling
3. Cluster Centriod undersampling
4. SMOTEEN over-and-undersampling
5. BalanacedRandomForestClassifier
6. EasyEnsembleClassifier

Each model will have it's performance evaluated to see if it would be a good recommendation for predicting credit risk.


## Results:

The balanced accuracy score, the confusion matrices, and the imbalance classificaiton reports are shown for each model in the images below.


RandomOverSampler Model:

![naive_random](https://user-images.githubusercontent.com/75760493/120284233-ad5c2900-c281-11eb-9397-6e2e5a537156.PNG)


SMOTE Model:

![SMOTE](https://user-images.githubusercontent.com/75760493/120284300-b9e08180-c281-11eb-9d92-a217cb5a43ad.PNG)


ClusterCentroids Model:

![Cluster](https://user-images.githubusercontent.com/75760493/120284346-c664da00-c281-11eb-8714-a86567ef67ff.PNG)


SMOTEEN Model:

![combo](https://user-images.githubusercontent.com/75760493/120284411-d54b8c80-c281-11eb-9641-7f5551934ef2.PNG)


BalancedRandomForestClassifier Model:

![Forest](https://user-images.githubusercontent.com/75760493/120284730-2d828e80-c282-11eb-92bf-1d0e39e33996.PNG)


EasyEnsembleClassifier Model:

![Easy](https://user-images.githubusercontent.com/75760493/120285162-9c5fe780-c282-11eb-85c4-7b047863a93f.PNG)



## Summary:







