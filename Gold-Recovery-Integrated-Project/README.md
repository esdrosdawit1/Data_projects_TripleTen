# 🟡 Gold Recovery Prediction

## 📌 Overview
This project focuses on predicting gold recovery rates from industrial processing data using machine learning. Accurate predictions help optimize production efficiency and reduce operational losses in mining operations.

---

## 🎯 Objective
To build a machine learning model that accurately predicts gold recovery at different stages of the extraction process.

---

## 📊 Dataset
- Industrial mining dataset with 22,000+ records
- Includes features related to processing stages and material composition  
- Challenges:
  - Missing values  
  - Feature correlation  
  - Data preprocessing complexity  

---

## ⚙️ Approach

### 1. Data Preprocessing
- Handled missing values and removed irrelevant features  
- Performed feature engineering based on domain-specific relationships  
- Ensured no data leakage between training and test sets  

### 2. Modeling
- Trained multiple models:
  - Linear Regression (baseline)  
  - Random Forest (final model)  

- Random Forest selected for its ability to capture non-linear relationships  

### 3. Evaluation
- Metric used: sMAPE (Symmetric Mean Absolute Percentage Error)  
- Chosen due to its suitability for percentage-based prediction tasks  

---

## 📈 Results

- Final model: Random Forest
- Achieved: sMAPE = 2.16
- Improved performance significantly over baseline model  

👉 Interpretation:  
The model provides highly accurate predictions of gold recovery, making it useful for optimizing industrial processes.

---

## 💡 Key Insights
- Feature engineering significantly improved model performance  
- Certain process variables had a strong influence on recovery rates  
- Tree-based models outperformed linear approaches  

---

## 🧠 What I Learned
- Importance of preventing data leakage  
- How to work with complex industrial datasets  
- Model evaluation using specialized metrics like sMAPE  

---

## 🚀 Future Improvements
- Deploy model using Streamlit for real-time predictions  
- Experiment with advanced models (e.g., XGBoost)  
- Integrate real-time data pipelines  

---

## 🔗 Project Link
https://github.com/esdrosdawit1/Data_projects_TripleTen/blob/main/Gold-Recovery-Integrated-Project/Gold-Recovery-Integrated-Project.ipynb
