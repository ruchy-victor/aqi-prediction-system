# 🌍 AQI Prediction & Spatial Visualization System

## 📌 Overview
This project predicts **Air Quality Index (AQI)** using **Machine Learning (XGBoost)** and visualizes pollution levels using **spatial heatmaps**. It follows a **data-centric approach** by improving data quality, integrating multiple data sources, and generating both **current and future AQI predictions**.

Developed as part of **TNSDC Naan Mudhalvan AI/ML Hackathon**.

---

## 🚀 Features
- **AQI prediction** using XGBoost  
- **Multi-source data integration** (AQI + Weather)  
- **Current & Future AQI heatmaps**  
- **Spatial approximation (IDW-inspired)**  
- **AQI risk level classification**  
- **Model evaluation (MAE, RMSE, R²)**  

---

## 🧠 Tech Stack
- **Python**  
- **Pandas, NumPy**  
- **XGBoost**  
- **Scikit-learn**  
- **Folium (Heatmaps)**  

---

## 📊 Workflow
**Data → Preprocessing → Feature Engineering → Model Training → AQI Prediction → Spatial Mapping → Visualization → Risk Classification**

---

## 🔗 Colab Notebook
Run the full project here:  
👉 https://colab.research.google.com/drive/1UkYuaGWqxEIB0C8DYvcp1N9WvnQII3fB?usp=sharing  

---

## 📂 Datasets

**1. AQI Dataset (India Air Quality Data)**  
https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india  

**2. Weather Dataset (Daily Climate Data)**  
https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data  

📌 **Note:**  
Download the datasets from the above links and **upload them in Colab** before running the notebook.

---

## ▶️ How to Run
1. Open the **Colab Notebook** (link above)  
2. Click **Runtime → Run All**  
3. Upload datasets when prompted  
4. View outputs including **predictions and heatmaps**  

---

## 📍 Spatial Note
This project uses **simulated spatial sampling** to approximate **street-level AQI variation** due to lack of real sensor coordinates. In real-world deployment, **true geospatial methods (IDW/Kriging)** and **live sensor data** will be used.

---

## 📈 Output
- **Predicted AQI values**  
- **Current AQI Heatmap**  
- **Future AQI Heatmap**  
- **AQI Risk Classification** (Good, Moderate, Poor, etc.)  
- **Performance Metrics** (MAE, RMSE, R²)  

---

## 📌 Project Status
**Final AQI Prediction System with Spatial Visualization** successfully developed as a working prototype.

---

## 📌 Future Improvements
- **Real-time AQI data integration (IoT sensors)**  
- **Advanced spatial interpolation (IDW/Kriging)**  
- **Time-series forecasting (LSTM/ARIMA)**  
- **Deployment as web application/dashboard**  

---

## 👥 Team
Hackathon Project – **5ManArmy**
