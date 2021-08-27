This repository contains an analysis of global weather data via the OpenWeather API, written Python in Jupyter Notebook files.

----

There are two directories:

1) WeatherPy
2) VacationPy

* WeatherPy.ipynb uses custom functions to call weather data from the OpenWeather API. 
* Random coordinates were generated with 'numpy' and we use the 'citipy' package to identify the nearest city to each coordinate.
* We then pulled weather data from OpenWeather API using 'requests' and 'json' with the assitance of 'time' and 'sys'.
* Data were cleaned and manipulated with 'pandas' and plotted with 'matplotlib'.

* VacationPy.ipynb uses the .csv output from WeatherPy.ipynb to plot humidity and select hotels based on specified weather conditions.
* Global humidity data were plotted with 'gmaps'.
 We then the filtered data based on weather preferences with 'pandas' and used the Google Places API to determine the closest hotel to our desired destination.

----

All code was written by Corey D. Anderson
