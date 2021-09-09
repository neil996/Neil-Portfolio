# Data Science Projects Portfolio


# [Project 1:Factors-affecting-Covid-19](https://github.com/neil996/Factors-affecting-Covid-19)

* The project aims to generalize the effects of Novel coronavirus across different counties in United States Of America and moreover discuss various different factors affecting the same. We have taken into account multiple age factors which are getting affected due to the virus and moreover takes into account different condition factors. The project looks to find distinct and diverse factors in various age groups, i.e. how they are impacting Covid deaths and cases across various regions in United States. The domain of the datasets is related to health care as discussed above the project aims to identify the impact of Covid. The datasets have been selected to take into account all these factors so as to combine diverse factors to get a generalized sense from the available data. The data is obtained mainly from Centre for Disease Control and Prevention which is Federal organization collecting data on daily or random basis as per their availability, moreover as per their description states and local authorities reports the cases regularly to keep the data up to date.

# Data Pre-processing

* To analyze the Null values in a more quantitative and generalized manner, we use different packages such as naniar which can give the number of missing values by plotting it and thus giving us a visualization to get more insights,fig. shows the implementation of naniar package

  ![image](/images/naniar.png)
  
* VIM (Visualization and Imputation of Missing Values) package helps to visualize the missing data in a deep way and thus can help to apply specific mechanisms which can be helpful in analyzing the missing values and deciding whether to impute/replace or remove it, while Fig Shows the implementation of VIM package.


  ![image](https://user-images.githubusercontent.com/78203289/120350915-4f6a2880-c2f7-11eb-9c7a-cfcab6a63ac6.png)


* Regression Techniques Implemented:

1.	XGBoost
2.	Random Forest
3.	Multiple Linear Regression
4.	Decision Tree

* Classification Models Implemented:

1.	KNN(K-Nearest Neighbor)
2.	SVC(Support Vector Classification)


# [Project 2:Time series analysis](https://github.com/neil996/Time_Series_Analysis)

Analysis of different time series models on OverseasTrips and NewHouseRegistrations in Ireland.
Th project makes use of different time series analysis models such as ARIMA, Naive, Simple Exponential Model, etc. Below is a short description of data set and how it is analyzed for a time series model.

# OverseasTrips Dataset

* The Overseas Trips dataset is obtained from Central Statistics Office in Ireland and is a quarterly time series data indicating travel by non-residents to Ireland from Q1. 2012 to Q4, 2019.
In this section, we will analyze the raw time series of the dataset which is also the required step in every time series modeling process. As the raw time series helps to identify the
Trends or Seasonality patterns within the data, which we can take into consideration during the execution of the models.

* Firstly the dataset extracted, is converted to a time series model using the function ts(), where the start and end is given along with the frequency and as this is a quarterly dataset, we given the frequency as 4. Moving on we plot the data using 
the function plot for which the output obtained is shown below in Fig. 1. ,which shows that there is increasing trend in the data as we move along from 2012 to 2020 moreover the plot also
indicates the presence of seasonality which although remains constant for most time but also show spikes as the years progresses.:

 ![image](/images/seasonal.png)
 ![image](/images/colouredquarterly.png)
 
 # [Project 3:Business-Intelligence-and-Business-Analytics](https://github.com/neil996/Business-Intelligence-and-Business-Analytics)
 
This was a group project in which I had a team of 2 members and our task was that we have been hired from Olist firm with intend to increase Sales and Profit Margins. We have to perform analysis on the current system, and we have to come up with the approach to implement full business intelligence suite which will give better Insights on the Customer and Sales. Olist is Start-up in Brazil in E commerce industry. The Main objective is to analyse the Gaps in the current System and give the low-cost scalable Business intelligence system.

# Business Background, Marketplace Information and Operations

* Olist Store is a very large departmental store in Brazil and it connects various small stores across the country on a single platform without any issues. As many stores are in the rural areas which though having products are not able to sell across the country due to logistic issues and most important factor to outreach the large consumer base. Through integration with Olist marketplace, such small and medium level stores are given the opportunity to expand their consumer base across regions which were earlier not part of their manifesto.
* The marketplace under which Olist operates comes under E-commerce, which has seen a rapid increase in the consumer base. In Latin –America, Brazil has a strong place in the e-commerce market with a market share closing to around 43%. As many rural areas in Brazil are able to access things outside their regions via mobile phones, thus attracting a large consumer base, and with a market share approaching 50 percent share in the entire Latin America, Brazil as a country cannot be ignored as a prospective marketplace considering the large population and ownership of cashless payment facilities mainly through credit cards. Moreover the increasing mobile commerce across the country with a significant percentage of approximately 40 percent just next to United States of America, makes Brazil as the forerunner in the prospect of E-commerce business.

# Tableau Powered Dashboards

As the scope of E-commerce is increasing day by day across different regions, we as Olist try to help our consumers which in this case are our sellers to help increase their business growth so that more and more sellers from different regions can be part of Olist eco-system which provides end to end demand and forecast handling in dealing with the customers. We have connected our Tableau directly with the database hosted on Azure SQL Server. The below figure shows Tableau direct connection with SQL Server, with database selected as BIBA_PROJECT and tables designated below the same.

 ![](https://github.com/neil996/Business-Intelligence-and-Business-Analytics/blob/main/images/tableau_sql.PNG)
 
## Story Line for our Payments Segregation Dashboard
 
### Credit card as a payment type
 
Credit card is the most common type of payment method prevalent across the entire globe, where the consumer even if don’t have sufficient money in their accounts can make the payments. Therefore on selecting the credit card as payment type in highlighter, Tableau is able to highlight the key parts in the entire dashboard.
Below are the core modules and insights shown by our interactive dashboard.

1. Credit card accounts for approx... 90 percent of Payment segmentation, showing that many distinct payments are made through credit cards.
2. Approximately 78 % consumers opted credit card as the mode of payment, this gives us an interesting insight which can be used by our sellers to promote their products.
3. In 2016 credit card payments accounted merely 0.25 %, but increased in 2017 by 30%, owing up to 34 % and in 2018 accounted for 45%.

![](https://github.com/neil996/Business-Intelligence-and-Business-Analytics/blob/main/images/paymenttype.PNG)

### Opting Boleto as a payment type

Boleto is a type of payment system in Brazil which is regulated by FEBRABAN, which is short for Brazilian Federation of Banks. Boleto’s can be used across different ATM machines, Outlets, Online Transactions and superstores till the expiration date.
Our dashboard below highlights some of the important aspects mentioned below:

1. Boleto as payment type accounts for approximately 20 percent as preferred payment type, second most after credit card usage.
2. Around 43.69 % distinct payments came through boleto payment type, again second most after credit card.
3. Payment type by year shows increasing trend ion usage of boleto as payment type, with stats as 0.06 % boleto usage in 2016, followed by approx... 10% in 2017 and finally 10.31% in 2018.

![](https://github.com/neil996/Business-Intelligence-and-Business-Analytics/blob/main/images/boleto.PNG)

### Opting Debit Card as a payment type

Debit card is the least opted payment method opted by the consumers while buying products through Olist. The below observations describes the insights retrieved from the dashboards.
1. Marginally 2% of consumers opted for Debit card as their payment method as can be concluded from the dashboard.
2. While in 2016, debit card did not accounted for any transactions through Online payments via Olist , the figure marginally increased in the following year coming to 1.11%.

![](https://github.com/neil996/Business-Intelligence-and-Business-Analytics/blob/main/images/debit.PNG)

# Customers Insights

The next Dashboard Gives information regarding Customer Insights.The First Bar Graph represents no. of customers by years like we can see in year 2016 we have less customers but there was a huge surge in the year 2017 which got increased from to 44,000 and then in year 2018 we again see huge margin increment in the no of customers of about 15000 customers.So already we can see lot of people start using E commerce websites for there buisness.We have also plotted the Demographic map which shows state wise Contribution of Customers and this Map tell us that Sao Paulo has highest no of customers in the year 2017 with count of 17.52 K customers, which finally got increased to 23.74 k customers in the year of 2018.As the Dashbiard is interactive we can see no of delivred product is also changing yearly.Also we can see delivered item also got increased which was natural as the no of cutomers got increased. We have also plotted Regression line in witn adjusted R Square 87 percent and the p value of 0.27 which is less then 0.5 means we are nearly correct in our Analysis.

![](https://github.com/neil996/Business-Intelligence-and-Business-Analytics/blob/main/images/insights.PNG)

 
# [Project 4:Analyzing Covid-19 Deaths in Patients with Different Conditions among Various Counties in the United States of America](https://github.com/neil996/Database-and-analsytics-programming)

As a group project comprising of 2 team memebers, this repository presents the work done by me, moreover there are 2 Jupyter Notebooks uploaded, and it contains analysis performed on Coivd-19 using Pandas dataframes, numpy, regression techniques and No-SQL databases design. The datasets has been acquired from CDC though Socrata API, and retreived in python by using limit parameter. Please clcik on the highlighted link to move to the particular repository and get more insights.)

Below is the abstract, detailing about the problem faced and how it will be tackeled thorugh this research.

* Since the spread of Covid-19 virus which has impacted the whole world, dislodging some of the world’s biggest economies to the bottom with no exception of the United States of America, the death rates across America spiked at a tremendous rate therefore causing tremendous loss of life. Thus such an impact around the world has been a motivation for the research, so as to evaluate the covid-19 mortality among various counties with patients suffering under various conditions such as some patients have septic, influenza and many other moreover finding the probable cases so as to predict the mortality rates of the region, which can help the counties to take measures to avoid such an outcome.

* The study aims to analyze various patients’ under different categories of their respective health status. The research in the topic helped to generalize the data in a more efficient manner so as to analyze the Covid deaths across various counties moreover exploring new insights in the hidden data such as number of probable deaths, new cases, updated probable deaths, identifying different age groups and their corresponding symptoms.


* Scatter plot:

 ![image](images/analysis.PNG)

* Pie chart showing patients with different conditions affected by covi-19

 ![image](/images/conditions.PNG)

* Bar chart showing Probable vs. Confirmed cases

 ![image](/images/probable.PNG)


