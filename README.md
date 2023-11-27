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

This folder contains the following files:
  1. data_cleaning.rmd --> the file where the data was cleaned in order to be used
  2. analysis1.ipynb
  3. RNN_Weather_Predictor_IK.ipynb
 
### Code Installing/Building

This project was created using RStudio for the data cleaning and Python for the Decision Tree Regression and RNN models. Here are the steps:
  1. Run the data_cleaning.rmd file with the weather_data.csv to retrieve the average_temperature_ds.csv file to be used for the analyses.
  2. Run the analysis1.ipynb with a Python IDE along with the average_temperature_ds.csv in the same directory to build the decision tree regression model.
  3. Run the RNN_Weather_Predictor_IK.ipynb with a Python IDE along with the average_temperature_ds.csv in the same directory to build the recurrent neural network model.

### Code Usage

Running the files in SRC will produce predictive models that can be used to predict the temperature based off of the context provided from the data sources.

## Data

All the data for this project can be found in the [Data](https://github.com/ik4vrb/ds-4002-team-aai-project-3/tree/main/Data) folder.

There are two data files in this folder:
  1. weather_data.csv --> The original data set
  2. average_temperature_ds.csv --> The data set we used for the project after cleaning
   
### Main Data Set


|    Column     |  Description  |   Type  |
| ------------- | ------------- |------------- |
|     date      | The year and the month |  Date (Month year)  |
| days_min0_degrees | Number of days in the month where the minimum temperature was 0 degrees F | numeric |
| days_min32_degrees | Number of days in the month where the minimum temperature was 32 degrees F | numeric |
| days_max32_degrees | Number of days in the month where the maximum temperature was 32 degrees F | numeric |
| days_max70_degrees | Number of days in the month where the maximum temperature was 70 degrees F | numeric |
| days_max90_degrees | Number of days in the month where the maximum temperature was 90 degrees F | numeric |
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
|    figure1      | Cummulative Monthly Snowfall 1945-2023 | This graph demonstrates the commulative snowfall that happened every month for every year.  |
|    figure 2     | Maximum Rainfall by Month 1945-2023 | This shows the average maximum rainfall for evey month. |
|    figure 3     | Average Temperature Range 1945-2023 | This graph shows the average max and min temperatures for every month. |
|    figure 4     | Distribution of Commulative Rainfall 1945-2023 | This show the distribution of rainfall throughout the years. |
|    figure 5     | Distribution of Commulative Snowfall 1945-2023 | This show the distribution of snowfall throughout the years. |


## Reference
 
[1] R. Kosandal, “Weather forecasting with Recurrent Neural Networks in Python” Medium.com, Dec. 29, 2019. [Online]. Available: https://medium.com/analytics-vidhya/weather-forecasting-with-recurrent-neural-networks-1eaa057d70c3. [Accessed Nov. 5, 2023].  

[2] Lawrimore, Jay H.; Ray, Ron; Applequist, Scott; Korzeniewski, Bryant; Menne, Matthew J. (2016): “Global Summary of the Month (GSOM), Version 1". NOAA National Centers for Environmental Information. https://doi.org/10.7289/V5QV3JJ5. [Assessed Nov. 12, 2023]

[3] Lawrimore, Jay H.; Ray, Ron; Applequist, Scott; Korzeniewski, Bryant; Menne, Matthew J. (2016): “Global Summary of the Month (GSOM), Data Files". NOAA National Centers for Environmental Information.https://www.ncei.noaa.gov/data/global-summary-of-the-month/doc/GSOM_documentation.pdf .[Assessed Nov. 12, 2023]
