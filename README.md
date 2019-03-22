# Openweather Analysis

## What's the Weather Like As We Get Near The Equator?

"Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively."

Using Python requests, APIs (API wrappers), and JSON traversals I aimed to answer the fundamental question: "What's the weather like as we approach the equator?"

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.


## Process:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.

Then build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Saved both a CSV of all data retrieved and png images for each scatter plot.
