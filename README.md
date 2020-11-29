# World_Weather_Analysis
## Project Overview
Desiging the travel app - 'PlanMyTrip' which gives weather description and weather data of places. Then, we'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose particular cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between these cities as well as a marker layer map.
## Resources
* Data Source: https://openweathermap.org/api
* Software: Jupyter Notebook, Pandas Library, CityPy, Python Request, APIs, JSON Traversals
## Objectives
* Use nested try-except blocks
* Use Pandas methods and attributes on a DataFrame or Series.
* Create a new DataFrame from a new API search with new weather parameters.
* Filter DataFrames based on input and nested decision statements, and logical expressions.
* Create pop-up markers on a Google map from a filtered DataFrame.
* Add a directions layer on a Google map between cities in the filtered DataFrame.
## Challenge Summary
### Part I - Retrieving Weather Data
> Generating a set of 2,000 random latitudes and longitudes, retrieving the nearest city, and performing an API call with the OpenWeatherMap. Using API to retieve the current weather description of the city. Creating a new dataframe containing the updated weather data.

The DataFrame at the end of Part I of the project looks as below:

![1](https://user-images.githubusercontent.com/73450637/100529510-410b4a80-31b6-11eb-8660-ed981753b82f.png)

### Part II - Creating a Customer Travel Destinations Map 
> Using input statements, customer weather preferences are retrieved and then using those preferences potential travel destinations and nearby hotels are identified. Then, these destinations are showed on a marker layer map with pop-up markers.




### Part III - Creating a Travel Itinerary Map
