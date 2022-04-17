# World Weather Analysis

## Purpose
The purpose of this project was to create a vacation map that allows users to plan vacation destinations by looking at their desired weather conditions.  I utilized OpenWeatherMap APIs and Google APIs to provide the user to view cities, and hotels, based on the user's ideal weather data, and then map their vacation iteneraries.  

## Overview
In order to create the map, I generated 2,000 random latitutes and longitutes, then retrieved the closest cities using the Pandas citipy module.  From there, I was able to retrieve the current weather data for those cities.  Based on the user's input of a maximum and minimum temperature, I was able to filter the cities to match that input.  I then generated hotels within 5000 meters (or approximatley 3 miles) of the city center.  I then mapped those hotels, with a pop-up marker containing the hotel name, city, country, current weather, and maximum temperature.  The user can then map their travel route using the Google Directions API.  
