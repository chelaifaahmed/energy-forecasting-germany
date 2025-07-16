# Germany Energy Consumption Forecasting (2015–2025)

This project uses classical time series modeling (SARIMA) to forecast daily energy load in Germany for the year 2025. It includes data cleaning, stationarity tests, seasonal decomposition, residual diagnostics, and model tuning.

## 📊 Technologies
- Python (DataLab / Jupyter)
- pandas, statsmodels, scikit-learn
- SARIMA modeling
- Forecast evaluation: RMSE, MAE, MAPE

## ✅ Results
- Best model: SARIMA(1,0,0)(0,1,1,7)
- Test RMSE (2024): 20,698 MW
- MAPE: 8.34%

## 📁 Files
- `sarima_energy_forecast.ipynb` — full notebook
- `forecast_vs_actual_2024.csv` — test year output
- `forecast_2025.csv` — predicted values for 2025
- `sarima_model.pkl` — saved model object

## 📌 Author
Ahmed Chelaifa — [LinkedIn](https://www.linkedin.com/in/ahmed-chelaifa)
