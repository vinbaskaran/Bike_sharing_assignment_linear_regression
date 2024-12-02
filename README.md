# Bike Sharing Assignment - Linear Regression
> The primary objective of this model is to identify and quantify the key factors influencing bike bookings. By understanding these predictors, the model aims to:
> - Provide actionable insights to optimize bike availability and resource allocation.
> - Forecast bike demand under varying environmental, temporal, and situational conditions.
> - Support strategic decision-making to maximize customer satisfaction and revenue.
>   
> This analysis will help prioritize critical variables, enabling effective planning and operational efficiency.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- The Goal is to understand which variables are significant in predicting the demand for shared bikes and How well those variables describe the bike demands.
- The dataset "day.csv" is being used, which had 730 rows and 16 columns. cnt is the dependent variable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **Final Result**
    - Train R^2 = 0.835
    - Train Adj R^2 = 0.831
    - Test R^2 = 0.811
    - Test Adj R^2 = 0.798
- **Key Predictors Influencing Bike Bookings**

  Based on our final model, the top three predictor variables that significantly influence bike bookings are:

    **Temperature (temp)**

    A coefficient value of 3888 indicates that a one-unit increase in the scaled temperature variable results in an increase of 3888 bike hires. This highlights the strong positive impact of temperature on demand.

    **Weather Situation 3 (weathersit_rainy)**

    A coefficient value of -2494 indicates that bike bookings decrease by 2494 units on heavily rainy days.This demonstrates the adverse effect of bad weather on demand.

    **Year (yr)**

    A coefficient value of 2039 indicates that a one-unit increase in the year variable leads to an increase of 2039 bike hires. This can be attributed to year-on-year brand growth and increased popularity.

- **Additional Influential Variables**    

  While the following predictors are slightly less impactful, they are still worth considering in forecasting and planning:

    **Windspeed**

    A coefficient value of -1318 indicates that a one-unit increase in windspeed decreases bike hires by 1318 units. Strong winds negatively affect customer willingness to hire bikes.

    **Holiday**

    A coefficient value of -790 indicates that bike bookings drop by 790 units on holidays, possibly due to reduced commuting activity.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas version: 2.2.2
- NumPy version: 1.26.4
- Matplotlib version: 3.8.4
- Scikit-learn version: 1.4.2
- Statsmodels version: 0.14.2
- Seaborn version: 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@vinbaskaran] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
