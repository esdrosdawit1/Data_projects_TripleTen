# 💬 Sentiment Analysis of Movie Reviews

## 📌 Overview

This project focuses on building a machine learning model to classify movie reviews as **positive or negative** using Natural Language Processing (NLP) techniques. The goal is to transform raw text data into meaningful features and apply classification models to understand sentiment patterns in user reviews.

---

## 🎯 Objective

The objective of this project is to develop a model capable of accurately classifying movie reviews, with a target **F1-score of at least 0.85**, ensuring a strong balance between precision and recall.

---

## 🧠 Approach

### 1. Data Preprocessing

* Loaded and explored the IMDB movie review dataset
* Cleaned raw text data (removal of noise, normalization)
* Converted text into numerical features using vectorization techniques
* Prepared labels for binary classification (positive/negative)

---

### 2. Exploratory Data Analysis (EDA)

* Analyzed distribution of review lengths
* Examined most frequent words in positive vs negative reviews
* Identified patterns in sentiment-related language

---

### 3. Feature Engineering

* Applied text vectorization (e.g., TF-IDF / Bag-of-Words)
* Converted textual data into machine-readable format

---

### 4. Model Training

Two machine learning models were trained and compared:

* Logistic Regression
* Gradient Boosting Classifier

---

### 5. Evaluation

Model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score (primary metric)

The best-performing model achieved an **F1-score above 0.85**, meeting the project objective.

---

## 📊 Results & Insights

* Logistic Regression performed competitively and provided strong baseline results
* Gradient Boosting captured more complex patterns in the text data
* The model successfully distinguishes between positive and negative sentiment with high reliability

---

## 💡 Key Takeaways

* NLP preprocessing significantly impacts model performance
* Simpler models like Logistic Regression can perform very well on text classification tasks
* Evaluation metrics like F1-score are critical for balanced performance assessment

---

## 🚀 Potential Applications

This sentiment analysis model can be extended to:

* Movie recommendation systems
* Customer review analysis for businesses
* Social media sentiment monitoring
* Product feedback classification

Future improvements could include:

* Hyperparameter tuning
* Deep learning models (LSTM, Transformers)
* Aspect-based sentiment analysis (e.g., acting, plot, visuals)

---

## 🛠 Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* NLP techniques (TF-IDF / vectorization)
* Matplotlib / Seaborn

---

## 📂 Code

📓 [View Notebook](https://github.com/esdrosdawit1/Sentiment-Analysis/blob/main/Sentiment-Analysis.ipynb)
---

## 📁 Dataset

The IMDB movie reviews dataset was used for this project, containing labeled movie reviews for binary sentiment classification (positive/negative).
