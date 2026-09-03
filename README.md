# Forecasting with Hybrid Statistical-ML Models
•	Examined the cases of Schneider Electric stock, the EURO STOXX 50 index and the iShares Core DAX UCITS ETF from January 2008 to September 2025.\\
•	Split the data into two periods to evaluate model predictability under different market conditions.
•	Employed three main models: ARIMA, LSTM and XGBoost.
•	Implemented two types of hybridization: 
     1)	Residual Modeling: Fitting the stationary series with ARIMA and modeling the residuals with LSTM and XGBoost. 
     2)	Model Averaging: Averaging the predictions of LSTM and XGBoost.
•	Evaluated predictive performance using root mean squared error and mean absolute error metrics, as well as the Diebold-Mariano test.
•	Observed that different types of hybridization yielded superior results in both periods compared to standalone models.
