# Smart Home Energy Prediction

A machine learning regression project that predicts household appliance energy consumption using environmental, weather, lighting, and time-based features.

## Project Overview

The objective of this project is to predict appliance energy consumption (`Appliances`) from household sensor and environmental data.

The project covers the complete machine learning workflow:

* Data preprocessing
* Exploratory Data Analysis
* Feature engineering
* Data visualization
* Feature scaling
* Model training
* Model evaluation
* Model comparison
* Feature importance
* Prediction
* Model saving

## Dataset

**Source:** UCI Machine Learning Repository
**Dataset:** Appliances Energy Prediction

The dataset contains household energy consumption measurements along with indoor and outdoor environmental conditions.

**Target Variable:** `Appliances`

**Unit:** Watt-hours (Wh)

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

## Machine Learning Models

The following regression models were implemented and compared:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. K-Nearest Neighbors Regression
5. Decision Tree Regression
6. Random Forest Regression
7. Gradient Boosting Regression

## Model Evaluation

Models were evaluated using:

* **MAE** — Mean Absolute Error
* **RMSE** — Root Mean Squared Error
* **R² Score** — Coefficient of Determination

## Project Workflow

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Model Training
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Feature Importance
      ↓
Model Saving
```

## Project Structure

```text
Smart-Home-Energy-Prediction/
│
├── data/
│   └── energydata_complete.csv
│
├── models/
│   ├── best_energy_model.pkl
│   ├── energy_scaler.pkl
│   └── model_comparison.csv
│
├── energy_prediction.ipynb
├── README.md
└── requirements.txt
```

## Installation

```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib jupyter
```

## Dataset Source

UCI Machine Learning Repository
Appliances Energy Prediction Dataset

https://archive.ics.uci.edu/dataset/374/appliances%2Benergy%2Bprediction

## Author

**Devam Rajput**

B.Tech Computer Science Engineering
