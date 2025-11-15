# ⚡ Energy Consumption Prediction

## 📘 Project Overview
This project focuses on predicting energy consumption based on environmental factors such as temperature, humidity, light, and CO₂ levels.  
The goal is to use data science and machine learning techniques to develop a predictive model that estimates energy usage efficiently.

---

## 🎯 Objectives
- Analyze and visualize energy-related data.  
- Build a **Linear Regression** model to predict energy consumption.  
- Compare performance with a **Random Forest Regressor**.  
- Identify the most influential features affecting energy usage.  
- Perform **advanced EDA**, feature engineering, and test **XGBoost** & **LSTM** models (Week 3).  
- Develop a **Streamlit dashboard** for interactive visualization (Week 3).

---

## 🧩 Dataset Information
The dataset is stored in `data/energy.csv`.  

| Feature | Description |
|---------|-------------|
| Temperature | Room temperature in °C |
| Humidity | Relative humidity in % |
| Light | Light intensity (Lux) |
| CO₂ | Carbon dioxide concentration (ppm) |
| HumidityRatio | Ratio of humidity to temperature |
| EnergyConsumption | Energy consumed (kWh) |

---

## ⚙️ Technologies Used
- **Python 3**  
- **Pandas, NumPy** — Data handling  
- **Matplotlib, Seaborn** — Data visualization  
- **Scikit-learn** — Machine learning models  
- **XGBoost** — Advanced tree-based model  
- **TensorFlow / Keras** — LSTM for time-series prediction  
- **Streamlit** — Interactive dashboard  

---

## 📊 Data Exploration

### Week 1 & 2
Key commands used for initial EDA:

```python
data.head()
data.info()
data.describe()
sns.heatmap(data.corr(), annot=True, cmap='coolwarm')

*Visualized distributions of numerical features

*Plotted correlation heatmaps

*Built Linear Regression and Random Forest models

Week 3 Additions...

Detailed univariate and bivariate analysis

Time-series plots to understand energy trends

Feature engineering:

hour

weekday

is_weekend

Rolling averages (rolling_3h_mean, rolling_24h_mean)

Lag features (lag_1, lag_24)

Advanced models: XGBoost and LSTM for improved predictions

Interactive Streamlit dashboard to visualize trends and predictions
