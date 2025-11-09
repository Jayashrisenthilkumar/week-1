# ⚡ Energy Consumption Prediction

## 📘 Project Overview
This project focuses on predicting **energy consumption** based on environmental factors such as temperature, humidity, light, and CO₂ levels.  
The goal is to use **data science and machine learning** techniques to develop a predictive model that estimates energy usage efficiently.

---

## 🎯 Objectives
- Analyze and visualize energy-related data.
- Build a **Linear Regression** model to predict energy consumption.
- Compare performance with a **Random Forest Regressor**.
- Identify the most influential features affecting energy usage.

---

## 🧩 Dataset Information
The dataset used is stored in `data/energy.csv`.

| Feature | Description |
|----------|--------------|
| Temperature | Room temperature in °C |
| Humidity | Relative humidity in % |
| Light | Light intensity (Lux) |
| CO₂ | Carbon dioxide concentration (ppm) |
| HumidityRatio | Ratio of humidity to temperature |
| EnergyConsumption | Energy consumed (kWh) |

---

## ⚙️ Technologies Used
- **Python 3**
- **Pandas**, **NumPy** — Data handling  
- **Matplotlib**, **Seaborn** — Data visualization  
- **Scikit-learn** — Machine learning models

---

## 📊 Data Exploration
Key commands used:
```python
data.head()
data.info()
data.describe()
sns.heatmap(data.corr(), annot=True, cmap='coolwarm')
