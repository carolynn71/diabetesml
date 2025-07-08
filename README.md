# 🩺 Diabetes Prediction using Machine Learning (KNN)

This project aims to detect the likelihood of diabetes in patients using machine learning, specifically the **K-Nearest Neighbors (KNN)** algorithm. It leverages the **PIMA Indian Diabetes Dataset** and applies data preprocessing, visualization, model training, and evaluation techniques to build an effective binary classification model.

---

## 📌 Project Overview

- ✅ Built a classification model to predict the presence of diabetes
- 📊 Performed exploratory data analysis (EDA) using visualizations
- ⚙️ Preprocessed the dataset and scaled features
- 🧠 Trained and tuned the K-Nearest Neighbors (KNN) classifier
- 📈 Evaluated model performance using accuracy, confusion matrix, and classification report

---

## 🗂️ Dataset Used

- **PIMA Indian Diabetes Dataset**
- Features include: `Pregnancies`, `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`, `DiabetesPedigreeFunction`, `Age`, `Outcome`
- Target variable: `Outcome` (1 = Diabetic, 0 = Non-diabetic)

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** – data handling
- **Matplotlib**, **Seaborn** – data visualization
- **Scikit-learn** – ML model and evaluation
- **Jupyter Notebook**

---

## 📊 Exploratory Data Analysis

- Count plot of diabetic vs non-diabetic cases
- Boxplots and histograms to detect outliers and understand distributions
- Heatmap to visualize correlations
- Pair plots grouped by target class

---

## ⚙️ Model Building & Tuning

- Used **StandardScaler** for feature normalization
- Trained multiple KNN models for `k = 1 to 14`
- Chose the best `k` based on test accuracy and plotted scores
- Final model selected: **K = 13**

---

## 📈 Model Evaluation

- Achieved test accuracy: **XX%** *(Replace with your best accuracy)*
- Evaluated using:
  - Confusion Matrix
  - Precision, Recall, F1-score
  - Classification Report

---

## 🔍 Key Takeaways

- Learned to visualize and preprocess medical datasets
- Understood how distance-based algorithms like KNN depend on proper scaling
- Gained experience in tuning and evaluating classification models
- Highlighted the importance of EDA in ML workflows

---


