# Solar Flare Prediction
This repository contains code for predicting solar flares using a Random Forest model. The project includes hyperparameter tuning using Optuna to optimize the model's performance. The dataset includes features related to solar activity, such as detail of magnetic field strength and complexity. The goal is to predict the occurrence solar flares.

## Introduction
Solar flares, which are powerful bursts of energy from the sun that can disrupt technology on Earth.

These flares happen when the Sun's magnetic field lines, which are like invisible rubber bands, get twisted and tangled. This build-up of magnetic energy eventually becomes unstable and is released explosively, similar to a rubber band snapping when twisted too far. This energy heats the Sun's atmosphere to millions of degrees and accelerates particles to near the speed of light, creating the intense burst of radiation.

While Earth's atmosphere and magnetic field protect us from most of the harmful effects of solar flares, the radiation they emit can still cause some trouble.

The X-rays and extreme ultraviolet radiation from flares can disturb Earth's ionosphere, a layer that reflects radio waves. This can lead to radio blackouts and disruptions in navigation systems like GPS. The intense radiation can also damage satellites, affecting communication, navigation, and weather forecasting.  It can also increase drag on satellites in low Earth orbit, shortening their lifespan. In extreme cases, very strong flares can induce electrical currents in power grids, potentially causing widespread blackouts.

Predicting solar flares gives us a crucial heads-up, allowing us to take protective measures before their effects hit Earth. Satellites can be reoriented to minimise the surface area exposed to the radiation.  Sensitive instruments can be powered down. 
 
The Solar Dynamics Observatory (SDO) is a NASA satellite launched in 2010 to study the Sun. SDO captures images of the Sun's atmosphere, measures its magnetic field, and tracks solar flares and other activity.

NASA make this data available. This project aims to predict the occurance of flares using it.

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

