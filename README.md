# Weather Prediction Project

This project focuses on predicting weather conditions using hourly data. It employs various machine learning models, including Support Vector Machine (SVM), Random Forest, and others, to analyze the data and determine the best classifier based on accuracy.

## Project Overview

The goal of this project is to predict weather conditions using machine learning techniques. The dataset consists of hourly weather data, which is processed, analyzed, and used to train multiple models. The performance of these models is evaluated using cross-validation to identify the best performing classifier.

## Features

- **Data Handling**: Cleaned and processed hourly weather data.
- **Modeling**: Implemented multiple machine learning algorithms:
  - Support Vector Machine (SVM)
  - Random Forest Classifier
  - Decision Tree Classifier
  - K-Neighbors Classifier
  - Logistic Regression
  - Naive Bayes Classifier
- **Evaluation**: Calculated cross-validation scores to assess model performance.
- **Hyperparameter Tuning**: Used GridSearchCV to find optimal hyperparameters for the Random Forest model.
- **Visualization**: Plots of model accuracies and performance metrics.

## Dataset

The dataset used in this project contains hourly weather observations. Each observation includes various features such as temperature, humidity, wind speed, visibility, and weather conditions.

## Installation

To run this project locally, ensure you have Python installed along with the following libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
