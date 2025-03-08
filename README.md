# Weather-prediction
This project aims to predict the chance of rain based on weather data such as temperature, humidity, and wind speed. The weather data is retrieved from an API for the past 30 days for several cities in Israel. The data is then cleaned by removing outliers, and a Random Forest regression model is trained to predict the rain chance.

Features:
Fetch historical weather data from the WeatherAPI API for multiple cities.
Clean and preprocess data by removing outliers.
Visualize relationships between different weather features (Temperature, Humidity, Wind Speed, and Rain Chance).
Train a Random Forest regression model to predict the chance of rain.
Evaluate the model's performance using Mean Absolute Error (MAE).

How to Use:
1.Clone this repository to your local machine: git clone https://github.com/yuval036/Weather-prediction.git
2.Replace the api_key variable in the code with your API key from WeatherAPI.
3.Run the code in the Jupyter notebook (or script).
   The script will fetch weather data for the last 30 days for the cities: Tel Aviv, Haifa, Jerusalem, Eilat, and Beersheba.
   It will clean the data, remove outliers, and visualize relationships between weather features.
   The script will then train a Random Forest model to predict the rain chance and output the Mean Absolute Error (MAE).
   The cleaned data will be saved as weather_data.csv.
