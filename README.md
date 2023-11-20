# Power-Consumption

## Dataset

The dataset comprises four key columns: Time, representing hours in Coordinated Universal Time (UTC); Location, denoting the largest city within the relevant price area and serving as a representative sample of the area’s weather; Consumption, indicating the average hourly energy consumption measured in megawatts (MW); and Temperature, offering the weather forecast for the specified location at the respective hour, expressed in degrees Celsius.


## Data analysis

"ANEO_data_analysis" and "aneo_stats" are designed to perform data analysis on power consumption data, considering various factors such as time, location, and temperature. The primary goal is to gain insights into patterns and trends related to power usage.

## Power consumption forecasting

"ANEO_forecasts" is a LSTM-model that forecasts power consumption based on a time series with temperature and location. Power consumption from the last five days is unknown, but the weather data is available at the time of the forecasting. 
