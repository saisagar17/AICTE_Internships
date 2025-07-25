# AICTE_Internships
# ⚡ EV Adoption Forecasting using Machine Learning

This repository contains a comprehensive analysis and machine learning model to forecast the adoption rate of Electric Vehicles (EVs) over time. The goal is to use historical data and predictive modeling to provide actionable insights for policymakers, automakers, and clean energy advocates.

---

## 🚀 Project Overview

With the global push toward sustainable transportation, predicting EV adoption trends is critical. This project leverages Python, data science techniques, and machine learning models to:

- Clean and analyze EV-related datasets
- Visualize EV growth patterns
- Build predictive models for EV adoption
- Forecast future trends and growth rate

---

## 🧠 Technologies & Tools Used

| Category            | Tools / Libraries                          |
|---------------------|---------------------------------------------|
| Programming         | Python                                      |
| Data Manipulation   | Pandas, NumPy                               |
| Visualization       | Matplotlib, Seaborn, Plotly                 |
| Machine Learning    | Scikit-learn, XGBoost, Prophet              |
| Jupyter Notebook    | For development and visualization           |

---

## 📊 Features

- 📌 Data Cleaning & Preprocessing
- 📈 Trend Analysis & Visualization
- 🤖 Predictive Modeling with ML Algorithms
- 🔮 Forecasting Future EV Adoption
- 📉 Model Evaluation Metrics

---

## 📁 File Structure

```bash
📦EV_Adoption_Forecasting
 ┣ 📓 EV_Adoption_Forecasting.ipynb
 ┣ 📓 EV_Adoption_Forecasting_Optimized.ipynb
 ┣ 📁 data/
 ┃ ┗ 📄 ev_data.csv (example data file)
 ┣ 📄 README.md

## 📈 Model Features

The forecasting model includes sophisticated feature engineering:

- **Time-based features**: Months since start, seasonal patterns
- **Lag features**: Previous 1-3 months EV totals
- **Rolling statistics**: 3-month moving averages
- **Growth metrics**: Percentage changes and growth slopes
- **Cumulative metrics**: Total EV adoption over time
- **Categorical encoding**: County and state information

## 🔧 Usage

1. **Run the Jupyter Notebook**:

jupyter notebook EV_Adoption_Forcasting.ipynb


2. **Or run as Python script**:
The notebook can be converted to a Python script for automated forecasting.

## 📊 Model Performance

The Random Forest Regressor model provides:
- Feature importance analysis
- Time series validation
- Multiple evaluation metrics (MAE, MSE, R²)
- Prediction confidence intervals

## 🎯 Key Features

- **Data Preprocessing**: Handles missing values, date parsing, and feature scaling
- **Feature Engineering**: Creates lag features, rolling statistics, and growth metrics
- **Model Training**: Random Forest with hyperparameter tuning
- **Evaluation**: Comprehensive model performance metrics
- **Visualization**: Charts showing trends, predictions, and feature importance
- **Forecasting**: Ability to predict future EV adoption rates

