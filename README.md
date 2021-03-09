# Python API - Experiment

## Background

Data's true power lies in its ability to answer questions definitively. Use Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?" The obvious answer is "It gets hotter..." but we want to **prove** it.

Note: If you would like to run the included Jupyter Notebook files, you will need to provide your own API keys for [OpenWeatherMap API](https://openweathermap.org/api) and [Google API](https://console.developers.google.com/).


## Part I - WeatherPy

* Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using [simple Python library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api)to create a representative model of weather across world cities.

* Create a series of scatter plots to showcase the following relationships:

** Temperature (F) vs. Latitude
** Humidity (%) vs. Latitude
** Cloudiness (%) vs. Latitude
** Wind Speed (mph) vs. Latitude

*Run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

** Northern Hemisphere - Temperature (F) vs. Latitude
** Southern Hemisphere - Temperature (F) vs. Latitude
** Northern Hemisphere - Humidity (%) vs. Latitude
** Southern Hemisphere - Humidity (%) vs. Latitude
** Northern Hemisphere - Cloudiness (%) vs. Latitude
** Southern Hemisphere - Cloudiness (%) vs. Latitude
** Northern Hemisphere - Wind Speed (mph) vs. Latitude
** Southern Hemisphere - Wind Speed (mph) vs. Latitude

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.

* Perform a weather check on each of the cities using a series of successive API calls.

* Include a print log of each city as it's being processed with the city number and city name.

* Save a CSV of all retrieved data and a PNG image for each scatter plot.

