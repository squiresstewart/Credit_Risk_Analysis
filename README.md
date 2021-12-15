# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to employ different machine learning techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, data is oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. A combinatorial of over- and undersampling is demonstrated in the SMOTEEN algorithm. Finally two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, are used to predict credit risk.

## Results:

### Balanced accuracy scores and the precision and recall scores of all six machine learning models:


- RandomOverSampler balanced accuracy score 63, precision .99, recall .53
![randomover.png](./Module-17-Challenge-Resources/randomover.png)

- EasyEnsembleClassifier balanced accuracy score 93, precision .99, recall .94
![easyensemble.png](./Module-17-Challenge-Resources/easyensemble.png)

- SMOTE accuracy balanced score 65, precision .99, recall .68
![smoteover.png](./Module-17-Challenge-Resources/smoteover.png)

- ClusterCentroids balanced accuracy score 65, precision .99, recall .68
![clustercentroid.png](./Module-17-Challenge-Resources/clustercentroid.png)

- SMOTEEN balanced accuracy score 65, precision .99, recall .57
![smoteencombo.png](./Module-17-Challenge-Resources/smoteencombo.png)

- BalancedRandomForestClassifier balanced accuracy score 76, precision .99, recall .88
![balancedrandomforest.png](./Module-17-Challenge-Resources/balancedrandomforest.png)

- Easy Ensemble AdaBoost Classifier balanced accuracy score 93, precision .99, recall .94
![EasyEnsembleAdaBoost.png](./Module-17-Challenge-Resources/EasyEnsembleAdaBoost.png)


## Summary: 
Based upon all models I think the RandomOverSampler is most suitable. It sacrifices some accuracy but had the least amount of recall which I feel is preferred given the objective. 

