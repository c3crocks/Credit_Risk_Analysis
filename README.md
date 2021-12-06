# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to predict credit risk by evaluating machine learning models as below:
- Naive Random Oversampling
- SMOTE Oversampling 
- Undersampling 
- Combination (Over and Under) Sampling
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

## Results:

#### Naive Random Oversampling



#### SMOTE Oversampling 



#### Undersampling 



#### Combination (Over and Under) Sampling



#### Balanced Random Forest Classifier



#### Easy Ensemble AdaBoost Classifier




## Summary:

All the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high.
The Ensemble models brought a lot more improvment specially on the sensitivity of the high risk credits.
The EasyEnsembleClassifier model shows a recall of 92% so it detects almost all high risk credit. On another hand, with a low precision, a lot of low risk credits are still falsely detected as high risk which would penalize the bank's credit strategy and infer on its revenue by missing those business opportunities.
For those reasons I would not recommend the bank to use any of these models to predict credit risk.
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)