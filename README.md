# **Maximum Temperature Forecasting in Surabaya (1981-2023) using ARIMA Algorithm**

📌 **Project Description**  
This project focuses on forecasting the maximum temperature in Surabaya from 1981 to 2023 using the ARIMA algorithm. The aim is to predict future temperature trends and provide valuable insights into climate patterns in Surabaya.
![image](https://github.com/user-attachments/assets/0b697ca6-4409-46a5-8a3d-ed9afe60eace)

📝 **Dataset**  
**Source**: Historical maximum temperature data of Surabaya (1981-2023).  
**Features**:  
- Date  
- Max Temperature (°C)

🔍 **Methodology**  
📌 **Data Collection**  
The dataset consists of historical maximum temperature records for Surabaya from 1981 to 2023.

📌 **Data Preprocessing**  
- Handling missing values
- Time series decomposition (Trend, Seasonality, Residuals)
- Stationarity testing using the Augmented Dickey-Fuller (ADF) test

📌 **Modeling with ARIMA**  
- Data split into training and testing sets
- Optimal parameters (p, d, q) determined through grid search
- ARIMA model fitting
- Temperature forecasting for future dates

📌 **Evaluation Metrics**  
- **Root Mean Squared Error (RMSE)**  
- **Mean Absolute Error (MAE)**  
- **Mean Absolute Percentage Error (MAPE)**  

📊 **Results**  
📌 **Visualization T-Max**  
![image](https://github.com/user-attachments/assets/f2327ede-671f-4ded-af5c-613dae8b889c)

📌 **Model Performance**  
![image](https://github.com/user-attachments/assets/b7d2dda7-50bc-4d4f-ab78-2b06ebc1e7a1)
ARIMA Model Evaluation:
Mean Absolute Error (MAE): 1.07
Root Mean Squared Error (RMSE): 1.50

### Compare Another Model
![image](https://github.com/user-attachments/assets/a5ba0c08-344a-42eb-bca7-c880d3a2e741)

💻 **Technologies Used**  
- **Python**: Pandas, NumPy, Matplotlib, Statsmodels  
- **Time Series Forecasting**: ARIMA  
- **Data Visualization**: Time series plots, error comparison charts


🔥 **Conclusion**  
This project demonstrates the use of the ARIMA model for time series forecasting to predict the maximum temperature in Surabaya. The forecasted results can be valuable for climate trend analysis, urban planning, agriculture, and other sectors that are sensitive to climate variations.
