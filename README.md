# Electricity Demand Forecasting

## 🏢 Business Context

A major electricity distribution company aimed to improve the efficiency of its production and procurement processes by forecasting electricity demand. Accurate demand forecasting helps the company plan for energy supply, optimize resource allocation, and minimize costs.

## 📊 Summary

This project involved analyzing **monthly electricity consumption data** to forecast future demand. Several models were tested, including **ARIMA**, **SARIMAX**, and **ETS** (Error, Trend, and Seasonality). After applying data cleaning, first-order differencing, and seasonal decomposition techniques, the **ETS model** emerged as the most accurate, achieving the lowest **RMSE** of **6.91** and became the preferred forecasting model.

## 🛠 Tools

- **Pandas**: Used for data manipulation and preparation.
- **Matplotlib & Seaborn**: Used for visualizing trends, seasonality, and model performance.
- **Statsmodels**: Implemented stationarity tests (ADF), ARIMA, SARIMAX, and ETS models.
- **Scikit-learn**: Used for evaluating model performance using RMSE.

## 🔧 Techniques

- **Data Cleaning**: Removed any outliers and filled missing values to ensure the dataset was consistent.
- **Stationarity Testing (ADF Test)**: Performed the **Augmented Dickey-Fuller** test to assess the stationarity of the data.
- **Differencing**: Applied first-order differencing to make the data stationary.
- **Seasonal Decomposition**: Decomposed the time series data into its trend, seasonal, and residual components.
- **ARIMA & SARIMAX Models**: Implemented ARIMA and SARIMAX models to capture patterns in the time series.
- **ETS Forecasting**: Applied the **ETS model** to capture error, trend, and seasonality for more accurate forecasting.
- **RMSE Evaluation**: Used **RMSE (Root Mean Squared Error)** to evaluate model accuracy and select the best-performing model.

## 📈 Results

The **ETS model** outperformed both ARIMA and SARIMAX, with the lowest **RMSE** of **6.91**, making it the preferred model for forecasting electricity demand.

## 🛠 Installation

To run this project, you need the following libraries:

pip install pandas matplotlib seaborn statsmodels scikit-learn

🏃‍♂️ Usage
Clone the repository:

```
git clone https://github.com/faizanasadkarim/electrcity-demand-prediction.git
```

Navigate to the project directory:


cd electrcity-demand-prediction
Run the analysis:

python 13.py

This will load the dataset, perform the necessary preprocessing, apply the forecasting models, and display the results.

## 🎯 Conclusion
By using statistical forecasting models, this project provided a more accurate prediction of electricity demand, enabling better planning and optimization for the electricity distribution company.
