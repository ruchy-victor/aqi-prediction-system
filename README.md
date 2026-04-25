# 🌍 AQI Prediction & Spatial Visualization System

## 📌 Overview
This project predicts Air Quality Index (AQI) using Machine Learning and visualizes pollution levels using spatial heatmaps.

## 🚀 Features
- AQI prediction using XGBoost
- Multi-source data (AQI + Weather)
- Current & Future AQI heatmaps
- Spatial approximation (IDW-inspired)
- Risk level classification
- Model evaluation (MAE, RMSE)

## 🧠 Tech Stack
- Python
- Pandas, NumPy
- XGBoost
- Folium (Heatmaps)
- Scikit-learn

## 📊 Workflow
Data → Preprocessing → Model → Prediction → Spatial Mapping → Visualization → Risk Output

## 📍 Spatial Note
This project uses simulated spatial sampling to approximate street-level AQI.
In real-world deployment, real sensor data and true IDW/Kriging will be used.

## ▶️ How to Run
1. Open the notebook in Google Colab
2. Click **Runtime → Run All**
3. Upload dataset (or auto-download will work)

## 📈 Output
- AQI Predictions
- Heatmaps (Current & Future)
- Risk Classification
- Performance Metrics

## 📌 Future Improvements
- Real-time sensor integration
- True geospatial interpolation
- Time-series forecasting

## 👥 Team
Hackathon Project
