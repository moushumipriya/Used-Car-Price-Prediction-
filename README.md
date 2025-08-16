Project Overview

This project predicts the selling price of used cars in the Australia using two regression models:

Linear Regression – A simple baseline model

Random Forest Regression – A more advanced model capturing non-linear relationships

The dataset is cleaned, processed, and encoded for categorical features. The project includes evaluation metrics and visual comparison between the two models.

Dataset

Source: Used Car Dataset (CSV)

Important Features:

ManufactureYear

Odometer (mileage)

Make

Model

Variant

ColourBody

Series

MinPrice (Target)

Unnecessary columns (IDs, URLs, Dealer info, registration) have been removed.

Key Features

Data Cleaning: Remove irrelevant columns, handle missing values

Categorical Encoding: LabelEncoder for categorical features

Train/Test Split: 80% training, 20% testing

Models: Linear Regression & Random Forest Regression

Evaluation Metrics: RMSE, MAE, R² Score

Visual Comparison: Predicted vs Actual scatter plot
