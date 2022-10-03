# **World Weather Analysis**

## Overview of Project

This project’s objective is to apply analysis, visualizations, statistical skills and retrieve specific information from websites using application programing interface (API) from 2000 cities around the world.  The expected deliverables for this project are:
1)	Retrieve Weather Data
2)	Create a Customer Travel Destination Map
3)	Create a Travel Itinerary Map

## Results 

### Retrieve Weather Data 

The Weather Data was retrieved based on a set of 2,000 random latitudes and longitudes. Using the Open Weather map and retrieving the information with API, the cities weather data was collected with the current weather description and saved in a new DataFrame.Data frame gives information about lattitude, longitude, city, country, maximum temperature , wind speedand current cloudiness description. Here image of collected data fram shown below:

![Weatherpy_data](https://github.com/miralchangela/World-Weather-Analysis/blob/main/Weather_Database/WeatherPy_data.png)
 
### Create a Travel Destination Map 

Using customer weather demands, potential travel destinations were identified along with nearby hotels. The destinations are identified with a marker layer map with pop-up markers.Below image is a Map representation with pop-up marker. Marker includes the Information about Hotel Name, City, Country and Current weather details.

![weatherpy_vacation](https://github.com/miralchangela/World-Weather-Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Create a Travel Itinerary Map

Using Google Directions API a travel route was created to display positional coordinate between four cities chosen by the customer. 

![weatherpy_travel_map_direction](https://github.com/miralchangela/World-Weather-Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_direction.png)

A marker layer map with pop-up was added to provide customized information to the user describing the name of the city, country, hotel and current weather description. 

![weatherpy_travel_map_marker](https://github.com/miralchangela/World-Weather-Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
