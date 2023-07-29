# Bosch-Production-Line-Performance
This repo consists of the solution for the Bosch Production Line Performance competition from Kaggle (Dataset Link -> https://www.kaggle.com/c/bosch-production-line-performance/data).

The dataset is one of the largest datasets on Kaggle in terms of features and hence it is processed and used in the form of chunks

Preprocessing:

  Get to know the dataset[Data exploring](https://github.com/GuoyiMa/Bosch-Production-Line-Performance/blob/main/bosch/Data%20exploring.ipynb).

Feature Engineering:
  1. Selected the most important [numerical features](https://github.com/GuoyiMa/Bosch-Production-Line-Performance/blob/main/bosch/Numeric%20Classifier.ipynb) and [categorical features]() by XGBoost.
  2. Max-min time per station, per line [time feature]().
 
[Modelling]():
  Matthews correlation coefficient(mcc) is used as the evaluation metric.
  
  MCC obtained using the RandomForest is 0.39918 on private leaderboard and 0.38269 on public leaderboard.

