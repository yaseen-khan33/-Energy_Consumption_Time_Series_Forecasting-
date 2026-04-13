# ⚡ Energy Consumption Time Series Forecasting

## 📌 Problem Statement
Electricity consumption in households varies over time due to different usage patterns. Understanding these patterns and predicting future energy consumption is essential for efficient energy management and planning.

This project aims to analyze historical household power consumption data and forecast future energy usage using time-based patterns. By applying time series techniques and machine learning models, the project provides insights into energy usage behavior.

---

## 🎯 Objective
The main objectives of this project are:

- To analyze historical household energy consumption data  
- To preprocess and clean time series data  
- To convert raw data into a time-based format using resampling  
- To perform feature engineering (hour, day, month)  
- To build a forecasting model using XGBoost  
- To evaluate the model using MAE and RMSE  
- To visualize actual vs predicted energy consumption  

---

## 📂 Dataset
- Dataset Name: Household Power Consumption Dataset  
- Source: UCI Machine Learning Repository  
- File Used: `household_power_consumption.txt`  

---

## 🛠 Tools & Libraries
- Python  
- pandas  
- numpy  
- matplotlib  
- scikit-learn  
- xgboost  

---

## ⚙️ Project Workflow

1. Data Loading  
2. Data Cleaning  
3. Datetime Conversion  
4. Resampling (Hourly Data)  
5. Feature Engineering (hour, day, month)  
6. Model Training (XGBoost)  
7. Prediction  
8. Evaluation (MAE, RMSE)  
9. Visualization  

---

## 📊 Results & Insights

- Energy consumption follows time-based patterns (hourly & daily trends)  
- The model successfully captures usage patterns  
- XGBoost provides reasonable prediction accuracy  
- Prediction error is evaluated using MAE and RMSE  

---

## 📈 Visualization

The project includes a plot comparing:
- Actual energy consumption  
- Predicted energy consumption  

---

## 🚀 Conclusion

This project demonstrates how time series data can be used to forecast energy consumption. By applying feature engineering and machine learning techniques, we can predict future usage and support better energy planning.

---



