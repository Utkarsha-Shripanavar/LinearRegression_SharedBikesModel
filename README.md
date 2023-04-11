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
- By looking at the data set we understand that cnt variable that indicates the total number of bike rentals, including both casual and registered is our target variable, 
 
 Upon doing the bivariate analysis over the categorical variables with respect to target variable loan_status it can be concluded that :- 
   - Borrower who choose term of 60 months tend to have 30% more chances of default then people with loan term of 30 months
   - Borrower who take loan grade is of F and G tends to have higher defaulting chances of 30% then compared to other grades 
   - Borrower who take loan Sub grade F5 have 50% chances of defaulting
   - Borrower who apply for the loan with the purpose of 'small business' have 30% more chances of defaulting then other purposes.
   
  Upon doing a bivariate analysis on numerical variables with respect to target variable loan_status it can be concluded that :-
   - Borrower whose loam amount is more, have higher chances of being defaulted
   - Borrower who has taken loan with higher interest rate have higer chances of being defaulted
   - Borrower who have more number of enquires in the last 6 months, have more chances of being defaulted
   - If the amount of credit the borrower is using relative to all available revolving credit is high then there are higher chances of being defaulted


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
Created by [@Utkarsha-Shripanavar,@khyatidesai09] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available on git repository called LinearRegression_SharedBikesModel


<!-- You don't have to include all sections - just the one's relevant to your project -->

