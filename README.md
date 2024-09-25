# Bike-sharing system
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
You are required to model the
 demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. 

- We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

- Bike Sharing dataset provided by upgrad is used for analysis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We have season, weathersit, workingday, year, are few of the categorical variables and below are the observation for the plots I have drawn,
	Bike Sharing count across different season : We can say that the bike's sharing is been approximately same during different seasons.
	Bike sharing across different years: We can see that the number of bike shared in 2018 and 2019 are approximately same.
	Bike sharing on working days vs holidays: we can clearly say that bike riding done on working day is drastically high when compared to weekend or holiday.
	Bike sharing w.r.t to Weathersit below are the observations:¶
	•	When the weather is Clear, bike renting is done more than 450.
	•	When the weather is Mist+Cloudy, the bike renting has reduced and it's falling between 200 to 300.
	•	When the weather is with Light Snow, the bike rides has dropped less than 100.
	•	When there is a heavy rain, there is no bike ride at all.
Bike Sharing count across different months : we can say that bike renting is more than 50 irrespective of the month and from January

- We have built our model using linear regression and we observe that R-squared value is 0.83 for train data and 0.80 for test data. Hence we can say that we the prediction made using above method is best model fit and it can be utilized for future predictions with similar set of data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
statsmodels 0.14.0
sklearn 1.2.2
numpy 1.26.4
pandas 2.1.4
matplotlib 3.8.0
seaborn 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upgrad

## Contact
Created by [@poonamrathod2022] - feel free to contact me!


<!-- ## License -->
<!-- This project is open source and available for access.
