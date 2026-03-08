# 🌍 AQI Intelligence System

A machine learning project that predicts **Air Quality Index (AQI)** using environmental pollutant data and provides an **interactive dashboard** built with Streamlit.

This project demonstrates how machine learning can be applied to analyze pollution data and estimate AQI levels based on pollutant concentrations.

---

## 🚀 Features

* Data cleaning and preprocessing
* Feature engineering for pollution indicators
* Machine learning model using **XGBoost**
* Model evaluation with R² and RMSE metrics
* Explainable AI using **SHAP**
* Interactive **Streamlit dashboard** for AQI prediction
* Visualization of pollution patterns

---

## 📊 Dataset

The project uses an air pollution dataset containing measurements of pollutants such as:

* PM2.5
* PM10
* NO
* NO2
* NOx
* NH3
* CO
* SO2
* O3
* Benzene
* Toluene
* Xylene

These values are used to predict the **Air Quality Index (AQI)**.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* SHAP
* Streamlit
* Plotly
* Matplotlib / Seaborn

---

## 🧠 Machine Learning Model

The model is trained using **XGBoost regression** with feature engineering and hyperparameter tuning.

Evaluation metrics used:

* R² Score
* Root Mean Squared Error (RMSE)
* Cross Validation

---

## 📈 Feature Engineering

Additional features were created to improve model performance:

* PM ratio (PM2.5 / PM10)
* Total pollution index
* Average pollution level
* Seasonal features (month, day, season)

---

## 💻 Streamlit Dashboard

The project includes a **Streamlit web application** that allows users to:

* Input pollutant values
* Predict AQI levels
* View pollution indicators visually
* Display AQI category with color-coded gauge charts

---

## 📂 Project Structure

```
aqi-intelligence-system
│
├── app.py
├── aqi_model.pkl
├── scaler.pkl
├── feature_columns.pkl
├── city_day.csv
├── requirements.txt
└── final-pbl.ipynb
```

---

## ▶️ How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/aqi-intelligence-system.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the Streamlit app

```
streamlit run app.py
```

4. Open in browser

```
http://localhost:8501
```

---

## 📌 Future Improvements

* Real-time AQI data integration using APIs
* Deployment on cloud platforms
* Advanced model tuning
* Time-series AQI forecasting

---

## 👨‍💻 Author

B.Tech Electronics & Telecommunication Engineering Student
Interested in **Machine Learning, IoT, and Environmental Data Analysis**
