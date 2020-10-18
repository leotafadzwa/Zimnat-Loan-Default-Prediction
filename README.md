# Zimnat Loan Default Prediction

## Overview
Giving loans is risky business. And the less you know about what loans will be paid, the harder it will be for you to manage that risk. Zimnat has provided a sample dataset of over 12,000 loans, many of them with money overdue. The challenge is to predict which loans will end in a missed payment, and which will not. 

## Packages 
Scikitlearn 
Pandas 
Numpy 
Seaborn 
Xgboost 
CatBoost

## Evaluation Metric
roc_auc_score

## Approach
The solution was built by combining two models i.e. Catboost and Xgboost. Date features were extracted to improve model performance. There is need for a detailed feature engineering. We used StratifiedKFold to ensure each fold is a good representative of the whole dataset. 
