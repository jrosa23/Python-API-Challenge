# Python-API-Challenge
# Vacation Planning with Weather and Hotel Data

This project helps in planning vacations by utilizing weather data and finding nearby hotels using the Geoapify API. 
The goal is to:
1. Visualize cities with their weather data (humidity, temperature, etc.) on an interactive map.
2. Filter cities based on ideal weather conditions (e.g., temperature, wind speed, and cloudiness).
3. Use the Geoapify API to find hotels near selected cities.

## Project Overview

The project includes the following steps:
1. **Weather Data**: Cities' weather data is fetched, cleaned, and visualized on a map with points sized by humidity.
2. **Ideal Weather Filtering**: Cities are filtered based on specific weather conditions like temperature, wind speed, and cloudiness.
3. **Hotel Search**: For each selected city, a nearby hotel is searched using the Geoapify API and displayed on the map.

## Technologies Used
- Python
- Pandas
- `hvplot` for interactive map visualizations
- Geoapify API for hotel search
- Open Weather API for weather data

## Prerequisites
Before running the project, you need to install the following dependencies:
- latest/our version of Python: Python 3.12.4
- pandas
- requests
- hvplot
- geoapify API key
- openweather API key
