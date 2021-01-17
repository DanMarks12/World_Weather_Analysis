# World_Weather_Analysis

## Project Overview
The purpose of this project was to provde analysis and planning tools to the company PLanMyTrip. These planning tools will involve weather analysis as well as hotel and lodging options for the given cities. We also provide our customers with a travel destination map and a travel itinerary map based on some inputs asked to the customer.

## Results

We began our project with a set of 2000 random latitudes and longitutdes through Pythons citypy module. From there coordinates we are able to pull the closest city and give certain descriptive statistics including max temp, humidity, cloudiness, wind speed and a current description of live weather in the area. 

![https://github.com/DanMarks12/World_Weather_Analysis/blob/main/weather_data/Fig3.png] ![https://github.com/DanMarks12/World_Weather_Analysis/blob/main/weather_data/Fig4.png]

After performing analysis on some of the data we pulled from our Weather API, we move into creating a tool for customers to use to plan their perfect vacation! We began by using google API to provide a global view of the hotels we have stored. We created an interactive map that is able to show which hotel we recomend in each city and some descriptive stats of what kind of weather you would except in these destinations. 

![https://github.com/DanMarks12/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPY_vacation_map.PNG]

After giving our customer an opportunity to chose their favorite destination we move on to creating an itinerary for them! We have suggested picking 4 cities in the same country so that travel can be accomplished from walking, driving, or biking. Through Google Maps Directions API we created tools so that we can plan a round trip for our customers. 

![https://github.com/DanMarks12/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPY_travel_map_markers.PNG]


![https://github.com/DanMarks12/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPY_travel_map.PNG]

Through these tools we hope all of our customers can plan their dream vacation!

