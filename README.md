# World Weather Analysis
## Overview of the Project
Jack, who works for PlanMyTrip app, along with beta testers would like to make these changes below to the app in order to optimize its performance:
* Adding the weather description to the weather data already priorly retrieved.
* Adding input statements for users to filter the data for their specific weather preferences, which will be used to identify potential travel destinations and nearby hotels.
* After making these changes the beta testers will choose four cities to create a travel itenerary. 
* Finallly, using the Google Maps Directioins API, I have created a travel route between the four cities as well as a markerr layer map
## Results
### Weather Database
The weather database was created by specifically extracting the data below
![weather_dataframe](https://user-images.githubusercontent.com/85372441/126918400-d5dc789c-a535-42e7-b77f-4b79c4152d0e.PNG)

### Vacation Search
The vacation search database was created after filtering the cities that meets the users specified minimum and maximum temperature preferences.
![vacation_search_df](https://user-images.githubusercontent.com/85372441/126918630-8b819227-9080-476e-b858-f114e537bbda.PNG)

The vacation map below was created after adding a heat layer and a marker layer.
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/85372441/126918767-aa34b5c0-ccc9-4ddd-9cb0-1302a468128a.PNG)

## Vacation Itenerary
The vacation itenerary dataframe below was created after the users selected four cities based on their weather preferences.
![vacation_itinerary_df](https://user-images.githubusercontent.com/85372441/126918949-1126249d-4113-46a2-bed2-33e44c06ddc1.PNG)

After selecting those cities I was able to provide a vacation map from google maps for the users
* One with the trip route based on driving
* ![WeatherPy_travel_map](https://user-images.githubusercontent.com/85372441/126919024-238c4b04-add0-475e-b9e2-12e568cbe7cf.PNG)
* One with an added heat layer and marker layer
* ![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/85372441/126919066-96fbd2c3-361c-47e9-aa92-3fd7f55df573.PNG)

## Summary
In conclusion, these changes have made the PlanMyTrip app much more user friendly and Jack as well as the beta users should be more than satisfied. In addition, more filters could be added using other APIs that could help filter through cities with michelin star restaraunts, specific sporting/entertainment events, etc.
