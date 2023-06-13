# Python-API-challenge
This repository contains the Python API Challenge project, which explores the relationship between weather variables and latitude. Utilizing Python requests, APIs, and JSON traversals, the project analyzes weather data from over 500 cities located at varying distances from the equator.

## Background
The project's goal is to answer the question, "What is the weather like as we approach the equator?" By leveraging data analysis techniques, the project aims to provide concrete evidence to support the relationship between weather and proximity to the equator.

## Project Structure
The project is divided into two main parts: WeatherPy and VacationPy.

### WeatherPy
In the WeatherPy part, a Python script is developed to visualize the weather conditions of cities worldwide. The citipy Python library and the OpenWeatherMap API are utilized to generate a representative model of weather patterns. The analysis involves creating scatter plots and performing linear regression to explore the correlation between weather variables and latitude.

### VacationPy
In the VacationPy part, the weather data obtained in WeatherPy is used to plan future vacations. Using Jupyter notebooks, the geoViews Python library, and the Geoapify API, the project creates map visualizations. By narrowing down cities based on specific weather conditions, suitable hotels near the desired destinations are identified.