# Brendan McCormack - Data Science Fundimentals - Individual Project

## Introduction

The core goal of my individual project was to further focus on additional questions that I found to be very interesting and important to me that gave insight into things not gone into as much in the group project. Overall however, the goal is no different, to analyse and read grocery and food data to better understand how things have changed in the past 20 or so years. This was a desire primarily stemming from the recent political and societal presence that discussion over increasing grocery prices and the negative effects of it. 

This is very important to me as a upcomming arrival to the working world as I graduate from college and need to directly interact with those parts of the economy as soon as August 2026. Because of this I want to know how things may have been positioned against me and how I may need to overprepare compared to previous generations. Depending on how much trends have changed or if a newfound 'standard' for things has been the case for the past 5 or so years (very recent changes that seem to be sticking) there are important things that the past generation and role models cannot treach me of from their past experiances and I need to learn for myself. Finally there is a specific intrest in this form of data in particular due to what it may mean to the overall satisfaction and happiness of recent times in the U.S.A.

For the project I selected 2 core questions to explore and find an answer for:
1. How has the divide between "eating out" and "eating in" changed over the years and what does that trend show for overall responsibility and money spent?
2. How has the purchase and consumption of alchohol (both at and away from home) changed over the years and how may this relate to overall societal statisfaction?

## Selection of Data & Relation to Group Project Data

The selected datasets I decided to use in the project is the same datasets and peramiters that I used in my questions during the group project. That means that all 3 of the datasets used, 1 for the core questions and the other 2 for supporting ideals and final conclusions are from the United States Department of Agriculture. As stated in the group project, the presence of datasets from the U.S. federal government allows for a degree of reliability in the data that gives  the exact scope of the data desired, one localized entierly to the U.S. and acting as a good basis of information and trend analysis.

While there are 3 datasets used in the project, 2 of the 3 are more present for support of the question formatting and overall support of the questions rather than being used in the data. This is due to the 2 datasets acting as trend data of the changing inflation and wage growth respectivley and the questions themselves not focusing on the changing price and moreso on the changing demand. The final of the 3 datasets is both the primary one used for both the group and individual projects and focuses on the many different subsections of food data.

A core example of the data housed within the main dataset used is shown below:

<img width="955" height="443" alt="image" src="https://github.com/user-attachments/assets/68a9c7a4-762d-4f94-b050-498dcf632664" />

This dataset section focuses primarily on the total values and most general sections of data that allows for closer analysis of important parts, for this project the alchohol and food total data are all being used. 

## Meathods

Tools:
- NumPy, Seaborne, Pandas, and Scikit-learn for data analysis and inference
- GitHub for code housing and submission
- Jupyter Notebook for testing of code before merging
Meathods:
- Linear Regression under both questions to help analysis and understanding
- Data cleaning / munging through:
    - Merging of data points to allow for consistent increments (converting from monlthy data points to yearly data points)
    - Convergion of 3 data sets of smaller increments into 1 single dataset containing all the information for better access 
    - Conversion of data values to better units of measurements and significant figures to allow for better reading from code processes.

## Results

Question 1:
The core results from question 1 provides the following graph for analysis:
<img width="579" height="468" alt="download1" src="https://github.com/user-attachments/assets/8d30b3f8-6286-4fdc-9a0b-18cf751ace70" />

The core focus of question 1 was to see how people have trended overall over the course of the past decades in deciding between eating at home and eating out. From the code analysis, we can see a massive drop off during the pandemic years of 2020 and a massive resurgence after the fact as a form of adjustment. This 'adjustment' period does not seem to be letting up however as the food away from home sales have shown no sign of decreasing and are only increasing in number. In the meantime we can see a much more consistent upward trend of sales from food at home sales. Overall we can conclude from this data analysis that there has been an overall shift in favor of eating out since 2015 and the after years of the pandemic show a deep gap between eating out and purchasing groceries.  

Question 2:
The core results from question 2 provides the following graph for analysis:
<img width="610" height="453" alt="download" src="https://github.com/user-attachments/assets/ffb50d55-48df-49f5-bac4-6f129905094b" />

The primary analysis of this graph and dataset is to compare the changing trends of alchohol purchasing and determine what that shows on the overall ideals and emotinal standing of the nation. As shown in the graph, the overall trend seems to show that the alcohol at home purchasing was naturally offset higher than the purchasing away from home, until the case of 2020. Once the 2020 pandemic happened, purchasing away from home plummited while the begin of a upward growth happened in at home purchasing. This was followed right after the pandemic times by a very large surge in away from home trends to the degree that it met and nearly overlapped the slow decline in growth of at home alcohol spending. 

## Discussion

For the deeper analyis and core things to learn from the data housed within the project, the two question act as good guidelines for what was learned and what can be inferred. For the case of the first question the upward scaling both before the 2020 pandemic as well as the larger surge after the 2020 pandemic where it has such a large gap betweeen the at home and away from home spending. This data can cause two conclusions, that the process of going out to eat is more desireable, and that the process of preparing oneself food to eat is becoming less and less of a desireable thing. For the increase in traffic for eating out, there is many possibilites with the primary two concluded being a mix of a desire to begin socilizing and being in a place of many after such a restrictive and isolating timespan, and the idea that in the ever increasing cost and possible uncertanty of recent events, the shorter term satisfaction and furfillment of going to a nice resturaunt or something being prepared for you is beginning to outweigh the added mental load that possible foodstuffs purchasing and preparation may bring. For the small decrease in slope of eating at home through groceries, it is possible that the recent news and consensus of prices leads to more people avoiding the issue entierly and deciding that takeout or resturaunts are more reliable than the grocery store. 

In the case of the second problem, while not originally looking to have a larger meaning or statement to say in the large increase of away from home spending to such a degree to catch up to the increasing (albiet recent lower increase) of the at home alcohol sales, there are two conclusions able to be reached here as well. The first conclusion is a further support of one made in question 1, that the desire for a social position at resturaunts and pubs is more desireable than either saving money or chosing the more cost effective option of purchasing your own alcohol. This however does have the secondary nature of taking into account the still large increase in at home spending of alcohol, which brings forward the idea that people may be less satisfied with the nation and world state than they have been in the past as there is vices in drinking alcohol and escapism. Overall this does show a trend in people looking more favorably in the form of drinking out with others and enjoying life "in the moment" rather than staying sedimentary with a smaller upward trend of natural dissatisfaction with the status quo.

## Summary

This project aimed to look at food and alcohol spending data to possible get a better understanding of changing societal reations to the changing years and how these datasets can give insight into overall public sentiment of the state of the world. This was attempted to be done through the comparison of changing demand of "at home" food spending vs "away from home" food spending and the comparison of the changing demand of "at home" alcohol spending vs going out to get alcohol at resturaunts or pubs/clubs. 

Through the project data and overall analyzed trends, it can be seen that there have been larger growths of demand and traffic in both food and alcohol spending out of the home and in either larger institutions or as parts of social interaction with others. This as a final analysis brings forward the idea that people have a growing dissatisfaction with the status quo of the current society and are more willing to do more short term pleasures for social or physical furfillment than get swept up in the worries and doldrums of the modern years, especially post pandemic. 
