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
| CO2 | Carbon dioxide concentration (ppm) |
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

🧠 Model Training & Evaluation (Week 2)

For Week 2, the focus was on training and testing predictive models using the prepared dataset.

🔹 Steps Performed:

Loaded the dataset (energy.csv) into a Pandas DataFrame.

Split data into training (80%) and testing (20%) sets using train_test_split.

Trained a Linear Regression model to predict EnergyConsumption.

Evaluated performance using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score (Accuracy)

Compared actual vs. predicted values for validation.

📈 Sample Output:
Mean Absolute Error: 2.45
Mean Squared Error: 8.76
R² Score: 0.92

📊 Visualization Ideas (optional):

You can visualize results by plotting:

plt.scatter(y_test, y_pred)
plt.xlabel("Actual Energy Consumption")
plt.ylabel("Predicted Energy Consumption")
plt.title("Actual vs Predicted Energy Usage")
plt.show()

