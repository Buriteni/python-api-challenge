# python-api-challenge

# Background

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

# Part 1: WeatherPy

In this deliverable, created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python libraryLinks to an external site, the OpenWeatherMap APILinks to an external site, and my problem-solving skills to create a representative model of weather across cities.

For this part, I used the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. 

Getting started the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination was provided.

## Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

To fulfill the first requirement, I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. The following are a series of scatter plots to showcase the following relationships:

-Latitude vs. Temperature

![](WeatherPy/Weatherpng/CityMTemp.PNG)