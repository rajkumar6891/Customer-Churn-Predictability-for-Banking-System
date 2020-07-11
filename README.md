# Customer-Churn-Predictability-for-Banking-System

## In this project, we are mainly concerend about correctly identifying "Exited = 1" values, so we will check which above ML models
## give the best F1-score for "Exited=1". As we can see in the above algorithms that even though we got a better accuracy using
## imbalanced data, ehat we are concered here about is the F1 score for Exited=1. From all the algorithms implemented after
## identifying the best parameters, upsampling and downsampling, we can see that eventhough the accuracy has went down with the
## downsampling considerably, the F1 score for the "1" is best with XGBoost after downsampling. So we can conclude that for the 
## given dataset, the best ML model is xgboost after downsampling the dataset.
