# Bike Sharing Assignment
> We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same. 

- Bike sharing data set of 2018 and 2019 along with data dictionary is provided

**Problem Statement:**

- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- A US bike-sharing provider BikeIndia has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

- In such an attempt, BikeIndia aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    -  Which variables are significant in predicting the demand for shared bikes. 
    -  How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

**Business Goal:**

- We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- As per our final model, the following variables can significantly predict the demand for shared bikes:
    -   year
    -   workingday
    -   windspeed
    -   Jan
    -   Sept
    -   Mon
    -   Light_snowrain
    -   Misty
    -   spring
    -   summer
    -   winter

- Out of all the significant variables, the top 5 predictor variables that influence the bike booking and which the company should focus on after the end of COVID-19   situation are listed below.

    1. **Year** - A coefficient of 0.247992 indicates that a unit increase in 'year' variable, increases the bike hire numbers by 0.247992 units. Based on previous data it is expected to have a boom in number of users once situation comes back to normal, compared to 2019.


    2. **Light_snowrain** - A coefficient of -0.303393 indicates that w.r.t weathersit_1 (clear weather), a unit increase in Light_snowrain variable decreases the bike hire numbers by 0.303393 units. There would be less bookings during Light Snow or Rain. So the company could probably use this time to service the bikes without having business impact.


    3. **Spring** - A coefficient of -0.258069 indicates that, w.r.t season_1 (fall), a unit increase in spring variable, decreases the bike hire numbers by 0.258069 units. So the company should not focus on expanding business during Spring.


    4. **Windspeed** - A coefficient of -0.188736 indicates that, a unit increase in windspeed variable decreases the bike hire numbers by 0.188736 units. So the company should not expect on high bookings during windy days as the demand will be low during such days. People generally avoid bike riding during windy days as it is cold.


    5. **January** - A coefficient of -0.103085 indicates that w.r.t month_1 (April), a unit increase in January month variable decreases the bike hire numbers by 0.103085 units. So the company should not focus on expanding business during January as the demand will be probably less due to winter season when people would not prefer to ride bikes.


    So, it is recommended to consider these variables with utmost importance while planning their sales to achive maximum rentak booking.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - 1.24.3
- python - 3.11.4
- seaborn - 0.13.0
- pandas - 1.5.3
- plotly - 5.17.0
- matplotlib - 3.7.1
- statsmodel - 0.14.0
- scikit-learn - 1.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on [Bike Sharing Assignment from Upgrad](https://learn.upgrad.com/course/4705/segment/43555/258687/790246/3970578).


## Contact
Created by [https://github.com/kallalnath] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->