# spotify-and-weather-data-analysis

## Table of Contents
- [Hypothesis](#hypothesis)
- [Motivation](#motivation)
- [Data Set](#data-set)
- [Data Processing](#data-processing)
- [Exploratory Data Analysis](#exploratory-data-analysis)

## Hypotehesis
Hypothesis: When the weather is warm and precipitation is low I spend less time listening to music. On the contrary, when the weather is cold and precipitation is high I spend more time listening to music.


## Motivation
Music choices are often influenced by our mood and external factors like the weather. Through this project I aim to discover how my spotify listening habits are impacted by weather conditions. After this project I hope to have a better understanding of how my music listening preferences are affected by weather conditions such as the temperature and precipitation. 


## Data Set 
Spotify: Spotify’s personal data request feature. Data is collected from my spotify account in the privacy settings from the “Download Your Data” section (this will be a JSON file). It contains track metadata (song name, artist, genre, playlist) and timestamps of when each track was played. Weather Data: Historical weather data is from visualcrossing.com. The data includes daily temperature and precipitation information for the dates corresponding to Spotify listening history. 


## Data Processing 
To analyze the correlation between weather and Spotify listening habits, the project begins with data cleaning and preprocessing. Spotify data is processed to convert timestamps into a date format. Similarly, weather data is standardized to match date formats and will include daily averages for temperature and rainfall. The datasets are merged to identify relationships. 

## Exploratory Data Analysis
Exploratory data analysis involves visualizing trends in daily listening habits and weather conditions to identify potential patterns and relationships. To support EDA, visualizations play a critical role in presenting insights effectively. 


## Files
- [DSA 210 Project Report (PDF)](DSA_210_Project_Report.pdf)
- [Colab Notebook (IPYNB)](dsa210project.ipynb)
- [README (Markdown)](README.md)

## Detailed Report
A detailed report explaining the analysis, methodology, and findings can be found [here](DSA_210_Project_Report.pdf).
