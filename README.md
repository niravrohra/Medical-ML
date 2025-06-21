# Medical-ML

**Medical-ML** is a machine learning tool that classifies particles as gamma or hadron using supervised learning techniques. It leverages the UCI Gamma Telescope Dataset to distinguish between the two types of events based on observed features.

## Features

- Utilizes the MAGIC Gamma Telescope dataset from the UCI Machine Learning Repository.
- Implements multiple machine learning algorithms for classification, including:
  - K-Nearest Neighbors (KNN)
  - Decision Trees
  - Support Vector Machines (SVM)
  - Logistic Regression
  - Random Forest
- Performs preprocessing, training, evaluation, and comparison of model performance using metrics like accuracy, precision, recall, and F1-score.

## Dataset

The dataset contains 10 continuous features derived from high-energy gamma-ray telescope observations, with a binary classification label indicating whether the event is a gamma or hadron.

## Evaluation

Each model is evaluated based on:

- Confusion Matrix  
- Classification Report  
- ROC Curve  
- Cross-Validation Accuracy
