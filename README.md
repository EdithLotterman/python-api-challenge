# python-api-challenge 
## -------------------


## Project Description
### Relationships between max temps, humidity, cloudiness, and wind speeds are investigated using data from the CitiPy library and OpenWeather API. We then narrow down the cities into places to visit and use the Geoapify API to obtain the nearest hotel. This data is plotted on an hvplot.
## -------------------

## WeatherPy Notebook
### The code in this notebook selects cities based on a random number generator selecting latitude and longitude. Weather data is obtained for the cities from the OpenWeather API. Scatterplots for max temps, humidity, cloudiness, and wind speeads relative to latitudes are created to investigate possible relationships. We separated the cities into the northern and southern hemispheres and ran linear regressions on these same variables to further investodate potential relationships. The code outputs a csv file that is used by the VacationPy notebook
## -------------------

## VacationPy notebook
### The cities from the WeatherPy notebook are mapped using hvplots, with the size of the dot varying by humidity. The list of cities is then narrowed by preference on weather conditions. The Geoapify API was used to locate the nearest hotel in each city, and the map was updated so that the name of the nearest hotel shows when hovering over a column.