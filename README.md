# Project Name: Demand prediction for Bike Sharing

Boom Bikes is a US based bike sharing service provider, the company recently has faced a revenue loss due the pandemic and is now aiming to perform a thorough analysis of the demand for the bike sharing.
Enough data has been collected in reference to the parameters( independent variables) that have an influence on the demand.
The aim of the project is to understand the influence of each of these factors on the demand, build a reliable model that can provide insights to the demand in future. The model should provide the company with relevant recommendations so that the company take enough measures to utilise the oppurtunities to increse their revenue by meeting the demand.

## Table of Contents
* Technologies used
Python
The important libraries used :-
Numpy
Pandas
matplotlib
seaborn
sklearn
statsmodel

## General Information

- What is the background of your project?

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.  The company had suffered revenue loss due to the pandamic situation, so there is a need for mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- What is the business probem that your project is trying to solve?

 There is a need to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. 
The Business goal is to assess the demand for shared bikes with the available independent variables and build a multiple linear regression model for the prediction of demand for shared bikes

- What is the dataset that is being used?
day.csv is the data set that has a total of 16 columns, that contains information about some of the factors (independent variables) that affect the demand for the Bike sharing. Some of the key variables are listed below from the dataset that has been used for the analysis
    - instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered

Conclusion
Out of the listed variables, the below listed variables have a greater impact on the demand.
•	Season: Spring season has the lowest value of cnt and fall season has the highest value of cnt. Summer and winter had cnt values in the middle.

•	Weather Situation (weathersit): The highest value of cnt was observed when the weather is clear / partly cloudy. During heavy rain/ snow there was a very significant drop in the number of users.

•	Holiday: The number of users was very low during holidays.

•	Month: September had higher number of rentals

•	Weekday: Weekends had a significant increase in the number of users

•	Working day: had very little impact on the number of users renting the bike



## Contact
Created by [@HamsaVR] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->