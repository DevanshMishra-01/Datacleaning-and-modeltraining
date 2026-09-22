# Heart Disease Prediction

A machine learning project that predicts heart disease risk from patient health indicators using a K-Nearest Neighbors (KNN) classifier.

## 📌 Overview

This project walks through cleaning a heart disease dataset, engineering features, training a KNN classification model, and evaluating its performance. The trained model powers a simple risk-assessment tool.

## 📂 Dataset

- File: `heart_cleaned.csv`
- Preprocessing done: missing value handling,label encoding and one-hot encoding of categorical features (Sex, ChestPainType, RestingECG, ExerciseAngina, ST_Slope), and feature scaling.

## 🧠 Model

- **Algorithm:** K-Nearest Neighbors (KNN)
- **Max Accuracy achieved as compared to naive bayes,logistic regreession models etc**
- **Artifacts saved:**
  - `Knn_model.pkl` — trained model
  - `Scaler.pkl` — fitted feature scaler
  - `features.pkl` — final column order used during training

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook


## 📊 Results


-Best and optimal model for this dataset is Knn with max accuracy
-The dataset is now cleaned 
-A simple but efficient heart disease preediction model

