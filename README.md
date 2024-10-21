# Optimizing-Weather-Forecast-Accuracy-with-Machine-Learning


## Project Overview

The objective of this project is to predict temperature using historical weather data. The model utilizes various regression techniques to evaluate and compare their performance in forecasting temperature.

## Dataset

The dataset used in this analysis is named `Weather.csv`, which includes the following columns:

- `maxtempC`: Maximum temperature in Celsius
- `mintempC`: Minimum temperature in Celsius
- `tempC`: Current temperature in Celsius
- `cloudcover`: Percentage of cloud cover
- `humidity`: Percentage of humidity
- `sunHour`: Number of hours of sunlight
- `HeatIndexC`: Heat index in Celsius
- `precipMM`: Precipitation in millimeters
- `pressure`: Atmospheric pressure
- `windspeedKmph`: Wind speed in kilometers per hour
- `date_time`: Date and time of the recorded weather data

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


## Analysis

The analysis consists of the following steps:

1. **Data Preparation**:
   - Load and explore the dataset.
   - Handle missing values and visualize the data.

2. **Feature Selection**:
   - Identify relevant features for predicting temperature.

3. **Model Training**:
   - Split the data into training and testing sets.
   - Train three different regression models: Linear Regression, Decision Tree Regressor, and Random Forest Regressor.

4. **Model Evaluation**:
   - Calculate prediction errors using metrics such as Mean Absolute Error, Residual Sum of Squares, and R² Score.
   - Compare the performance of the different models.
