﻿# ML_house_pricing
# Housing Dataset Analysis Documentation

## Introduction
This documentation provides an overview and detailed explanation of the analysis performed on the housing dataset.

## Dependencies
The code requires the following dependencies:
- matplotlib
- numpy
- pandas
- seaborn
- tensorflow
- scikit-learn
- keras

## Description
The provided code performs the following tasks:
- Imports necessary libraries.
- Loads the housing dataset from a CSV file.
- Provides an overview of the dataset.
- Performs data analysis including checking for missing values, removing missing values, and visualizing data distributions.
- Builds correlation matrices to identify relationships between features and the target variable.
- Removes highly correlated features.
- Creates new features based on existing ones.
- Encodes categorical variables.
- Splits the dataset into training and testing sets.
- Normalizes the data.
- Builds and trains a neural network model using Keras.
- Evaluates the model's performance on the test set.
- Visualizes the training loss per epoch.
- Evaluates regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Explained Variance Score.
- Compares model predictions with a perfect fit.
- Predicts the price of a brand new house using the trained model.

## Usage
To use this code:
1. Ensure all dependencies are installed.
2. Replace the file path in the `pd.read_csv()` function with the path to your dataset.
3. Run each code cell sequentially to perform the analysis.

## Example
```python
# Replace 'housing.csv' with the path to your dataset
df = pd.read_csv('housing.csv')
# Continue running each code cell as needed
