# CNN-LSTM Numerical Weather Prediction

## Overview
This project explores a hybrid deep learning approach for **Numerical Weather Prediction (NWP)**.  
The model combines **Convolutional Neural Networks (CNNs)** to capture spatial dependencies with **Long Short-Term Memory (LSTM)** networks to model temporal patterns.  
The goal is to improve the accuracy of short-term weather forecasts compared to traditional statistical or machine learning models.  

## Features
- Hybrid **CNN-LSTM architecture** for spatiotemporal forecasting  
- Works with multi-variable weather data (temperature, humidity, wind speed, pressure, etc.)  
- Preprocessing pipeline: cleaning, normalization, and sequence generation  
- Evaluation metrics: **RMSE, MAE, R²**  
- Modular design, easy to extend to new datasets  

## Methodology
1. **Data Collection** – Historical meteorological data (e.g., ERA5, ERA-Interim)  
2. **Preprocessing** – Time-series windowing, scaling, missing value handling  
3. **Model** – CNN for spatial feature extraction + LSTM for sequential learning  
4. **Training** – Early stopping, learning rate scheduling, dropout regularization  
5. **Evaluation** – Benchmarked against ARIMA and regression-based baselines  

## Results
- CNN-LSTM improved short-term forecasting accuracy over baseline models  
- Strong performance in predicting **temperature** and **precipitation trends**  
- Visualizations confirm predicted vs actual values align closely  

## Tech Stack
- Python 3.1  
- TensorFlow / Keras  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib, Seaborn  
- (Optional) Streamlit or Flask for web deployment  

## Future Work
- Add **attention mechanisms** for improved long-range sequence modeling  
- Incorporate **satellite imagery** for richer spatial features  
- Deploy a **cloud-based real-time dashboard** for operational use  

