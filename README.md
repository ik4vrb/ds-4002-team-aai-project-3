# What is the temperature outside?

### Project Information
  - DS 4002
  - Project 3
  - Team: AAI
  - This repository is a collaboration between Ishan Koroth, Ashley Huang, and Ana Cristina Cordova for DS 4002 Project 2

## Context

Weather is something that everyone looks at everyday. In order to be dressed correctly and not be too hot or too cold, everyone has to look at the temperature outside, listen to weather broadcasting, or more commonly, consult with various weather-forecasting apps. While weather-forecasting can sometimes be unreliable with weather events, it is usually more accurate in predicting weather temperatures. This led to us thinking, what would it take to create a predictive model for temperature? 

	For project 3, we want to create a predictive model for Charlottesville weather. We are aware this already exists in many shapes, ways, and forms, but we thought it would be a fun way to learn new tools and play around with data that affects us day to day. We come in contact with local Charlottesville weather every day whether it's walking to class or going grocery shopping. We want to be able to predict the average temperature for each month in Charlottesville. This will not only be something we learn about, but something we experience as well. 


## Repository Contents 

All code used for this project can be found in the [SRC](https://github.com/ik4vrb/ds-4002-team-aai-project-3/tree/main/SRC) folder.

This folder contains _ files:
 
### Code Installing/Building

This project was created using _____. Here are the steps:

(INSERT STEPS HERE)

### Code Usage

There are __ files in the SRC folder:

(INSERT SRC FILE INFORMATION HERE)

## Data

All the data for this project can be found in the [Data](https://github.com/ik4vrb/ds-4002-team-aai-project-3/tree/main/Data) folder.

Only one data set was used for this project.
   
### Main Data Set


|    Column     |  Description  |   Type  |
| ------------- | ------------- |------------- |
|     date      | The year and the month |  Date (Month year)  |
| days_min0_degrees | Number of days in the month where the minimum temperature was 0 degrees F | numeric |
| days_min32_degrees | Number of days in the month where the minimum temperature was 32 degrees F | numeric |
| days_max32_degrees | Number of days in the month where the maximum temperature was 32 degrees F | numeric |
| days_max70_degrees | Number of days in the month where the maximum temperature was 70 degrees F | numeric |
| days_max90_degrees | Number of days in the month where the maximum temperature was 90 degrees F | numeric |
|   numD_fog   | |  |
|  numD_thunder | Number of days in the month where there were thunderstorms | numeric |
|  min_temp_ext | The extreme minimum temperature that there was during given month | numeric (celcius) |
|  max_snow_depth | Highest daily snow depth in the month | numeric (inches)  |
|  max_daily_snowfall | Highest daily snowfall in the month | numeric (inches) |
|  max_daily_rain | Highest daily total of precipitation in the month | numeric (inches) |
|  max_temp_ext   |  The extreme maximum temperature that there was during given month  | numeric (celcius) |
|  total_rain    | Total precipitation for the month  | numeric (inches) |
| total_snowfall | Total snowfall during given month | numeric (inches) |
|  avrg_temp | The average temperature for given month | numeric (celcius) |
|  avg_max_temp | The average of daily maximum  temperature | numeric (celcius) |
|  avg_min_temp | The average of daily minimum temperatures | numeric (celcius) |


## Visualizations 
All the visualizations for this project can be found in the [Figures](https://github.com/ik4vrb/ds-4002-team-aai-project-3/tree/main/Figures) folder.


|    Figue ID     |  Figure Name  |  Description  |
| ----------------| ------------- | ------------- |
|  Figure 1       | Estimated Price by Time Period | Boxplot demonstrating the spread of price estimates within a given time period. The data base had three diferent time periods which is why there are only three box plots.|
|  Figure 2       | Artist Count | This is a bargraph demontrateing how many paintings correponding to each artist are represented in the dataset. |
|  Figure 3       | Average Price of Painting by Artist| This is a bragraph demontstrating the average estimaed price by the artist represented in our data set. |


## Reference
[1] G. Fernández, “The 200 Most Valuable Paintings in private hands” theartwolf.com, May. 2008. [Online]. Available: https://theartwolf.com/art-market/most-valuable-paintings/. [Accessed Oct. 8, 2023]
[2] Ray, “Color, Shape, and Texture: Feature Extraction using OpenCV” medium.com, Feb. 19, 2022. [Online]. Available: https://medium.com/mlearning-ai/color-shape-and-texture-feature-extraction-using-opencv-cb1feb2dbdAccessed Oct. 7, 2023.
