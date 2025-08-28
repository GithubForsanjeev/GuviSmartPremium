# Smart Premium
# 💰 Insurance Premium Prediction
- This project aims to build a machine learning model that accurately predicts insurance premiums based on various customer characteristics and policy details.
- It follows a structured MLOps-lite approach, covering data preprocessing, model training with MLflow tracking, and deployment using Streamlit.

## 🌟 Features

* **Data Preprocessing:** Handles missing values, encodes categorical features, and scales numerical data.
* **Multiple Regression Models:** Explores and evaluates Linear Regression, Decision Trees, Random Forest, and XGBoost.
* **MLflow Integration:** Tracks experiments, logs model metrics, parameters, and artifacts for reproducibility and comparison.
* **Automated ML Pipeline:** Combines preprocessing and model training into a streamlined workflow.
* **Interactive Web Application:** A user-friendly Streamlit interface for real-time premium predictions.
* **Modular Codebase:** Organized into `data`, `models` directories for clarity and maintainability.

## 🛠️ Technologies Used

* **Python**
* **Pandas**, **NumPy**
* **Scikit-Learn**
* **XGBoost**
* **MLflow**
* **Streamlit**

### Prerequisites

* Python 3.8+


## 🚀 Project Highlights
### 📊 Dataset Size: 1.2 million records × 21 features

### 🤖 Model Used: LightGBM Regressor

### 📈 Core Metrics:

    RMSE: ~₹845
    MAE: ~₹647
    R² Score: 0.036
### 📌 Must-have Features Used:

    Age
    Annual Income
    Health Score
    Credit Score
    Marital Status
    Policy Type