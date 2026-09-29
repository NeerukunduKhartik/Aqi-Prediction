# 🌫️ Smart AQI Intelligence Dashboard


A **production-ready Machine Learning web application** that monitors, analyzes, and predicts Air Quality Index (AQI) using real-world pollution data.

Designed with a focus on **data-driven insights, user experience, and scalability**, this project demonstrates end-to-end ML system development — from data preprocessing to deployment-ready UI.

---

## ✨ Key Features

* 📊 **Interactive Dashboard**
  Visualize AQI trends across countries and cities using dynamic charts.

* 🤖 **ML-Based AQI Prediction**
  Predict AQI using a trained Random Forest model based on pollutant levels.

* 🔍 **Advanced Filtering System**
  Filter data by country and city for localized insights.

* 📈 **Trend & Correlation Analysis**
  Understand relationships between pollutants like CO, NO₂, Ozone, and PM2.5.

* 🔔 **Smart Alert System**
  Notify users when AQI exceeds safe thresholds.

---

## 🧠 Machine Learning Details

* **Model:** Random Forest Regressor

* **Features Used:**

  * CO AQI Value
  * Ozone AQI Value
  * NO₂ AQI Value
  * PM2.5 AQI Value

* **Target:**

  * AQI Value

* **Evaluation Metrics:**

  * Mean Absolute Error (MAE)
  * R² Score

---

## 🛠 Tech Stack

| Category      | Tools Used    |
| ------------- | ------------- |
| Frontend      | Streamlit     |
| Backend       | Python        |
| ML Framework  | Scikit-learn  |
| Data Handling | Pandas, NumPy |
| Visualization | Plotly        |
| Model Storage | Joblib        |

---

## 📁 Project Structure

```
AQI Project/
│── app.py
│── requirements.txt
│── README.md
│── data/
│   └── global_air_pollution.csv
│── aqi_model.pkl (generated)
```

## 📊 Dataset

* Source: Kaggle – Global Air Pollution Dataset
* Contains AQI data across multiple countries and cities
* Note: PM10 is not included in the dataset

---

## 🎯 Future Improvements

* 🌍 Real-time AQI API integration
* 🗺️ Map-based AQI visualization
* 📱 Mobile-responsive UI
* 🔐 User authentication system
* ☁️ Cloud deployment (Streamlit / AWS / Vercel)