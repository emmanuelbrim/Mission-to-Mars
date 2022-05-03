# MISSION TO MARS
_Web Scraping to Extract Online Data_


## Overview of the Project

Large organizations employ web scraping to assess and track the competition within their industires via online. 
This project was undertaken to polish a web app that uses an automated web browser to visit different websites containing data on Mars Exploration and publish the results on a webpage.

The main goals for the project include:

- Scarping full-resolution images and titles of Mars Hemisphere.
- Updating the the scraping script, Flask app and the index.html file, so that the Mars Hemisphere images and tiles can be displayed on the page.
- Imporve the appearance of the page using Bootstrap3 components.

### Resources:


## Results

* **Weather Database**

Using the numpy module with the random function, 2,000 cordinates were generated to help produce city destinations.
The list of possible cities was generated from the cordinates after the citipy module was applied on the cordinates.
In order to get the weather condition of these cities, required using API calls to OpenWeatherMap to obtain current weather. 
A DataFrame was then created to hold the infomation retrieved from the call.

_Below is an example of the  DataFrame that was generated_

![city_data](https://user-images.githubusercontent.com/100079292/162348096-156e6293-0a26-4aba-881b-7415256917a1.PNG)


* **Vacation_Search**

Prefered weather was collected from clients using input statements where clients could enter the maximum and minimum temperatures they so desire.
These values were then used to generate cordinates to produce list of prefered cities from the weather database file.
Next an API call to Google maps returned the nearest hotels to possible city destinations.
Using info_box_template and list comprehension a marker layer map was produced to show cureent weather conditions for possible hotel locations around the world.

_Example of google maps with markers for current weather condition_

![Alt text](https://github.com/emmanuelbrim/World_Weather_Analysis/blob/main/Vacation_Search/Weather_vacation_map.PNG)


* **Vacation_Itinerary*

The creation of the vacation_itinearry involved the use of Google maps API to map out a sample itinerary from 4 cities that a client might prefer to visit based on the weather. The result showed a clean route for travel between four cities in South Africa. 


Example of google maps with markers for current weather condition_

![Alt text](https://github.com/emmanuelbrim/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

## Summary
Though the analysis done in this project meets the objectives for which it was set, other statistical analysis like using linear regression models on the weather provides more information on which clients would make a valid decision on which city to visit.

