 ML Project – Explainable AI Models

 ## Author
AyaSelim


# Diabetes Health Indicators Prediction using XGBoost


## Project Overview
This project focuses on building a machine learning model to classify diabetes health indicators (Non-diabetic, Pre-diabetic, and Diabetic) using the **XGBoost** algorithm. The dataset is based on the BRFSS 2015 health indicators.
This project applies multiple Machine Learning models (KNN, Random Forest, XGBoost) along with Explainable AI (XAI) techniques to interpret model predictions.

The goal is to build accurate models and explain their decisions using modern interpretability methods.
## Key Features
- **Class Imbalance Handling:** Implemented `sample_weight` to improve recall for minority classes (Diabetic and Pre-diabetic).
- **Data Preprocessing:** Handled duplicates, performed feature scaling, and stratified train-test splitting.
- **Model Optimization:** Tuned XGBoost parameters for better performance and avoided deprecated features.
- **Evaluation:** Comprehensive evaluation using Accuracy, ROC-AUC (OVR), and Confusion Matrix.


## 📁 Files in This Project

- data_preprocessing.ipynb → Data cleaning, EDA, feature engineering  
- KNN_model.ipynb → KNN implementation + explainability  
- RandomForest_model.ipynb → Random Forest + explainability  
- XGBoost_model.ipynb → XGBoost + explainability

- 
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




## ⚙️ Requirements

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost shap lime
