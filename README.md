# NCAA-Basketball-Game-Predictor
A machine learning approach to predict the outcomes of NCAA Basketball games using historical game data, team statistics, and tournament seeds.

# NCAA Basketball Prediction

This repository contains the code and resources for predicting NCAA Basketball game outcomes using machine learning techniques. The project is based on data provided by a Kaggle competition.

## Overview

The objective of this project is to develop a machine learning model that accurately predicts the outcomes of NCAA Basketball games. The dataset used for training and testing is provided by Kaggle and includes historical game data, team statistics, and tournament seeds.

## Dataset

The dataset used in this project consists of several CSV files that provide information on past NCAA Basketball games, team statistics, and tournament seeds. Some of the key files used in this project include:

- `MNCAATourneyCompactResults.csv`
- `MNCAATourneyDetailedResults.csv`
- `MNCAATourneySeeds.csv`
- `MNCAATourneySeedRoundSlots.csv`
- `MNCAATourneySlots.csv`
- `WNCAATourneySlots.csv`

## Methodology

The project follows these main steps:

1. Data preprocessing and feature engineering to prepare the dataset for training and testing.
2. Splitting the dataset into a training set and a test set.
3. Training a baseline model and then a neural network model using TensorFlow and Keras.
4. Evaluating the model's performance on the test set using metrics such as accuracy, precision, recall, and F1-score.

## Results

The current model achieved an accuracy of 89%, a precision of 89.92%, a recall of 86.85%, and an F1-score of 89.91% on the test set.

## Future Work

There are several possible improvements that can be made to enhance the model's performance:

- Incorporating additional features from the provided dataset.
- Experimenting with different machine learning algorithms and neural network architectures.
- Performing a more thorough hyperparameter optimization.

