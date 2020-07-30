# Overview of the Project

## Basic Project Plan

Here’s an outline of your project plan:

- **Task**: Collect and analyze weather data across cities worldwide.

- **Purpose**: PlanMyTrip will use the data to recommend ideal hotels based on clients’ weather preferences.

- **Method**: Create a Pandas DataFrame with 500 or more of the world’s unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

Your analysis of the data will be split into three main parts, or stages.

1. **Collect the Data**

    - Use the NumPy module to generate more than 1,500 random latitudes and longitudes.

    - Use the citipy module to list the nearest city to the latitudes and longitudes.

    - Use the OpenWeatherMap API to request the current weather data from each unique city in your list.

    - Parse the JSON data from the API request.

    - Collect the following data from the JSON file and add it to a DataFrame:

        - City, country, and date

        - Latitude and longitude

        - Maximum temperature

        - Humidity

        - Cloudiness

        - Wind speed

2. **Exploratory Analysis with Visualization**

    - Create scatter plots of the weather data for the following comparisons:

        - Latitude versus temperature

        - Latitude versus humidity

        - Latitude versus cloudiness

        - Latitude versus wind speed

    - Determine the correlations for the following weather data:

        - Latitude and temperature

        - Latitude and humidity

        - Latitude and cloudiness

        - Latitude and wind speed

    - Create a series of heatmaps using the Google Maps and Places API that showcases the following:

        - Latitude and temperature

        - Latitude and humidity

        - Latitude and cloudiness

        - Latitude and wind speed

3. **Visualize Travel Data**

    Create a heatmap with pop-up markers that can display information on specific cities based on a customer’s travel preferences. Complete these steps:

    1. Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
    2. Create a heatmap for the new DataFrame.
    3. Find a hotel from the cities’ coordinates using Google’s Maps and Places API, and Search Nearby feature.
    4. Store the name of the first hotel in the DataFrame.
    5. Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

____

# Challenge

## Background

For the new modifications to the PlanMyTrip app, you are asked to add more data to the database, or cities DataFrame, so that customers know the weather in the cities when they click on a pop-up marker. You’ll also need to add the amount of rainfall or snowfall within the last three hours so that customers can filter the DataFrame using input statements based on the temperature range and whether or not it is raining or snowing. Finally, you’ll need to create a directions layer Google map that shows the directions between multiple cities for travel.

## Objectives

The goals for this challenge are for you to:

- Use nested try-except blocks.
- Use Pandas methods and attributes on a DataFrame or Series.
- Create a new DataFrame from a new API search with new weather parameters.
- Filter DataFrames based on input and nested decision statements, and logical expressions.
- Create pop-up markers on a Google map from a filtered DataFrame.
- Add a directions layer on a Google map between cities in the filtered DataFrame.
