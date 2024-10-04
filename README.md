# Solar Flare Prediction
This repository contains code for predicting solar flares using a Random Forest model. The project includes hyperparameter tuning using Optuna to optimize the model's performance. The dataset includes features related to solar activity, and the goal is to predict the occurrence solar flares.

## Introduction
Solar flares are sudden eruptions of energy on the solar surface that can have significant impacts on space weather. Predicting solar flares is crucial for mitigating their effects on satellite communications, power grids, and other technologies. This project aims to build a machine learning model to predict the occurrence of solar flares based on various input features.

## Model Details
Model Type: Random Forest Classifier
Framework: Scikit-learn
Hyperparameters: Tuned using Optuna
- n_estimators: Number of trees in the forest
- max_depth: Maximum depth of the tree
- min_samples_split: Minimum number of samples required to split an internal node
- min_samples_leaf: Minimum number of samples required to be at a leaf node
- max_features: Number of features to consider when looking for the best split

Please refer to the model card for more information

