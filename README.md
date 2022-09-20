# World Weather Analysis

###### *Overview of Assignment*

You will see three folders (Weather_Database, Vacation_Search, and Vacation_Itinerary) in this repo. 

The overall goal of this project was to provide clients with a list with over 500 potential vacation locations, allow them to filter those destinations by a desired minimum and maximum temperature, and then provide them with a marker map showing all available options that meet their criteria. Additionally, I generated a vacation itinerary directions map assuming a client had chosen (4) destinations in the same vicinity. 

The Weather_Database folder contains code that generated the random list of cities and, using the OpenWeather API, gathered the current temperature, longitude, latitude, and weather conditions. This data was extracted and used in the code found in Vacation_Search folder to generate a list of cities that meet the clients temperature criteria and create a heatmap visual for all options. Lastly, in the Vacation_Itinerary folder we have code that used the data collected from the Vacation Search analysis and picked (4) cities within close proximity to generate a directions map and heatmap visual. 
