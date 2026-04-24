# 🧠 Age Verification Using Computer Vision

## 📌 Project Overview

Accurately verifying a customer’s age is essential for businesses that sell age-restricted products such as alcohol. Manual ID checks can be time-consuming and prone to human error.

In this project, I built a deep learning model to estimate a person’s age from facial images using computer vision techniques, with the goal of supporting automated age verification systems.

---

## 🎯 Objective

The goal of this project is to:

* Predict a person’s age from facial images using deep learning  
* Evaluate model performance using regression metrics  
* Explore the feasibility of automating age verification in retail environments  

---

## 📂 Dataset

The dataset consists of labeled facial images with corresponding age values.

* Images of individuals across various age groups  
* Target variable: Age (continuous numerical value)  

> Note: The dataset is not publicly available due to privacy restrictions.

---

## 🧹 Data Preprocessing

* Resized images to a consistent input shape  
* Normalized pixel values for improved model convergence  
* Split data into training and validation sets (80/20)  

---

## 🤖 Model Used

* Convolutional Neural Network (CNN)

The model includes:
* Conv2D layers for feature extraction  
* MaxPooling layers for downsampling  
* Dense layers for final age prediction  

---

## 📈 Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)

### Key Result:

The model achieved a **Mean Absolute Error (MAE) of ~5.2 years**, meaning predictions are, on average, within ~5 years of the actual age.

---

## 📊 Visualizations

* Training vs validation loss curves  
* Sample predictions vs actual ages  

These visualizations helped monitor model performance and identify potential overfitting.

---

## 🔍 Key Insights

* The model is capable of learning meaningful facial features related to age  
* Performance is sensitive to image quality and lighting conditions  
* Predictions are more accurate for middle age groups than extreme age ranges  

---

## 💡 Conclusion

This project demonstrates how computer vision and deep learning can be used to estimate age from images and support automated decision-making systems.

Such models can help businesses improve efficiency and compliance when handling age-restricted sales.

---

## 🚀 Future Improvements

* Use transfer learning (e.g., pretrained models like ResNet)  
* Apply data augmentation to improve generalization  
* Train on a larger and more diverse dataset  
* Deploy the model as a real-time application (web or camera-based system)  

---

## 🛠 Tools & Technologies

* Python  
* TensorFlow / Keras  
* NumPy  
* OpenCV  
* Matplotlib  

---

## 📎 How to Run

1. Clone the repository  
2. Install required libraries  
3. Open and run the Jupyter Notebook  

Notebook:  
https://github.com/esdrosdawit1/Data_projects_TripleTen/blob/main/Age-Verification-For-Alcohol-Sales-Project/Age-Verification-For-Alcohol-Sales-Project.ipynb  

---

## 📬 Author

**Esdros Yohannes**
