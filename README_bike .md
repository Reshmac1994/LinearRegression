**Linear Regression Assignment**

**Problem Statement**

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.



**Objectives**

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

**Business Objectives**

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Table of Contents

**Step 1:Reading and Understanding Data

- Loaded the data related to bike
- Printed the column names, head and shape

**Step 2:** Data Cleaning: Handle missing values, outliers, and inconsistent data entries.

- Filled the Null Values
- Detected And Removed the Outliers
   - 

**Step 3:** Data Exploration: Analyse demographic information, loan attributes, and repayment status.

- Created Univariate , Bivariate , Multivariate Analysis using the graphs
- Univariate- Boxplot 
- Bivariate- Scatter plot
- Mutivariate- Heatmap

**Step 4:** Preparing the data for modelling
--Counting the categorical variables
--Dropping casual and registered variables


**Step 5:** Creating dummy variables
- #Encoding
#1. Converting binary vars to 1/0
#2. Other categorical vars to dummy vars

**Step 6:**Splitting into train and test sets
--Rescaling the features

**Step 7:**Training the model
--create the first model
--fit model
---params
--summary

**Step 8:**Checking VIF

**Step 9:** Residual analysis

**Step 10:**Predictions and Evaluations on the test set

## Conclusions

From this regression analysis, we can conclude that several factors significantly influence the dependent variable. Specifically, season, weekday, weathersit, holiday, year, temperature, humidity, and windspeed all have notable impacts, while the month does not show a significant effect. This kind of analysis helps in understanding which factors are most influential and can guide decision-making and further analysis.

## Technologies Used

- Python - version 3.11.2
- Jupyter Notebook - version 7.1.2

## Acknowledgements

- The project was based on Linear Regression Assignment to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

## Contact

Created by [@Reshma C] - feel free to contact me!

