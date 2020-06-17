## About

This was a structured dataset ML Challenge conducted by Hackerearth. The goal is to predict severity of airplane crash.</br>

More details: [Challenge Link](https://www.hackerearth.com/challenges/competitive/airplane-accident-severity-hackerearth-machine-learning-challenge/problems/)



There are 3 notebooks in this repository:

1. Analysis: The dataset is examined, feature relevance on target is found out. Few new features are added.

2. Encoding: Categorical features are encoded via various methods. The encoded features in dataset will be useful when using non-tree-based models

3. Tree-based models + Evaluation: Used RFE to select relevant features and applied Adaboost, Random Forest and Gradient Boost

The best test set accuracy achieved is 85.6%, while the dev set accuracy stands at 96%

## TODO

* Add model evaluation metrics and visualizations
* Add one-hot encoding of categorical features
* Add and test using remaining tree-based methods- XGBoost, CatBoost
* Add non-tree ML models such as Naïve-Bayes, SVM etc.- to be tested on encoded dataset
* Create and test a Neural network model
