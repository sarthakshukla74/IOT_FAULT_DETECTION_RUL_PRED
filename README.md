![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![LightGBM](https://img.shields.io/badge/LightGBM-Gradient%20Boosting-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

# Predictive Maintenance using Machine Learning

## Project Overview

This project predicts the **Remaining Useful Life (RUL)** of industrial machines using sensor data and machine learning. By analyzing machine behavior, maintenance history, and sensor trends, the model helps identify potential failures before they occur, enabling predictive maintenance and reducing downtime.

## Features

* Data cleaning and preprocessing
* Outlier detection and capping
* Correlation analysis and visualization
* Rolling mean and rolling standard deviation feature engineering
* Delta feature generation for anomaly detection
* Machine age calculation
* One-hot encoding of categorical variables
* Random Forest Regression
* Hyperparameter tuning using RandomizedSearchCV
* LightGBM Regression
* Feature importance visualization

## Dataset

The dataset contains:

* Machine ID
* Machine Type
* Vibration readings
* Sound levels
* Temperature
* Power Consumption
* Maintenance History
* Failure History
* Error Codes
* Installation Year
* Remaining Useful Life (Target)

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* LightGBM

## Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
EDA & Visualization
      ↓
Feature Engineering
      ↓
Train-Test Split
      ↓
Random Forest Model
      ↓
Hyperparameter Tuning
      ↓
LightGBM Model
      ↓
Performance Evaluation
```

## Model Evaluation

Metrics used:

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

## Key Feature Engineering

* Rolling Mean (30-window)
* Rolling Standard Deviation (30-window)
* Sensor Delta Features
* Machine Age
* Historical Maintenance Indicators

These features help capture machine degradation patterns over time.

## Results

The LightGBM model achieved strong predictive performance and provided feature importance insights for identifying the most influential machine health indicators.

## Future Enhancements

* XGBoost and CatBoost implementation
* SHAP-based model explainability
* Streamlit dashboard deployment
* Real-time IoT integration
* Maintenance alert system

## Installation

```bash
git clone <repository-url>
cd predictive-maintenance
pip install -r requirements.txt
```

## Run

```bash
python main.py
```

## Author

**Sarthak Shukla**

B.Tech (CSDS) | Machine Learning & Data Science Enthusiast
