# Diabetes Prediction Android App using Machine Learning

An Android application powered by Machine Learning that predicts the likelihood of diabetes based on medical input parameters.  
The project combines a trained ML model with Android app integration to provide fast and simple diabetes risk prediction.

---

# Project Overview

This project demonstrates an end-to-end Machine Learning application pipeline:

- Data preprocessing
- Model training using Python
- Model serialization using Pickle
- Android app integration
- Real-time diabetes prediction

The application takes health-related inputs from users and predicts whether the person is likely to have diabetes.

---

# Features

- Android-based user interface
- Diabetes prediction using ML model
- Real-time prediction results
- Trained model integration
- Simple and lightweight design
- Fast inference performance

---

# Tech Stack

## Machine Learning
- Python
- Scikit-learn
- Pandas
- NumPy
- Jupyter Notebook

## Android Development
- MIT App Inventor / Android
- AI2 Extension Integration

## Dataset
- PIMA Indians Diabetes Dataset

---

# Machine Learning Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Feature Selection
4. Model Training
5. Model Evaluation
6. Model Export using Pickle
7. Android Integration

---

# Model Training

The model was trained using classification algorithms on the diabetes dataset to predict diabetic outcomes.

### Input Features
- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Output
- Diabetic
- Non-Diabetic

---

# Repository Structure

```bash
├── Diabetes_prediction_model_training.ipynb
├── android_app_for_diabetes_prediction_ml_model.ipynb
├── diabetes.csv
├── diabetes_model.pkl
├── diabetes_prediction_app.aia
├── README.md
