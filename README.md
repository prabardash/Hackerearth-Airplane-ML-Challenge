## About

This was a structured dataset ML Challenge conducted by Hackerearth. The goal is to predict severity of airplane crash.</br>

More details: [Challenge Link](https://www.hackerearth.com/challenges/competitive/airplane-accident-severity-hackerearth-machine-learning-challenge/problems/)



There are 3 notebooks in this repository:

1. [Analysis](https://github.com/prabardash/Hackerearth-Airplane-ML-Challenge/blob/master/Analysis.ipynb): The dataset is examined, feature relevance on target is found out. Few new features are added.

2. [Encoding](https://github.com/prabardash/Hackerearth-Airplane-ML-Challenge/blob/master/Encoding%20and%20Feature%20Testing.ipynb): Categorical features are encoded via various methods. The encoded features in dataset will be useful when using non-tree-based models

3. [Tree-based models + Evaluation](https://github.com/prabardash/Hackerearth-Airplane-ML-Challenge/blob/master/Tree%20Based%20Models%20%2B%20Evaluation.ipynb): Used RFE to select relevant features and applied Adaboost, Random Forest and Gradient Boost

The best test set accuracy achieved is 85.6%, while the dev set accuracy stands at 96%

## TODO

* ~~Add model evaluation metrics and visualizations~~
* Add one-hot encoding of categorical features
* Add and test using remaining tree-based methods- XGBoost, CatBoost
* Add non-tree ML models such as Naïve-Bayes, SVM etc.- to be tested on encoded dataset
* Create and test a Neural network model
