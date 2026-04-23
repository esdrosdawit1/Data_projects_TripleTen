# 📊 Customer Churn Prediction

## 📌 Project Overview

Customer churn is a critical problem for subscription-based businesses. Losing customers directly impacts revenue, making it essential to identify and retain at-risk users.

In this project, I built and evaluated multiple machine learning models to predict whether a customer will churn, and analyzed which factors most influence customer retention.

---

## 🎯 Objective

The goal of this project is to:

* Predict customer churn using machine learning models
* Compare model performance using multiple evaluation metrics
* Identify key factors that influence churn

---

## 📂 Dataset

The dataset used is the **Telco Customer Churn dataset**, which contains information about:

* Customer demographics
* Account details
* Service subscriptions
* Billing information
* Churn status (target variable)

---

## 🧹 Data Preprocessing

* Handled missing values
* Converted categorical variables using encoding techniques
* Transformed target variable (`Churn`) into binary format (0 = No, 1 = Yes)
* Split data into training and testing sets

---

## 🤖 Models Used

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

---

## 📈 Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

### Key Insight:

Random Forest achieved the best overall performance, with a strong balance between precision and recall, making it the most reliable model for identifying churn.

---

## 📊 Visualizations

* Model comparison bar chart
* Confusion matrix heatmap
* Feature importance plot

These visualizations helped interpret model performance and understand prediction behavior.

---

## 🔍 Feature Importance

Feature importance analysis revealed that factors such as:

* Contract type
* Monthly charges
* Tenure

play a significant role in predicting customer churn.

---

## 💡 Conclusion

This project demonstrates how machine learning can be applied to predict customer churn and provide actionable insights for customer retention strategies.

By identifying high-risk customers and understanding key drivers of churn, businesses can take proactive steps to improve retention and reduce revenue loss.

---

## 🚀 Future Improvements

* Hyperparameter tuning for improved performance
* Handling class imbalance more effectively
* Deploying the model as an API or web application
* Incorporating time-based features for better prediction

---

## 🛠 Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 📎 How to Run

1. Clone the repository
2. Install required libraries
3. Run the notebook or script

---

## 📬 Author

[Esdros Yohannes]
