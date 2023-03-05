Data Science Practicum
Life Expectancy analysis Summary 

Life expectancy is a critical measure of the overall health and well-being of a population. It serves as a vital indicator of the standard of living and provides valuable insights into the social, economic, and medical conditions of a society. We will be using the Life Expectancy Data by WHO. In this data we will be examining the factors that affects the Life Expectancy considering demographics variables, income composition and mortality rates. This data considers data from 2000 to 2015 for all the countries and looks more into the intricacies of life expectancy by examining various factors such as immunization, mortality, economics, and other health-related indicators. These multiple country data aim to identify which factors have the greatest impact on life expectancy and in turn, provide insights to countries on which areas they focus on to enhance the health of the population. It will help us know the factors that affect life expectancy and contribute towards its improvement.  

The main goal of this analysis was to answer the following questions in regards of Life Expectancy Data. 

What factors are most strongly associated with life expectancy?
Can we identify specific diseases or health conditions that have had a significant impact on life expectancy? 
How does life expectancy vary by country or region, and what factors explain these differences? 
Does machine learning algorithms help predict life expectancy for individuals or populations? 

Implementation 

This project was performed in Jupyter Notebook where python was utilized and Data science tasks like Linear Regression, Multi linear regression and Decision tree were used to build the model.

Data Collection Cleaning and EDA 
This data was directly published by WHO where the data was collected from member countries and published in various reports and databases. The data is based on demographic, health, and mortality statistics from national and international sources, and it is standardized to ensure comparability across countries and over time. As EDA is a critical step in analysis, we visualized the data and also split the data into train and test which will helped in the Machine learning tasks that we performed. 
 
Creating the models 

We created three models. 

1.	Linear Regression
2.	Multi Linear Regression
3.	Decision tree 

In conclusion we found that a multi-linear regression model provided a good fit for the test data. Moreover, decision tree models showed high accuracy in predicting percentage expenditure based on GDP and life expectancy based on income composition. The analysis also revealed that adult mortality, HIV/AIDS, thinness, and under-five deaths were associated with decreased life expectancy.

