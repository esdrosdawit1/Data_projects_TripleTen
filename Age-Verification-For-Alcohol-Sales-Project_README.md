# Project 1: Age Detection using Computer Vision

## Overview
This project involves building a model to detect a person's age from images using computer vision techniques.

## Objective
Develop a model that accurately predicts age from images to help supermarkets adhere to alcohol laws.

## Approach
- Data Preprocessing: Loaded and preprocessed images (resizing, normalization) using OpenCV and Python.
- Model Architecture: Built a CNN with Keras/TensorFlow, using Conv2D, MaxPooling, and Dense layers.
- Training & Evaluation: Trained on 80% data, validated on 20%. Used MAE for evaluation.
- Optimization: Tuned hyperparameters (learning rate, batch size) for better accuracy.


## Models Used
- Neural Network (CNN)_

## Conclusion 
The CNN model achieved a Mean Absolute Error (MAE) of ~5.2 years on the validation set, demonstrating potential for automating age checks in supermarkets. With further tuning and more data, accuracy could improve, enhancing its applicability.

## Code
Code: [Age Detection using Computer Vision.ipynb](https://github.com/esdrosdawit1/data-science-portfolio/blob/main/Age-Verification-For-Alcohol-Sales-Project/Age-Verification-For-Alcohol-Sales-Project.ipynb)

## Data
The dataset contains images with age labels. Due to data privacy restrictions, the dataset is not publicly available.
