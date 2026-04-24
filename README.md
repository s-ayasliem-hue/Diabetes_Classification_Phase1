# Diabetes Health Indicators Prediction using XGBoost

## Project Overview
This project focuses on building a machine learning model to classify diabetes health indicators (Non-diabetic, Pre-diabetic, and Diabetic) using the **XGBoost** algorithm. The dataset is based on the BRFSS 2015 health indicators.

## Key Features
- **Class Imbalance Handling:** Implemented `sample_weight` to improve recall for minority classes (Diabetic and Pre-diabetic).
- **Data Preprocessing:** Handled duplicates, performed feature scaling, and stratified train-test splitting.
- **Model Optimization:** Tuned XGBoost parameters for better performance and avoided deprecated features.
- **Evaluation:** Comprehensive evaluation using Accuracy, ROC-AUC (OVR), and Confusion Matrix.

##  Results
- **Overall Accuracy:** ~84%
- **ROC-AUC Score:** ~0.74

## 🛠️ Technologies Used
- Python
- XGBoost
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn

##  Dataset
The dataset used is the [Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset-cdc) (BRFSS 2015).
