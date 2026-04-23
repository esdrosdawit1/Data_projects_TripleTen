# Project 4: Used Car Price Prediction

## Overview
This project involves building a model to predict used car prices based on technical specifications and other features.

## Objective
Develop a model that accurately predicts used car prices while considering prediction quality, speed, and training time.

## Approach 
Data Preprocessing: Cleaned and analyzed car data (handled missing values, encoded categoricals).
Model Training: Trained CatBoost, XGBoost, LightGBM, Random Forest, Linear Regression. Used RMSE for evaluation.
Optimization: Tuned hyperparameters for best performance (CatBoost best).
Feature Focus: Analyzed feature importance (e.g., mileage, registration year impact price).

## Models Used
- CatBoost
- XGBoost
- LightGBM
- Random Forest
- Linear Regression

## Conclusion
The model evaluation showed CatBoost as the top performer (RMSE: 1867.59, train time: 2.37s), followed by LightGBM (RMSE: 1943.41) and Linear Regression (RMSE: 3216.39), demonstrating CatBoost's effectiveness in predicting used car prices.

Deploying the model as a pricing tool for car dealerships or online marketplaces could streamline pricing decisions. Adding more features like car condition reports, service history, or regional market trends could improve prediction accuracy. The model could also be adapted for other vehicle types (like motorcycles, trucks) or expanded to predict price trends over time, aiding inventory management.

## Code
Code: [Used Car Price Prediction.ipynb](https://github.com/esdrosdawit1/data-science-portfolio/blob/main/Used-Car-Price-Prediction-Project/Used-Car-Price-Prediction-Project.ipynb)

## Data
The dataset contains technical specifications and prices of used cars. Due to data privacy restrictions, the dataset is not publicly available.
