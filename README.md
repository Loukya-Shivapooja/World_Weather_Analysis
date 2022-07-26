# World_Weather_Analysis
## Overview of the Analysis
### Purpose
The purpose of this Analysis is to improve the travel app so that it contains weather descriptions along with our weather data. Customers will be able to use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. Lastly, we created both a travel itinerary and travel map as well as a marker layer map.
### Resources
* CSV Files: Weather_Database.csv, WeatherPy_vacation.csv
* jupyter notebook Files: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb.
* Python: Python v3.7.6, 
* Dependencies: Pandas Library, Matplotlib Library, citypy Library, SciPy Library.
* Python requests: APIs, JSON Traversals
* Data source: API from OpenWeatherMap, API from GoogleMaps.
## Results
### Retrieve Weather Data
The Weather Data was retrieved based on a set of 2,000 random latitudes and longitudes. Using the Open Weather map and retrieving the information with API, the cities weather data was collected with the current weather description and saved in a new DataFrame.
<img width="734" alt="Weather Database" src="https://user-images.githubusercontent.com/107584361/181102166-bc729acd-15dd-480d-aa29-46e2fd1ae2a0.png">
### Create a Customer Travel Destination Map
Using customer weather preferences, potential travel destinations were identified along with nearby hotels. The destinations are identified with a marker layer map with pop-up markers.
<img width="1026" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/107584361/181121313-c0339ac1-1d9c-476b-bd6e-7a8fa6d4fc1a.png">

### Create a Travel Itinerary Map
Using Google Directions API a travel route was created to display positional coordinate between four cities chosen by the customer.
<img width="1440" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/107584361/181121355-b73e613d-78c0-4080-b56e-930b9f9fb1ae.png">

## Summary
