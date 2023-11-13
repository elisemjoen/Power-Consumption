# Power-Consumption

## Data set

The data set comprises four key columns: Time, representing hours in Coordinated Universal Time (UTC); Location, denoting the largest city within the relevant price area and serving as a representative sample of the area’s weather; Consumption, indicating the average hourly energy consumption measured in megawatts (MW); and Temperature, offering the weather forecast for the specified location at the respective hour, expressed in degrees Celsius.


## Data analysis

"ANEO_data_analysis" is designed to perform data analysis on power consumption data, considering various factors such as time, location, and temperature. The primary goal is to gain insights into patterns and trends related to power usage.

## Power forecasting

"ANEO_forecast" is a LSTM-model that forecasts power consumption based on a time series with temperature and location. Power consumption from the last five days is unknown, but the weather data is available at the time of the forecasting. 
