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

![naive_random](https://user-images.githubusercontent.com/75760493/120285965-666f3300-c283-11eb-9a19-be8542561caf.PNG)


SMOTE Model:

![SMOTE](https://user-images.githubusercontent.com/75760493/120285846-48093780-c283-11eb-9c39-3606a1b32363.PNG)


ClusterCentroids Model:

![Cluster](https://user-images.githubusercontent.com/75760493/120285756-31fb7700-c283-11eb-8641-e0f5962e95a3.PNG)


SMOTEEN Model:

![combo](https://user-images.githubusercontent.com/75760493/120285610-08dae680-c283-11eb-831a-97804383229a.PNG)


BalancedRandomForestClassifier Model:

![Forest](https://user-images.githubusercontent.com/75760493/120285433-dc26cf00-c282-11eb-9b23-cb7cf40be8d1.PNG)


EasyEnsembleClassifier Model:

![Easy](https://user-images.githubusercontent.com/75760493/120285162-9c5fe780-c282-11eb-85c4-7b047863a93f.PNG)



## Summary:







