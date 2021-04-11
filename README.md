## Overview of Analysis
### The Goal of the analysis was to implement multiple different machine learning(ML) models on a dataset provided by Lending Club to determine whether the ML models are good indicators of credit card risk.

## Results of Analysis
### - Random Oversampler - The accuracy score is .642, the percision score is .99 and the recall is .55
### - Smote OverSampling - The accuracy score is .662, the percision score is .99 and the recall is .69
### - ClusterCentroid UnderSampling - The accuracy score is .544, the percision score is .99 and the recall is .40
### - SMOTEEN Combination Sampling - The accuracy score is .647, the percision score is .99 and the recall is .57
### - Balanced Random Forest Classifier - The accuracy score is .789, the percision score is .99 and the recall is .87
### - Easy Ensemble AdaBoost Classifier - The accuracy score is .931, the percision score is .99 and the recall is .94

## Summary
### To accurately predict credit card risk, I would suggest using the Easy Ensemble AdaBoost Classifier as it has by far the highest accuracy, which means that with 93.1% accuracy, it will predict if a person is low_risk or high_risk. Also, this model scored the highest in recall(.94), meaning it has a very low number of false negative results. These two scores along with its high precision score (.99, the same as the other models) not only make it the best model out of those tested, it also makes it a great model to use in a real world setting.
