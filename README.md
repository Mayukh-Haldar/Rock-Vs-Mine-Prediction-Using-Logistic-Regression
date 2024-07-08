# Sonar Rock vs Mine Prediction

This project aims to predict whether an object is a rock or a mine using sonar returns. The model used for this binary classification task is a Logistic Regression model, which is well-suited for this type of problem.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)

## Overview
This project focuses on classifying objects as either rocks or mines based on sonar data. The data consists of 60 frequency-based features derived from sonar signals. A Logistic Regression model is used to make the binary classification between rock and mine.

## Dataset
The dataset used in this project is the [Sonar, Mines vs. Rocks Data Set](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+%28Sonar,+Mines+vs.+Rocks%29) from the UCI Machine Learning Repository. It contains 208 instances and 60 attributes.

## Dependencies
The project requires the following Python libraries:
- pandas
- numpy
- sklearn

You can install the dependencies using the following command:
```
pip install pandas numpy sklearn
```
## Model Training
The Logistic Regression model is trained using the sonar dataset. The following steps are involved in the training process:

1. Data Loading: Load the dataset using pandas.
2. Data Preprocessing: Separate the features from the labels.
3. Train-Test Split: Split the data into training and testing sets.
4. Model Training: Train the Logistic Regression model on the training set.
5. Model Evaluation: Evaluate the model on the testing set.

## Evaluation
The model's performance is evaluated using the accuracy score. These metric provide insights into how well the model is able to distinguish between rocks and mines.

## Usage
To use the model for prediction, follow these steps:

Clone the repository:
```
git clone https://github.com/Mayukh-Haldar/Rock-Vs-Mine-Prediction-Using-Logistic-Regression.git
cd Rock-Vs-Mine-Prediction-Using-Logistic-Regression
```
Run the Jupyter Notebook:

Start the Jupyter Notebook server and open the notebook:
```
jupyter notebook
```
This will open a new tab in your web browser. Navigate to the notebook file sonar-rock-vs-mine-prediction.ipynb and run the cells to see the code and results.


## Results
The Logistic Regression model achieved the following results on the test set:

Accuracy: 85.714%

## Conclusion
The Logistic Regression model demonstrates good performance in classifying sonar signals as either rocks or mines. Future improvements could include trying other machine learning models, performing feature selection, and tuning hyperparameters for better accuracy.
