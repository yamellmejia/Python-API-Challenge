# Python-API-Challenge

# Overview

WeatherPy and VacationPy are Python-based projects that analyze weather data to help users analyze the data of cities around the world. By leveraging data visualization libraries and the Geoapify API, the project identifies ideal travel destinations based on specific weather conditions and finds nearby hotels.

This project is divided into two main parts:

City Weather Data Analysis - Collected and visualized using Python libraries.

Vacation Destination Visualization - Displayed on a map with relevant details.

# Technologies Used

Python

Pandas

HvPlot

Geoapify API

Jupyter Notebook


# Installation

Clone this repository:

git clone <git@github.com:yamellmejia/Python-API-Challenge.git>

Install the required Python packages:

pip install pandas hvplot requests

Obtain a Geoapify API key by signing up at Geoapify.

Add your API key to the VacationPy.ipynb file.


# Features

Humidity Map: Displays a scatter plot of cities with point size based on humidity.

Weather Filtering: Users can filter cities based on temperature, wind speed, and cloudiness.

Hotel Search: Finds nearby hotels for each ideal destination using the Geoapify API.

Interactive Map: Hover over points to view city names, countries, humidity, and hotel names.

Example Criteria for Ideal Cities

Max temperature between 21°C and 27°C

Wind speed less than 4.5 m/s

Clear skies (0% cloudiness)

# Notes

If no hotel is found within the search radius, the output will display "No hotel found."

Ensure that you don't exceed the Geoapify API request limit.

