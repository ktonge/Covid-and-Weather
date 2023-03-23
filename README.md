
# Group 2 Final Project 
# Deliverable 1
## Project Design  
As a group we're looking at combining weather and Covid 19 datasets.  We are hoping to use multiple linear regression to determine what, if any effect, does weather have on the covid infection rate. 

When looking at databases, we discovered that our most immediate challenge would be determining scope of the study.  There are massive amounts of weather and covid data. We started doing research into pre-existing papers on the topic. We started out looking at the relationship between weather and the spread of Covid-19, after reviewing existing research, we chose to create three tables: one for county weather data and two for covid data (separated into sparse and dense by population density in the county).  

### Benefis of Analysis 
Improved understanding of the relationship between weather and Covid-19 infection rates: By using multiple linear regression to explore the relationship between weather and Covid-19 infection rates, your analysis may provide new insights into how weather conditions impact the spread of the virus. This information could be useful for public health officials and policymakers in developing targeted strategies for controlling the spread of Covid-19.
Identification of high-risk areas: Your analysis may also help identify areas that are particularly vulnerable to Covid-19 outbreaks based on weather conditions. This information could be useful for directing resources and interventions to those areas in order to mitigate the spread of the virus.
Contribution to scientific knowledge: By conducting this analysis and sharing your findings with others, you are contributing to the scientific understanding of Covid-19 and its relationship to weather conditions. This information may be useful for future research and could help inform public health policies and practices aimed at controlling the spread of the virus.

### The Questions
Is there a correlation between temperature and the number of COVID-19 cases?
How does the relationship between temperature and COVID-19 cases differ across different cities or regions?
Can we use machine learning models to predict the number of COVID-19 cases based on temperature and other variables such as population density?
+ Forming a more coherent hypothesis here with specific goal

## Data Exploration
### Working with the Covid Data
We found our covid data first, which was organized by counties.  We were choosing counties to compare, and initially struggled with what counties to compare. 
Determining what data to use
+ CDC
...The CDC also has criteria for grouping cities.  These groups range from rural to metropolitan.  Most of the cities in our dense county group fall into major and minor metropolitan areas (a key difference between them and the sparse county group) 
+ Population Density 
... We chose the following criteria: population density and covid mask mandates. To make our counties all comparable, we only chose counties that did instate a mask mandate. We chose two selections of counties: counties with a population density of 1000-2999 people/square mile as our sparse group, and counties with a population density of 4000-6999 people/square mile as our dense group.  We used data collected by the US census to determine county population density.

Our two county groups were:
1. <b> Dense Counties: </b> Baltimore City, Maryland; Essex, New Jersey; Cook, Illinois; Union, New Jersey; Norfolk, Virginia; Nassau, New York; Harrisonburg, Virginia
2. <b> Sparse Counties: </b> Fairfax County, Virginia; Camden County, New Jersey; Harris County, Texas; Franklin County, Ohio; Marion County, Indiana; Dekalb County, Georgia; Duval County, Florida; Wake County, North Carolina; Bexar County, Texas 

We then collected and cleaned the covid data, including creating two new columns, future_delta7 and future_delta14 which represent the change in number of covid cases from today to 7 days and 14 days from today respectively.We were looking to answer questions about how does the weather in the past impact covid cases in the future.  Does the temperature two weeks previously affect the covid infection rate? 

### Working with the Weather Data
+ Where we got the data 
+ What variables we chose to look at
+ questions to look into that came out of the weather data 

## Preliminary Analysis 
### Covid Data
+ how many data points we have
+ trends in data 
+ descriptive statistics 
### Weather Data
+ data points
+ descriptive statistics

## Designing a Multiple Linear Regression Model 

## Conclusion
The project aims to explore the relationship between weather and COVID-19 cases by using multiple linear regression analysis on combined datasets. The study faced challenges in determining the scope of the project due to the vast amount of available data. We focused on comparing counties with population density and mask mandates as the criteria for selection. The COVID-19 data was collected and cleaned and created new columns for future delta7 and future delta14. The questions to be answered include identifying the correlation between temperature and COVID-19 cases, regional differences in the relationship, and the potential use of machine learning models to predict COVID-19 cases based on various factors. The project has the potential to provide insights into the impact of weather on the spread of COVID-19, which could have implications for future pandemic response strategies.

