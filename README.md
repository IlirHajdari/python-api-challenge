# Python APIs Homework: WeatherPy and VacationPy.

## NOTE ##
The starter code for this assignment was provided by the course/class, which is why I did not rename the folders and continued on from where the course left off on provided the projects starter code. 

## Description
This python-api-challenge project in divided into two parts: WeatherPy and VacationPy. The project analyzes weather data from over 500 cities worldwide and visualizes various weather patterns to gain some insight in the interested locations. 


## Summary

### Part 1: WeatherPy
WeatherPy explores weather trend across the Northern and Southern Hemisphere by analyzing the relationship between weather variables such as temperature, humidity, cloudiness, and wind speed. Using the OpeanWeatherMap API, random geographic coordinates are generated to build a dataset of cities with corresponding weather data. 

Key deliverables include:
- Scatter Plots to showcase the relationship between latitude and weather variables:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs Cloudiness
- Latitude vs. Wind Speed
- Linear regression analysis for the above variables, separated by hemisphere:
- Northern Hemisphere vs. Southern Hemispheree


### Part 2: VacationPy
VacationPy focuses on planning for a vacation based on weather data. Using the Geoapify API and the geoViews Python Library, a map is generated to visualize city locations that meet specific weather criteria. For each city, nearby hotels are then located and generated on the map. 

Key deliverables include:
- A map displaying all cities, with point sizes corresponding to humidity levels
- The ability to filter cities based on specific weather conditions
- Max Temperature: 21-27C
- Wind speed < 4.5 m/s
- Zero Cloudiness
- A map that shows city names, country, humidity levels, and nearby hotels via a hover effect

## Requirements

### Tools and Libraries

**APIs:**
- OpenWeatherMap API
- Geoapify API

**Python Libraries:**
- Pandas
- Matplotlib
- Scipy
- Numpy
- Requests
- Json
- GeoViews


## Contact Information

For questions or additional information, reach out to me at:
-Email: ilir.hajdari111@gmail.com