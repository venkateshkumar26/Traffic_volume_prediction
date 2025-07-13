# Traffic_volume_prediction
Created a simple Traffic volume prediction model using history and time based features with random forest regressor model during the internship from the company INNOVATE 
# 🚦 Traffic Volume Prediction using Real Data (Kaggle)

## 📌 Overview
This project uses a real-world dataset from the Metro Interstate Traffic Station to build a machine learning model for predicting hourly traffic volume based on time and weather features.

## 🔍 Dataset
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/ughaku/metro-interstate-traffic-volume)
- **Features Used**: 
  - Time (hour, weekday, weekend)
  - Weather (temperature, rain, snow, clouds)
- **Target**: `traffic_volume` (Number of vehicles)

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy**
- **Scikit-learn (RandomForestRegressor)**
- **Seaborn & Matplotlib for visualization**

## 📊 Results
- **MAE**: ~450
- **RMSE**: ~600
- Good performance for a basic regression setup

## 💡 Future Work
- Add categorical weather descriptions
- Try LSTM for time series modeling
- Deploy using Flask + AWS or Streamlit for dashboard

## 🧪 How to Run
1. Download dataset from Kaggle: `Metro_Interstate_Traffic_Volume.csv`
2. Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
