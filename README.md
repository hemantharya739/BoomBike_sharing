# BoomBikes

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

	- Which variables are significant in predicting the demand for shared bikes.
	- How well those variables describe the bike demands
	
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The ask is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Technologies Used
- **Python** - version 3.10.5
- **Matplotlib** - version 3.9.2
- **Numpy** - version 1.23.5
- **Pandas** - version 1.5.3
- **Seaborn** - version 0.13.2
- **scikit-learn (sklearn)**- version 1.6.1
- **statsmodels**- version 0.14.4

## Conclusions
The summary of the model after data interpretation, visualization, data preparation, model building and training, residual analysis, and evaluation of the test model is as follows:

- **Model Performance**: The R-squared value for the training set is 82.19%, while the test set has a value of 80.91%. This suggests that our model explains the variance quite accurately on the test set, indicating it is a good model.

- **Mean Squared Error**: The model's mean squared error is almost 0 on both the training and testing datasets, suggesting that the variance is accurately predicted on the test set. The p-values and VIF were used to select significant variables, and RFE was conducted for the automated selection of variables.

- **Key Findings**: The bike demand for BoomBikes is dependent on temperature and whether it is a working day or not. More rentals are demanded in winter compared to summer and spring. The months of September and October had higher rental usage. In terms of days, the focus was on Wednesdays, Thursdays, and Saturdays, with more rentals on holidays.

- **Insights and Recommendations**: These interpretations provide meaningful insights into the bike rental market and user behavior. One recommendation is to implement aggressive marketing in the summer and spring seasons to drive up rentals. Since summer months show low rental levels, a strong marketing strategy for the first six months of the year can help increase rental numbers. Additionally, introducing incentives or strategic deals on days with less clear weather can attract more users. Rentals were higher in 2019 than in 2018, suggesting that over time, more people are adopting this service. Therefore, a strong analysis should be conducted to retain repeat customers.

## Acknowledgements
UpGrad tutorials on Linear Regression

## Contact
Created by [hemantharya739](https://github.com/hemantharya739) - feel free to contact me!
