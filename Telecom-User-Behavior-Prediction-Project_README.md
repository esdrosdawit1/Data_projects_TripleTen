# Project 6: Telecom User Behavior Prediction Project

## Overview
This project focuses on developing a machine learning model for mobile carrier Megaline. The goal is to analyze subscriber behavior and recommend one of two newer mobile plans: "Smart" or "Ultra." The task involves building a classification model to accurately predict the optimal plan for a user based on their usage data.

## Objective
To develop a robust machine learning classification model that analyzes subscriber behavior (calls, minutes, messages, MB used) and recommends the most suitable Megaline plan (Smart or Ultra). The primary objective is to achieve the highest possible accuracy, with a minimum threshold of 0.75, when evaluated on unseen test data.

## Approach
- Data Loading & Initial Review: The `users_behavior.csv` dataset was loaded, and its structure and contents were examined to understand available features and target variable (`is_ultra`).
- Data Splitting: The dataset was strategically split into training, validation, and test sets to ensure rigorous model development and unbiased performance evaluation.
- Model Development & Hyperparameter Tuning:
    - Logistic Regression: A Logistic Regression model was implemented, and its `C` regularization parameter was tuned to find an optimal balance between model complexity and generalization, aiming for the highest accuracy on the validation set.
    - Decision Tree Classifier: A Decision Tree model was developed, with its `max_depth` hyperparameter tuned to optimize performance on the validation set, preventing both underfitting and overfitting.
    - Random Forest Classifier: A Random Forest model was employed, and its hyperparameters (including `max_depth`) were systematically adjusted to identify configurations that yielded the best validation accuracy.
- Model Evaluation:
    - Each model's quality was investigated by assessing accuracy on the validation set during tuning.
    - The best-performing model was then retrained on the combined training and validation sets.
    - Final evaluation was performed on the independent test set, ensuring the accuracy met or exceeded the 0.75 threshold.
- Sanity Check: Model performance was benchmarked against a `DummyClassifier` baseline to confirm that the developed model learned meaningful patterns beyond simple chance.

## Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Dummy Classifier (for baseline comparison)

## Conclusion
This project successfully developed a machine learning model capable of recommending Megaline's Smart or Ultra plans with high accuracy. The **Random Forest Classifier** emerged as the top-performing model, achieving a final test accuracy of **0.786**. This significantly surpasses the project's target accuracy threshold of 0.75.

The effectiveness of the Random Forest model is further highlighted by its performance compared to the **DummyClassifier**, which yielded a baseline accuracy of approximately **0.705**. This substantial difference demonstrates that the developed model effectively learned intricate patterns from user behavior data, making robust and intelligent plan recommendations rather than merely making random guesses.

Throughout the development process, careful attention was paid to hyperparameter tuning for each model (e.g., `C` for Logistic Regression, `max_depth` for tree-based models). This iterative optimization was crucial for finding the optimal balance between model complexity and its ability to generalize to new, unseen user data, ultimately ensuring reliable and actionable insights for Megaline.

#Code
Code: [Telecom User Behavior Prediction.ipynb](https://github.com/esdrosdawit1/data-science-portfolio/blob/main/Gold-Recovery-Integrated-Project/Gold-Recovery-Integrated-Project.ipynb](https://github.com/esdrosdawit1/Data_projects_TripleTen/blob/main/Telecom-User-Behavior-Prediction-Project/Telecom-User-Behavior-Prediction-Project.ipynb)

## Data
The dataset used, `users_behavior.csv`, contains monthly behavior information for individual users, including `calls` (number of calls), `minutes` (total call duration), `messages` (number of text messages), `mb_used` (Internet traffic in MB), and `is_ultra` (the target variable: Ultra - 1, Smart - 0).
