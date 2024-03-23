# Churn Prediction for TeleDom Telecom

## Project Description
The telecom operator "TeleDom" is looking to combat customer churn. To this end, its employees will start offering promo codes and special conditions to those planning to discontinue their communication services. In order to identify such users in advance, TeleDom needs a model that can predict whether a subscriber will terminate their contract. The operator's team has collected personal data on some clients, including information about their tariffs and services. The task is to train a model on this data to predict customer churn.

## Project Objectives and Tasks
The main goal of the project is to develop a machine learning model that can predict the likelihood of customer churn for the telecom operator TeleDom based on the analysis of their behavior and service usage. The project tasks include:
- Analyzing the provided data on clients and their service usage.
- Data preprocessing to prepare for model training.
- Selecting and training a machine learning model to predict churn.
- Evaluating the model's effectiveness using appropriate metrics.

Success criteria:
The project will be considered successful if the following indicators are achieved:
AUC-ROC is above 0.85.

## Skills and Tools
- python
- pandas
- numpy
- matplotlib
- seaborn
- phik
- sklearn
- pickle
- OneHotEncoder
- SparkSession
- pyspark
- CatBoostClassifier
- roc_auc_score
- accuracy_score
- LogisticRegression
- confusion_matrix

  
```bash

!pip install pyspark
!pip install phik
!pip install catboost
!pip install --upgrade scikit-learn


## General Conclusion

I successfully trained various models to predict customer churn, with the focus on logistic regression and CatBoost classifiers. The evaluation of these models was based on metrics such as ROC-AUC and accuracy score. The best model surpassed the ROC-AUC threshold set for success,AUC-ROC is above 0.85 indicating its potential to help TeleDom in its efforts to reduce churn. This accomplishment not only met the project's objectives but also provided valuable insights for improving customer retention strategies.

