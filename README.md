# Linear-Regression-Assignment
This assignment is a Linear-Regression programming assignment wherein I have to build a multiple linear regression model for the prediction of demand for shared bikes.

## Table of Contents
* Problem Statement
* Business Goal
* Libraries Used
* Conclusion

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.
The company wants to know which variables are significant in predicting the demand for shared bikes or how well those variables describe the bike demands.
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Business Goal
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Libraries Used
* There are few libraries which are used for the assignment. 
* For analysis and numerical functions, pandas and numpy libraries were imported.
* For Visualization, seaborn and matplotlib libraries were imported
* For Regression, train-test split, RFE, Linear Regression, adding Constant, VIF and r2_score were imported from sklearn.
* To avoid warnings, warning's filter was imported.

## Conclusion
### We can see the demand for bike-sharing system depending on below variables:
* year , holiday , temp , humidity , windspped, summer , winter , January , July , Sep , Cloudy, Light_rain/snow are the main factors for demands od bikes.
* Demand for bike-sharing system decreases at the time of holidays mostly in January and July when its Humid, Cloudy, has High windspeed and Light rain or snow.
* Demand increase in month of September, December when winter is going on and also at the time of summer where temprature is high.
* Temperature and Year also plays important role for increase in demands of bike-sharing system.
* Seasons like winter and summer are the most demanding for bike-sharing, whereas cloudy, humid, light, and heavy rain/snow are the worst time for bike-share. 
* As the rentals are increasing, 2019 has more bike rentals than 2018 as it might be getting more popular or people becoming aware of the environment.
* As seasons make a huge difference in bike-sharing the months will be equally related. September, winter months as December, and summer months are good for rentals, however, January, July, and rainy months have less demand.
* People prefer spending quality time with family and mostly at home, maybe because the demand is less for holidays.
* Weekdays cannot be inferred much but Saturdays and Sundays are holidays, so those weekdays will not have many rentals.
* Working day can be a demanding time for bike-sharing as it will be helpful for office goings, college students, and others.
* Weather conditions can play an important role in the demand for bike share. Light snow, heavy snow/rain will have fewer rentals whereas clear or partly cloudy days have more rentals.




