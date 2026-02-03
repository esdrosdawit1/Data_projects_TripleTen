# Project 2: Gold Recovery Prediction

## Overview
This project aims to predict gold recovery from gold ore using machine learning models.

## Objective
Develop a model to predict gold recovery and evaluate its performance.

## Approach 
- Data Preparation: Cleaned and analyzed industrial process data, handled missing values.
- Feature Engineering: Selected relevant features impacting gold recovery (correlation analysis).
- Model Training: Trained Random Forest, Linear Regression, Decision Tree using cross-validation.
- Model Optimization: Tuned hyperparameters for Random Forest (best performer).

## Models Used
- Random Forest
- Linear Regression
- Decision Tree

## Conclusion
The Random Forest model effectively predicted gold recovery from industrial process measurements, achieving an sMAPE of 8.58 on validation and 12.10 on test data, outperforming Linear Regression (sMAPE: 13.18) and Decision Tree (sMAPE: 12.86).

## Code
Code: [Gold Recovery Prediction.ipynb](https://github.com/esdrosdawit1/data-science-portfolio/blob/main/Gold-Recovery-Integrated-Project/Gold-Recovery-Integrated-Project.ipynb)

## Data
The gold recovery dataset contains industrial process measurements. Due to data privacy restrictions, the dataset is not publicly available.
