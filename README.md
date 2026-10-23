# PM₂.₅ Prediction in DKI Jakarta Using Statistical and Machine Learning Approaches 

## 1. Project Overview

Air pollution is a major environmental concern that affects public health, particularly in urban areas. This project focuses on predicting hourly PM2.5 concentrations in DKI Jakarta, Indonesia, using statistical and machine learning methods.

The study combines air quality and meteorological data from five monitoring stations to analyze PM2.5 concentration patterns and compare the prediction performance of three approaches: ARIMAX, Support Vector Regression (SVR), and Hybrid ARIMAX–SVR.

## 2. Objectives

- Develop and compare ARIMAX, SVR, and Hybrid ARIMAX–SVR models for PM2.5 prediction.
- Analyze hourly PM2.5 concentration patterns across five monitoring stations in DKI Jakarta.
- Evaluate model performance using MAE, RMSE, and R².
- Identify the best-performing model based on prediction accuracy.

## 3. Dataset

### Study Area and Period

The dataset consists of hourly observations collected from five air quality monitoring stations in DKI Jakarta, Indonesia.

- **Study Period:** January 1, 2019 – December 31, 2022
- **Temporal Resolution:** Hourly
- **Study Area:** DKI Jakarta, Indonesia
- **Target Variable:** PM2.5 concentration (µg/m³)

### Air Quality Data

Air quality data were obtained from the DKI Jakarta Environmental Agency (Dinas Lingkungan Hidup DKI Jakarta).

The pollutant variables include:

- PM2.5
- PM10
- SO2
- CO
- O3
- NO2

### Meteorological Data

Meteorological data were obtained from ERA5, a global atmospheric reanalysis dataset.

The meteorological variables include:

- **Air Temperature (°C)**
- **Dew Point Temperature (°C)**
- **Solar Radiation (W/m²)**
- **Rainfall (mm)**
- **Relative Humidity (%)**
- **Wind Speed (m/s)**

These variables provide additional information about weather conditions that may influence PM2.5 concentrations.

### Monitoring Stations

The study covers five monitoring stations in DKI Jakarta:

1. DKI1 – Bundaran HI
2. DKI2 – Kelapa Gading
3. DKI3 – Jagakarsa
4. DKI4 – Lubang Buaya
5. DKI5 - Kebon Jeruk

## 4. Project Workflow

The project consists of the following stages:

1. **Data Preparation**
   - Data collection
   - Data understanding

2. **Data Preprocessing**
   - Data cleaning
   - Missing value handling
   - Data transformation
   - Exploratory Data Analysis (EDA)

3. **Data Modeling**
   - ARIMAX
   - Support Vector Regression (SVR)
   - Hybrid ARIMAX–SVR

4. **Model Evaluation**
   - Train-test split
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - Coefficient of Determination (R²)

5. **Conclusion**
   - Compare model prediction results
   - Identify the best-performing model

## 5. Models Used

| Model | Description |
|---|---|
| ARIMAX | A statistical time-series model that incorporates external variables. |
| SVR | A machine learning algorithm used for regression and numerical prediction. |
| Hybrid ARIMAX–SVR | A hybrid approach combining statistical time-series modeling and machine learning. |

## 6. Evaluation Metrics

Three evaluation metrics are used to assess prediction performance:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
- **RMSE (Root Mean Squared Error):** Measures prediction errors while penalizing larger errors more heavily.
- **R² (Coefficient of Determination):** Measures how well the model explains the variation in observed PM2.5 concentrations.

Lower MAE and RMSE values generally indicate better prediction accuracy, while an R² value closer to 1 indicates a better fit.

## 7. Results and Conclusion

The prediction performance of ARIMAX, SVR, and Hybrid ARIMAX–SVR is compared across the five monitoring stations.

Based on the results presented in this project, the Hybrid ARIMAX–SVR model achieved the best overall prediction performance across the five monitoring stations in DKI Jakarta.

The findings demonstrate the potential of combining statistical time-series methods and machine learning to model hourly PM2.5 concentrations.

## 8. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Google Colab / Jupyter Notebook


