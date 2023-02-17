# Credit_Risk_Analysis
Challenge 18


## Analysis Overview
In this project, we use Python to build and evaluate several machine learning models to predict credit risk.


## Procedure:

Use Resampling Models to Predict Credit Risk:
- We oversample the data using the RandomOverSampler and SMOTE algorithms.
- Undersample the data using the ClusterCentroids algorithm.
Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.
We will evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results:

### RandomOverSampler model
The balanced accuracy score is 65%

The high_risk precision is: 1% 
The high_risk recall is: 61%

The low_risk precision is: 100%
The low_risk recall is: 68%


### SMOTE model
The balanced accuracy score is 62%

The high_risk precision is: 1% 
The high_risk recall is: 61%

The low_risk precision is: 100%
The low_risk recall is: 64%


### ClusterCentroids model
The balanced accuracy score is 52%

The high_risk precision is: 1% 
The high_risk recall is: 60%

The low_risk precision is: 100%
The low_risk recall is: 44%


### SMOTEENN model
The balanced accuracy score is 62%

The high_risk precision is: 1% 
The high_risk recall is: 69%

The low_risk precision is: 100%
The low_risk recall is: 54%


### BalancedRandomForestClassifier model
The balanced accuracy score is 79%

The high_risk precision is: 3% 
The high_risk recall is: 70%

The low_risk precision is: 100%
The low_risk recall is: 87%


### EasyEnsembleClassifier model
The balanced accuracy score is 93%

The high_risk precision is: 9% 
The high_risk recall is: 92%

The low_risk precision is: 100%
The low_risk recall is: 94%


## Summary:
When determining if a credit risk is high, we can see weak precision in all the models used to perform the credit risk analysis.
The best model if we pay attention to the sensitivity of the high risk credits, would be the Ensemble model.
The EasyEnsembleClassifier model detects almost all high risk credit (shows a recall of 92%). 

