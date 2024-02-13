# Project Name
> Bike Sharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Package Versions Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
Building a multiple linear regression model for the prediction of demand for shared bikes.

## Background
A bike-sharing system provides access to bicycles for shared use to individuals for a short duration. These systems typically feature docks where users can borrow bikes after inputting payment details, with the bikes being returned to any dock within the same network.

## Trying to achieve
The company aims to identify:
  - Significant variables that influence the demand for shared bikes.
  - The effectiveness of these variables in explaining variations in bike demand.

## Dataset Information
The dataset utilized is a CSV-formatted bike sharing dataset (day.csv), with each row representing the details of bike rented on a particular day ranging from start of 2018 to end of 2019.


## Conclusions
Significant variables to predict the demand for shared bikes are:
i. Top 3 variables: 

    > temp - The coefficient value of '0.5499' suggests that for every one-unit increase in the temperature variable, the number of bike hires is expected to increase by 0.5499 units.
    > weathersit_light_snow_rain - A coefficient value of '-0.2871' implies that, a one-unit increase in the weathersit_light_snow_rain variable is associated with a decrease in the number of bike hires by 0.2871 units.
    > yr  - The coefficient value of '0.2331' suggests that for every one-unit increase in the 'yr' variable, the number of bike hires is expected to increase by 0.2331 units.
    
ii. Other important variables:

    > workingday                                       
    > windspeed                   
    > season_summer                
    > season_winter                
    > mnth_sep                     
    > weekday_sat                  
    > weathersit_misty 


## Package Versions Used
- numpy==1.24.3
- pandas==2.0.3
- matplotlib==3.7.2
- seaborn==0.12.2
- scikit-learn==1.3.0
- statsmodels==0.14.0


## Contact
Created by [@anagharavishankar] - feel free to contact me!
