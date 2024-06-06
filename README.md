# openweather_ETL
I've been working on an ETL (Extract, Transform, Load) data pipeline project to fetch and store weather data from the OpenWeatherMap API using Python. 🌤️

# Project Overview
In this project, I built a robust ETL pipeline that:

# Extracts weather data for a given city from the OpenWeatherMap API.
Transforms the data to extract relevant fields such as city name, temperature, and weather description.
Loads the transformed data into a CSV file for further analysis.

# Python Libraries Used:
requests for making API calls.
pandas for data manipulation and storage.
dotenv for managing API keys securely.

# Workflow:
Extract: Fetch data from OpenWeatherMap API.
Transform: Parse the JSON response to extract required fields.
Load: Save the transformed data into a CSV file using Pandas.
