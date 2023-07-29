# Bosch-Production-Line-Performance
This repo consists of the solution for the Bosch Production Line Performance competition from Kaggle (Dataset Link -> https://www.kaggle.com/c/bosch-production-line-performance/data).

The dataset is one of the largest datasets on Kaggle in terms of features and hence it is processed and used in the form of chunks

1. Preprocessing:

  Get to know the dataset [Data exploring](https://github.com/GuoyiMa/Bosch-Production-Line-Performance/blob/main/bosch/Data%20exploring.ipynb).

2. Feature Engineering:
  2(1). Selected the most important numerical features by XGBoost [Numeric Classifier](https://github.com/GuoyiMa/Bosch-Production-Line-Performance/blob/main/bosch/Numeric%20Classifier.ipynb)
  2(2). Preprocessed the categorical features [delete T](https://github.com/GuoyiMa/Bosch-Production-Line-Performance/blob/main/code/delete%20T.ipynb) and selected the most important categorical features by XGBoost[Categorical Classifier](https://github.com/GuoyiMa/Bosch-Production-Line-Performance/blob/main/code/Categorical%20Classifier.ipynb).
  2(3). Max-min time per station, per line [second part of the modeling notebook](https://github.com/GuoyiMa/Bosch-Production-Line-Performance/blob/main/code/modeling.ipynb).
 
3. Modelling [code](https://github.com/GuoyiMa/Bosch-Production-Line-Performance/blob/main/code/modeling.ipynb):
  Matthews correlation coefficient(mcc) is used as the evaluation metric.
  
  MCC obtained using the RandomForest is 0.39918 on private leaderboard and 0.38269 on public leaderboard.

