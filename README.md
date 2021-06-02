# Credit_Risk_Analysis

## Overview of Analysis:

The purpose of this analysis was to create a supervised machine learning model that can be used to accurate predict whether someone is a credit risk. Credit risk is an unbalanced classification problem because there are plenty of good loans to outnumber all the risky loans. Therefore, different techniques will be needed to evaluate and train the models with unbalanced classes.

Imbalanced-learn and scikit-learn libraries will be used to build the models and evaluate them as well, by resampling. For this analysis, 6 different models will be used:

1. Naive Random oversampling
2. SMOTE oversampling
3. ClusterCentroid undersampling
4. SMOTEENN over-and-undersampling
5. BalanacedRandomForestClassifier
6. EasyEnsembleClassifier

Each model will have its performance evaluated to see if it would be a good recommendation for predicting credit risk.


## Results:

The balanced accuracy score, the confusion matrices, and the imbalance classification reports are shown for each model in the images below.


### RandomOverSampler Model:

![naive_random](https://user-images.githubusercontent.com/75760493/120285965-666f3300-c283-11eb-9a19-be8542561caf.PNG)

This model had a balanced accuracy score of 66.03%, with an overall precision of 99% and a recall of 58$%.


### SMOTE Model:

![SMOTE](https://user-images.githubusercontent.com/75760493/120290470-fb742b00-c287-11eb-83df-a9e4837f460f.PNG)

This model had a balanced accuracy score of 65.73%, with an overall precision of 99% and a recall of 68%.


### ClusterCentroids Model:

![Cluster](https://user-images.githubusercontent.com/75760493/120285756-31fb7700-c283-11eb-8641-e0f5962e95a3.PNG)

This model had a balanced accuracy score of 65.37%, with an overall precision of 99% and a recall of 40%.


### SMOTEENN Model:

![combo](https://user-images.githubusercontent.com/75760493/120285610-08dae680-c283-11eb-831a-97804383229a.PNG)

This model had a balanced accuracy score of 54.43%, with an overall precision of 99% and a recall of 57%.


### BalancedRandomForestClassifier Model:

![Forest](https://user-images.githubusercontent.com/75760493/120285433-dc26cf00-c282-11eb-9b23-cb7cf40be8d1.PNG)

This model had a balanced accuracy score of 78.85%, with an overall precision of 99% and a recall of 87%.


### EasyEnsembleClassifier Model:

![Easy](https://user-images.githubusercontent.com/75760493/120286316-b8b05400-c283-11eb-9473-73d5c7ae9558.PNG)

This model had a balanced accuracy score of 93.17%, with an overall precision of 99% and a recall of 94%.



## Summary:

From the evaluation results for each model, the Naive Random, SMOTE, ClusterCentroids, and SMOTTEENN models all yielded poor accuracy scores, with the highest being the Naive Random with 66% and the lowest being the SMOTTEENN with 54%. Not only did these four models yield poor accuracy scores, but they also had poor recall scores. The model with the highest recall was the SMOTE with 68% and the model with the lowest recall was the ClusterCentriods with only 40%. Even though all models had an overall high precision of 99%, the low accuracy and recall would make these models not ideal. However, based on the results from the models with a classifier (BalancedRandomForestClassifier and EasyEnsembleClassifer), both had a lot higher accuracy and recall than the previous models. The BalancedRandomForestClassifier model had an accuracy of 78.85%, a precision of 99% and recall of 87%. The EasyEnsembleClassifier model had an even better accuracy of 93.17%, a precision of 99% and a better recall of 94%. The higher the accuracy, precision, and recall a model has, the more credible it becomes for predicting an outcome. Out of all six models, the EasyEnsembleClassifier stands above the others with its suburb accuracy, precision, and recall. The EasyEnsembleClassifier model would be my recommendation for predicting credit risk.





