# datastorm
Stage I of Datastorm

The final model uses a XGBoost algorithm.This algorithm gave the highest accuracy among catboost, random forests and lightgbm
Feature selection has been done to reduce any overfitting and training set has been balanced so that the majority class and minority class are equally represented.
Hyperparameter tuning via Grid search has been done though the code isn't shown. Hyperparameters suggested have not been used due to their poorer performance on the test set due to overfitiing
