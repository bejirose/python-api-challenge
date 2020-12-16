# Part I: Weather Analysis using Python

- Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, used a simple Python library, the OpenWeatherMap API, and created a representative model of weather across world cities.
- Randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude.
- Performed a weather check on each of the cities using a series of successive API calls.
- Includeed a print log of each city as it's being processed with the city number and city name.
- Saved a CSV of all retrieved data and a PNG image for each scatter plot.

## Plots
### Created the following scatter plots to showcase the relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

## Linear Regression

### Run linear regression on each relationship listed below, separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

### Data Analysis
- Each pair of plots is analyzed and a short description is added to explain the relationships 
- Created multiple linear regression plots and analyzed the realationships


# Part II - VacationPy

- Used jupyter-gmaps and the Google Places API to analyze the weather data to plan future vacations.
- Created a heat map that displays the humidity for every city from the part I of the homework.
  
- Narrowed down the DataFrame to find ideal weather condition using crriteria such as:
  - A max temperature lower than 80 degrees but higher than 70,
  - Wind speed less than 10 mph, and
  - Zero cloudiness.

  
