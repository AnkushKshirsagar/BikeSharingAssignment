# Project Name
> Bike Sharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

Essentially, the company wants —


- To identify which variables are significant in predicting the demand for shared bikes.

- To create a linear model that quantitatively relates total number of bike rentals (bike demands) with variables such as year, month, holiday, weekday, working day, temp etc.

- To know the accuracy of the model, i.e. How well those variables describe the bike demands.

**So interpretation is important!**

### Business Goal:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

# Following below steps for building model:

1) Reading and understanding the data

2) Visualizing the data

3) Preparing the data for model training 

4) Splitting the Data into Training and Testing Sets

5) Building a linear model

6) Residual Analysis of the train data

7) Making Predictions and Evalaution Using the Final Model

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

1) The R-squared value of the train set is 79.15% whereas the test set has a value of 77.00% which suggests that the model broadly explains the variance quite accurately on the test set, so it can be concluded that it is a good model. Also the Adjusted R-squared for training data is 78.8% which is very close to R-squared.

2) Developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set.  

3) As per the model below variables are significant for shared bike demand, `temp`, `year` and `season_winter` been the most significant:
- yr
- holiday
- temp
- windspeed
- season_summer
- season_winter
- mnth_sept
- weekday_sun
- weathersit_moderate

    cnt = 0.2385*yr  - 0.0915*holiday + 0.5489*temp -0.1820*windspeed + 0.0879*season_summer + 0.1165*season_winter + 0.0892*mnth_sept - 0.0428*weekday_sun - 0.0667*weathersit_moderate + 0.1296

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - pandas
- library - numpy
- library - seaborn
- library - matplotlib.pyplot
- library - sklearn
- library - statsmodels
- library - scipy 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@AnkushKshirsagar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->