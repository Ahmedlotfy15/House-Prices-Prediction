# House Prices Prediction

This repository contains a project for predicting house prices using advanced regression techniques. The dataset used is the "House Prices: Advanced Regression Techniques" dataset from Kaggle.

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Requirements](#requirements)
4. [Project Steps](#project-steps)

## Overview

The goal of this project is to predict the sale price of houses based on various features such as overall quality, living area, and location. Multiple machine learning models, including Random Forest and XGBoost, are implemented and evaluated to determine the best-performing model.

## Dataset

The dataset is provided by Kaggle and includes a training set (`train.csv`) and a test set (`test.csv`). Each row corresponds to a house, and columns represent features such as the number of rooms, square footage, and more. The target variable is `SalePrice`.

- **Train Dataset**: Contains features and the target variable (`SalePrice`).
- **Test Dataset**: Contains features for which predictions need to be made.

You can download the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

## Requirements

To run this project, you'll need the following libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost


## Project Steps

1. **Data Exploration**
   - Load and inspect the data.
   - Check for missing values.
   - Visualize distributions and relationships between features.

2. **Data Cleaning**
   - Drop unnecessary columns.
   - Handle missing values using appropriate imputation strategies.

3. **Feature Engineering**
   - Create new features, such as `AgeOfHouse`, `TotalBsmtArea`, and `RoomsPerSqft`.
   - Encode categorical variables using `LabelEncoder`.

4. **Feature Selection**
   - Use `SelectKBest` to select the most important features for the model.

5. **Model Training and Evaluation**
   - Train models using Random Forest and XGBoost.
   - Evaluate models using metrics like RMSE, MAE, and R².
   - Perform cross-validation for robust evaluation.

6. **Submission**
   - Generate predictions on the test dataset.
   - Create a submission file in the required format.

