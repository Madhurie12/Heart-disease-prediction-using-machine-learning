# Heart Disease Prediction

This repository contains code for predicting heart disease using logistic regression. The code is implemented in Python and utilizes various libraries for data preprocessing, exploratory data analysis, and machine learning.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Heart disease is a common and potentially serious medical condition. Early detection and prediction of heart disease can help in effective treatment and prevention. This project aims to predict heart disease based on various patient attributes using logistic regression.

## Installation

To run the code locally, you need to have the following dependencies installed:

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the dependencies by running the following command:

## Usage

1. Clone this repository:


2. Navigate to the project directory:


3. Run the code:


## Dataset

The dataset used for this project is stored in the `heart.csv` file. It contains information about various patient attributes such as age, sex, cholesterol level, etc. The dataset has 1025 instances and 14 columns, including the target variable indicating the presence or absence of heart disease.

## Model Training

The code uses logistic regression, a popular machine learning algorithm for binary classification, to train a predictive model. The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn. The logistic regression model is then trained on the training set and evaluated on the testing set.

## Results

The accuracy score of the trained logistic regression model is computed using the `accuracy_score` function from scikit-learn. The accuracy score indicates the percentage of correct predictions made by the model on the testing set.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
