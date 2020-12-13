# COVID-19 Analysis 

## Authors
Lucas Brossi, Amar Chatterjee, Daniel Chow, Sandip Panesar

## Description

A group lab project for UC Berkeley Master of Information and Data Science w203 Statistics class.

We were tasked with building a regression model to answer a question relating to COVID-19, using a provided dataset of COVID-19, demographic, policy, economic, social and other information for 50 U.S. States (+ District of Columbia). 

Our model was designed to answer the causal question:

**"Does the implementation of a mandatory face mask policy for all individuals aid in reducing the case rate of COVID-19 in the United States?"**

The report describes our exploratory data analysis, and building of 3 separate OLS regression models. 

### Model 1

Designed to test the relationship between mask use policies and case rate per 100,000 state population. Also includes a variable for test rate, which was included as a control. 

### Model 2

The most optimal model - Contains the aforementioned variables plus a host of other relevant variables related to case rate. These variables include socioeconomic, race, policy and behavioral metrics. 

### Model 3

An acid test to test the robustness of Model 2. Model 3 purposely includes variables that are collinear with the included variables from Model 2.

We subsequently discuss the validity of the 3 models based upon CLM assumptions and further consider potentially omitted variables. 

## References
Data taken from [Google's Mobility Reports](https://www.google.com/covid19/mobility/)
