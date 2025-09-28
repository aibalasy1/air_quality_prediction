# air_quality_prediction
The diploma project under the topic “Development of Machine Learning Models for
Air Quality Forecasting Based on Historical and Meteorological Data” was written by Guldana Shukerbek
Dana Damenova and Amir Abdykarimov, Dana Damenova and Amir Abdykarimov students of the Big Data
Analysis program at Astana IT University.

This study uses six main algorithms—Linear Regression, ElasticNet, Random Forest,
XGBoost, CNN, Bi-LSTM to predict the concentrations of five notable pollutants: PM2.5,
PM10, CO, NO and 2. Preprocessing included Fourier Transform to detect seasonality,
Granger causality to find lagging effects and using correlation analysis to pick important
variables. The performance of the models was checked with R², MAE, MAPE and
NSE. According to the results, random forest and XGBoost models did best for PM10,
surpassing the others in accuracy (R² = 0.61). Meanwhile, CO and PM2.5 showed a
lower level of variation in the data and sparse observations which led to a lower R² and
low ability to detect concentration levels precisely. NO and PM10 showed that the results
varied by location and were strongly dependent on nearby spatial patterns and seasonal
changes. This study demonstrates that targeted pollutant models and modern hybrid
deep learning methods are needed for accurate forecasting of air quality across space and
time. The approach creates an essential base for air quality prediction tools that can
adjust and scale, benefiting health, city planning and risk management in Kazakhstan.
**Keywords:** Air Quality Forecasting; Machine Learning; Deep Learning; CNN; BiLSTM; PM2.5; PM10; CO; NO; SO2; Time-Series Modeling; Random Forest; XGBoost.
