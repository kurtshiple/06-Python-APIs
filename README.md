# Python-and-Weather-API
The purpose of this project was to utilize Python requests, APIs, and JSON traversals in order to analyze weather data. This involved writing a python script to visualize the weather of 500+ cities across the world of varying distance from the equator.

Scatter plots include

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

The final jupyter notebook randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude. It also performed a weather check on each of the cities using a series of successive API calls. It also included a print log of each city as it's being processed with the city number and city name. It also saved both a CSV of all data retrieved and png images for each scatter plot.
