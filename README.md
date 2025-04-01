# AI with atmosphere 

Final project for the Building AI course

## Summary

**AtmoAI** is a machine learning project that aims to detect anomalies in atmospheric data and improve the short-term prediction of key variables such as air pollutants, temperature, and humidity. By combining traditional environmental monitoring with AI techniques, the project enhances our ability to understand, forecast, and respond to rapid changes in the atmosphere, such as pollution spikes or sudden weather shifts. This system has potential applications in air quality alerts, climate research, and urban environmental planning.

## 💡 Project Idea

Atmospheric scientists use both measurement data and numerical models to monitor the state of the atmosphere. However, unexpected events like wildfire smoke, pollution from shipping, or sudden aerosol changes can be missed or misrepresented by conventional models.

AtmoAI addresses this problem by:
- Detecting abnormal atmospheric behavior using machine learning
- Improving forecasts for pollutants like PM2.5 and NO₂
- Reducing reliance on heavy numerical modeling where possible

## 🎯 Problem Statement

Can we use machine learning to identify and forecast atmospheric anomalies in a fast, flexible, and accurate way, using measurement and model data?

## 🧠 AI Approach

### Input Data
- Ground-based: PM2.5, O₃, NO₂, SO₂, humidity, temperature
- Satellite: Aerosol Optical Depth (AOD), cloud cover
- Meteorology: wind speed, pressure, precipitation
- Model output: from SILAM, ECMWF, or Copernicus atmospheric datasets

### ML Techniques
- **Unsupervised learning**: anomaly detection via clustering or autoencoders
- **Time series prediction**: LSTMs, GRUs, Prophet
- **Supervised regression**: for pollutant level forecasting
- **Hybrid models**: correcting physics-based outputs with ML predictions

## 🧪 Key Features
- Identify pollution or meteorological anomalies
- Predict pollutant concentrations 1–48 hours in advance
- Interactive visualization of air quality indicators
- Trigger warnings for unhealthy air or rapid changes

## 🛠 Tech Stack
- Python: NumPy, Pandas, Scikit-learn, TensorFlow/PyTorch
- Atmospheric data tools: NetCDF4, xarray, HDF5
- Visualization: Matplotlib, Plotly, Cartopy
- Interface: Streamlit or Dash

## ✅ Evaluation Metrics
- RMSE / MAE for forecast accuracy
- Precision & recall for anomaly detection
- Spatial accuracy of predicted pollution fields

## 🚀 Future Extensions
- Apply to Arctic aerosol observations or Finnish urban air quality
- Integrate with low-cost sensor networks (e.g., PurpleAir)
- Use CNNs for satellite image-based prediction
- Collaborate with atmospheric models for hybrid workflows

## 👨‍🔬 Why This Project?

As a Master's student in atmospheric science, I'm passionate about integrating AI tools into environmental research. This project blends real-world relevance (air quality, health, climate) with technical innovation and serves as a stepping stone toward smarter environmental monitoring systems.

