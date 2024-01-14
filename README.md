# Forecasting-Walmart-Revenue
This project contains code and analysis for forecasting Walmart's quarterly revenue using time series analysis, regression models, and ARIMA models. The dataset spans from Q1 2005 to Q4 2022 and is sourced from MacroTrends. The project is organized into two case studies, each focusing on different aspects of the forecasting process.

In Case Study #2, the project begins with visualizing time series components and creating time series datasets in R. It then explores five regression models with data partitioning, covering linear and quadratic trends, seasonality, and combinations. The models are rigorously evaluated for statistical significance, goodness of fit, and forecasting accuracy using metrics like MAPE and RMSE. These foundational insights set the stage for more advanced modeling approaches.

Case Study #3 shifts the focus to AR and ARIMA models. It assesses the predictability of Walmart's revenue using AR(1) and first differencing. A two-level forecasting model is introduced, combining regression with AR models for residuals. ARIMA models, specifically ARIMA(1,1,1)(1,1,1) and Auto ARIMA, are applied and compared for accuracy. The final section comprehensively evaluates various forecasting models, including regression, two-level models, and ARIMA, to identify the most accurate model for predicting Walmart's revenue in the upcoming quarters.