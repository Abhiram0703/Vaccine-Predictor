# Vaccine Uptake Prediction Project

This machine learning project predicts the probability of an individual taking a particular vaccine using a **Random Forest Classifier**. The model analyzes input data to provide personalized vaccine uptake predictions based on key influencing factors.

## 1. Project Overview

- The objective is to predict the likelihood of vaccine uptake by analyzing individual data. Using a Random Forest Classifier, the model identifies and assesses the impact of various factors on vaccine decision-making.
- Comprehensive data cleaning and preprocessing were conducted to ensure high-quality inputs, transforming raw data into structured formats for accurate model training.

## 2. Data Processing

- Training data processing was done in `prepro.ipynb`.
- Testing data was processed in `prepro_test.ipynb`.
- The processed data was then exported as CSV files:
  - `train.csv` for model training
  - `test.csv` for model testing

## 3. Model Selection

- The **Random Forest Classifier** was chosen for its robust performance in classification tasks and its ability to handle complex interactions within the dataset.
- Model training and prediction generation were carried out in `model.ipynb`.
- The model evaluates various individual factors and predicts the probability of vaccine uptake for each individual.

## 4. Evaluation

- Predictions are saved in `submit.csv`, which contains the final probability scores of vaccine uptake for each individual.
  
This project workflow ensures that data preprocessing, model training, and prediction generation are clear and reproducible.
