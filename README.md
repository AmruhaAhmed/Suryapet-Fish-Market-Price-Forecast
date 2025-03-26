
# Suryapet Fish Market Price Forecasting

This project aims to forecast the fish prices sold in Suryapet Fish Market, Telangana, India with an overall Root Mean Squared Error (RMSE) of 21.84. The data has been collected manually from FMPIS website , spanning  1st January 2024 to 7th March, 2025. 5 popular fish species have been considered for the forecasting:
1. Mrigal
2. Common Carp
3. Tilapia
4. Catla
5. Rohu
   
These fish species are considered in the following sizes:

1. small
2. medium
3. large

## 🛠 Skills
1. Python
2. Data Science
3. Data Analysis

## Forecasting

The project uses the Vector Autoregression (VAR) model from the statsmodels library for time series forecasting. The VAR model is particularly suitable for multivariate time series data where multiple time-dependent variables influence each other.
## Key Steps

#### Data Cleaning :

Converting the "Date" column into dd-mm-yyyy format and setting "Date" as index. The null values are dealth with using forward fill.

#### Feature Engineering:

New columns are created by applying square root to the existing columns.

#### Stationarity Check:

The Augmented Dickey-Fuller (ADF) test is used to check for stationarity in the time series data. The features are selected based on their p-value. 

#### Model Development:

Implemented a Vector Autoregression (VAR) model using Python's statsmodels library to forecast future prices based on historical data. 80% of the data i.e. 345 rows are reserved for training and 20% of the data i.e. 87 rows are reserved for testing. 

#### Model Evaluation: 

Evaluated the model's performance using  Root Mean Squared Error (RMSE) metric.

#### Data Visualization:

Developed a function to visualize the historical prices and the prices forecasted by the VAR model.




## Screenshots
![image](https://github.com/user-attachments/assets/cef58ac5-1bcc-4f92-a326-cce407812cdd)
![image](https://github.com/user-attachments/assets/2ce8efa2-a75f-4250-97fd-b8453f16d091)




