# spotify-and-weather-data-analysis

## Table of Contents
- [Hypothesis](#hypothesis)
- [Motivation](#motivation)
- [Data Set](#data-set)
- [Data Processing](#data-processing)
- [Exploratory Data Analysis](#exploratory-data-analysis)

## Hypotehesis
Hypothesis: When the weather is warm, my preferences for music tend to be more up-beat and I spend less time listening to music. On the contrary, when the weather is cold the music I listen to tends to be slow-paced and I spend more time listening to music. 

## Motivation
Music choices are often influenced by our mood and external factors like the weather. Through this project I aim to discover how my spotify listening habits -such as the genres, and how many hours I listen to music- are impacted by weather conditions. After this project I hope to have a better understanding of how my music listening preferences are affected by weather conditions such as the temperature or by the fact that if the day is sunny, cloudy, rainy etc. 

## Data Set 
Spotify: Spotify’s personal data request feature. Data will be collected from my spotify account in the privacy settings from the “Download Your Data” section (this will be a JSON file). It contains track metadata (song name, artist, genre, playlist) and timestamps of when each track was played. In addition to this, Spotify Web API will be used to retrieve information about the tempo of the music streamed. 
Weather Data: Historical weather data will be collected from OpenWeatherMap or WeatherAPI (or could be another option). The data will include daily temperature, precipitation, and weather descriptions (sunny, rainy, cloudy) for the dates corresponding to Spotify listening history.

## Data Processing 
To analyze the correlation between weather and Spotify listening habits, the project will begin with data cleaning and preprocessing. Spotify data will be processed to convert timestamps into a date format and grouped by date to see daily listening activity, such as total songs played and top genres. Similarly, weather data will be standardized to match date formats and will include daily averages for temperature, rainfall, and other conditions. The datasets will be merged to identify relationships. 

## Exploratory Data Analysis
Exploratory data analysis will involve visualizing trends in daily listening habits and weather conditions to identify potential patterns and relationships. Things that will be examined: play counts versus temperature, changes in genre preferences under different weather conditions (upbeat music during sunny days or slow songs during rain). The list of things to be examined can be enriched. 
To support EDA, visualizations will play a critical role in presenting insights effectively. Line plots and scatter plots will be used to track daily trends in play counts alongside temperature levels. Bar charts and pie charts will illustrate distributions of genres under different weather conditions. 
