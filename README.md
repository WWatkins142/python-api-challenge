# Python-API-challenge
### What's the Weather Like?
 
 ## WeatherPy
 
Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 
This project utilizes a simple Python library and the OpenWeatherMap API to create a representative model of weather across world cities.
Scatter plots are created to show thee following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Linear regression is then run on each relationship with separate plots for the Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

## VacationPy
The second part of this project uses jupyter-gmaps and the Google Places API to work with weather data to plan future vacations. 
1. Created a heat map that displays the humidity for every city from WeatherPy (Part 1).
2. Narrowwd down the DataFrame with your ideal weather condition.
3. Used Google Places API to find the first hotel for each city located within 5000 meters of the ideal vacation destination coordinates.
4. Placed the hotels on top of the humidity heatmap with a pin containing the Hotel Name, City, and Country.
