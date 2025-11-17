# ⚡ Energy Consumption Prediction

## 📘 Project Overview
This project focuses on predicting **energy consumption** using environmental variables such as temperature, humidity, light intensity, and CO₂ levels.  
The goal is to apply **data science** and **machine learning** techniques to build accurate predictive models and visualize results through an interactive dashboard.

---

## 🎯 Objectives
- Analyze and visualize energy-related data  
- Build a **Linear Regression model** to predict energy consumption  
- Train and compare a **Random Forest Regressor**  
- Identify most influential features  
- Perform **advanced EDA & feature engineering (Week 3)**  
- Train advanced models: **XGBoost** and **LSTM**  
- Create a **Streamlit Dashboard** for interactive visualization  

---

## 🧩 Dataset Information
The dataset is stored in:

```
data/energy.csv
```

### **Features Description**

| Feature            | Description                                  |
|-------------------|----------------------------------------------|
| Temperature       | Room temperature (°C)                        |
| Humidity          | Relative humidity (%)                        |
| Light             | Light intensity (Lux)                        |
| CO₂               | Carbon dioxide concentration (ppm)           |
| HumidityRatio     | Ratio of humidity to temperature             |
| EnergyConsumption | Energy consumed (kWh)                        |

---

## ⚙️ Technologies Used
- **Python 3**
- **Pandas, NumPy** — Data handling  
- **Matplotlib, Seaborn** — Data visualization  
- **Scikit-learn** — Machine learning models  
- **XGBoost** — Advanced boosting model  
- **TensorFlow / Keras** — LSTM time-series model  
- **Streamlit** — Interactive dashboard  

---

## 📊 Data Exploration Summary

### **Week 1 & Week 2**
Performed initial EDA:
- `data.head()`, `data.info()`, `data.describe()`
- Plotted **distributions** of numerical features  
- Created **heatmap** to understand correlations  
- Built **Linear Regression** & **Random Forest** models  
- Compared performance and extracted feature importances  

---

## 🚀 Week 3 Enhancements

### **🔍 Advanced EDA**
- Detailed **univariate & bivariate** analysis  
- Time-series line plots to identify energy trends  
- Correlation insights with engineered features  

### **🛠 Feature Engineering**
Added new time-based & rolling features:

- `hour`  
- `weekday`  
- `is_weekend`  
- Rolling means:  
  - `rolling_3h`  
  - `rolling_24h`  
- Lag features:  
  - `lag_1`  
  - `lag_24`  

### **🤖 Advanced Models**
- **XGBoost Regressor** for boosted tree predictions  
- **LSTM Neural Network** for time-series forecasting  

### **📊 Streamlit Dashboard**
A simple interactive dashboard to:
- Visualize energy trends  
- Display model predictions  
- Explore engineered features  

---

## 📁 Project Structure
```
week-1/
│── data/
│   ├── energy.csv
│   ├── energy_with_timestamp.csv
│   └── energy_features.csv
│
│── models/
│   ├── xgb_model.pkl
│   └── lstm_model.h5
│
│── notebooks/
│   ├── Energy_Prediction.ipynb
│   ├── week2_model_training.ipynb
│   └── week3_energy_final.ipynb
│
│── scripts/
│── app.py
│── requirements.txt
│── README.md
```

---

## 🏁 Final Notes
This project demonstrates how **energy consumption** can be predicted using environmental conditions.  
It shows the full process from **data cleaning → EDA → feature engineering → model training → evaluation → dashboard deployment**.

Future improvements could include:
- Hyperparameter tuning  
- Time-series cross-validation  
- Deploying the model with an API  

---

✨ **Author:** Jayashri S
🌟 *Energy Prediction — Machine Learning Analytics Project*

