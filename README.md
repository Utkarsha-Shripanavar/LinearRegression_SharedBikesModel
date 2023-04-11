# LinearRegression_SharedBikesModel
>The objective of this project is to find variables that are significant in predicting the demand for shared bikes and 
how well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


#Business Goal:
There is a requirement to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
 From our analysis of the categorical variables from the dataset inference from the categorical variables is as follows:-
• The demand of bike is less in the month of spring when compared with other seasons
• The demand bike increased in the year 2019 when compared with year 2018.
• Month Jun to Sep is the period when bike demand is high. The Month Jan is the lowest demand month.
• Bike demand is less in holidays in comparison to not being holiday.
• The demand of bike is almost similar throughout the weekdays.
• There is no significant change in bike demand with working day and non working day.
• The bike demand is high when weather is clear and Few clouds however demand is less in case 
of Lights now and light rainfall. We do not have any data for Heavy Rain + Ice Pallets + 
Thunderstorm + Mist, Snow + Fog , so we cannot derive any conclusion. May be the company is 
not operating on those days or there is no demand of bike.
• Looking at the pair-plot among the numerical variables temp and atemp has the highest correlation with cnt the target variable 0.64,0.65 respectively
and A Negative correlation observed with cnt vs hum and cnt vs windspeed -0.06 and -0.25

Based on the final model, following are the top 3 features contributing significantly towards explaining 
the demand of the shared bikes :- temp, weathersit_Light_snow_rain_thunderstrom and yr_2019
temp with coefficient of 0.59 i.e., 59%
weathersit_Light_snow_rain_thunderstrom:- Light Snow, Light Rain + Thunderstorm + Scattered clouds, 
Light Rain + Scattered clouds with coefficient of -0.24 i.e., -24%
yr_2019 with coefficient of 0.22 i.e., 22%
so the bike sharing company mus concentrate on these 3 features temp, weathersit_Light_snow_rain_thunderstrom and yr_2019.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python Jupyter version 3
GitHub


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by EDA module
- This project was based on learnings acquired in this tutorial [https://learn.upgrad.com/course/4476/segment/32128/190535/586561/3000753](https://learn.upgrad.com/course/4476/segment/33701/199684/614617/3129231)


## Contact
Created by [@Utkarsha-Shripanavar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available on git repository called LinearRegression_SharedBikesModel


<!-- You don't have to include all sections - just the one's relevant to your project -->

