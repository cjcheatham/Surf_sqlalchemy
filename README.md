# Hawaiian Climate Analysis

![hawaii.jpg](SurfsUp/images/hawaii.jpg)

## Overview
This analysis is a climate analysis for Hawaii for those who are planning a vacation. This overview section will explain where to find all files that were used to conduct this analysis. All files are found within the SurfsUp folder. This folder contains a resources folder, an images folder, app.py, and climate.ipynb. The data folder will be broken down in the data section of this README. The images folder contains images used in this README. app.py is an app python file that is used to store the data. climate.ipynb is the main file for this analysis.

## Data 
Found within the Surfsup folder, there is a folder titled *resources*. Within this folder, there are two csv files and a sqlite file that are used in this analysis.

<ins>hawaii_measurements:<ins/>

The data in this file consists of the following variables:

* The station id (station).

* The date (date) ranging from the years 2010-2017.

* The precipitation in inches for that day (prcp).

* The tobs (tobs) which record the maximum temperature for that day.

<ins>hawaii_stations:<ins/>

The data in this file consists of the following variables:

* The station id (station).

* The name of each station (name)

* The location of each station split between latitude, longitude, and elevation (latitude), (longitude), (elevation). 

<ins>hawaii.sqlite<ins/>

This file is an sqlite file that was used to create tables of the previously mentioned csv files, this file will be used more in the analysis. 

## Analysis 
This analysis is split into two sections:

* Precipitation Analysis

* Staion Analysis

<ins>Precipitation Analysis:<ins/>

The Precipitation Analysis aims to measure the precipitaion for Hawaii between August 2016 to August 2017.

![precipitation_table.png](SurfsUp/images/precipitation_table.png)

As we can see from the precipitation bar graph, the most precipitation was roughly in September in 2016 with almost 7 inches of precipitation. 

## App

