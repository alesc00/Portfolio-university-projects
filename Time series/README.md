# 🚲 London Bike Sharing Time Series Analysis

This project performs a comprehensive time series analysis of the **London bike sharing dataset**, which records the hourly bike-sharing counts in London over two years (2015–2017). The goal is to understand the trends, seasonality, and patterns in the data and to develop predictive models using time series forecasting techniques.

## 📁 Project Contents

- **TimeSeriesProject.Rmd**: The R Markdown file containing the complete analysis, including data preprocessing, exploration, and forecasting models.
- **data/**: Contains the dataset used for the analysis.
- **docs/**: Includes the project documentation in PDF format, explaining the project objectives, methodology, and findings.

## 📊 Summary

### Dataset:
- **London Bike Sharing Dataset**: Hourly data from January 4th, 2015, to January 3rd, 2017, with various covariates like temperature, weather, and wind speed.
  
### Goal:
To analyze the bike-sharing patterns in London and build a time series model to predict future bike-sharing counts.

### 📈 Key Analyses:
- **Data Loading and Exploration**: Initial loading of the dataset and exploratory analysis to understand the trends and seasonal patterns in bike-sharing behavior.
- **Data Preprocessing**: Cleaning the data, handling missing values, and preparing it for time series modeling.
- **Time Series Modeling**: Developing forecasting models using techniques like ARIMA and Exponential Smoothing to predict bike-sharing counts.
- **Model Evaluation**: The models are evaluated using RMSE, MAE, and other forecasting accuracy metrics.

## 🛠️ Libraries Used:
- **forecast**: For time series forecasting models.
- **tseries**: For time series analysis functions.
- **kableExtra**: For enhanced table formatting in the output report.

## 📌 Conclusions:
This project successfully demonstrates the application of time series analysis techniques to forecast bike-sharing patterns in London. The models provide insights into the seasonal trends and contribute to accurate forecasting for future demand prediction.

⚠️ **Note**: The dataset is included in the `data/` folder, and detailed project documentation can be found in the `docs/` folder.
