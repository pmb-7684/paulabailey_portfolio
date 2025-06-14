## Academic & Personal Portfolio

### Personal Database, Excel, Tableau, Java, R, and Python Projects 

Welcome to a new section of projects featuring Excel, Tableau, MySQL, Python, clustering, machine learning, advanced unsupervised techniques, app development, microblogging, and LLM integration. Now that I’ve graduated, I’m committed to creating content on a bi-weekly basis to build my portfolio and advance professionally.

Starting now might seem counterintuitive but juggling full-time college while working third shift left little time for anything beyond studying, working, sleeping, and eating. After taking a short break to reflect on my projects, I’m ready to dive in—especially to showcase my proficiency in tools like Tableau and further refine my expertise.

Please return often to discover fresh content, innovative projects, and evolving expertise. Stay tuned—a completely redesigned website is coming soon to enhance your experience even further! 

---
[Sales Performance Dashboard - Coffee Shop (Excel)]()
<img src="images/Coffee_Shop_Sales.png" alt="Description" width="450" height="250" />

[Sales Performance Dashboard - Transportation Company (Excel)]()
<img src="images/sales_pmb2.png" alt="Description" width="450" height="250" />


---
### Academic Individual Database, Java, R, and Python Projects 

[Charlotte's Neighborhood Crime Over Time - Data Exploration (Python)](https://pmb-7684.github.io/Data_Mining_Project_1/){:target="_blank"}

Crime is a concern for many urban areas in the United States, and Charlotte is no exception. It is important to understand crime patterns and statistics to help communities and law enforcement agencies develop plans, allocate resources, and engage with the community to improve public safety. The Charlotte-Mecklenburg Police Department (CMPD) regularly publishes detailed crime reports. As of July 22, 2024, overall crime in Charlotte has seen a slight increase of 1% compared to the previous year. This includes various types of crimes, categorized broadly into violent crimes and property crimes.  Acquired data from [CMPD Data Portal.](https://data.charlottenc.gov/datasets/charlotte::cmpd-incidents-1/about){:target="_blank"}

Explored how crime has evolved over time in different communities and how does location (such as open field, department store, hotel/motel, etc.) of the incident within neighborhoods effective crime? By determining communitites that are experiencing higher than normal levels of crime and specific location, the city, local law enforcement, and community can help allocated resources, develop plans and support community outreach to support all neighborhoods.

<img src="images/CrimeOverTime.png" alt="Description" width="300" height="250" />


---
[Default of Credit Card Clients - Classification (Python)](https://pmb-7684.github.io/Data_Mining_Classification_Project2/){:target="_blank"}

Default of Credit Card Clients data set is available from UC Irvine Machine Learning Repository. It is based on research paper written by Che-hui Lien Yeh in 2009 which examined default patterns of Taiwanese customers. The research compared the predictive accuracy of six data mining techniques. For their initial research, neutral network more accurately estimated the real probability of default.

For this classification project, used various classification models to predict if an individual would default on their next month's payment or not.  Default of Credit Card Clients data is located [here ](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients){:target="_blank"} at UC Irvine Machine Learning Repository. 

<img src="images/default.png" alt="Description" width="250" height="200" />

---
[Wave Farm - Regression (Python)](https://pmb-7684.github.io/Data_Mining_Regression_Project3/){:target="_blank"}

Fossil fuel can be a double-edged sword offering both positive and negative opportunities.  It can offer wealth to countries to fuel their economies and gasoline (plus byproducts) to offer mobility and comfort in the form of electricity for their citizens.  On the other hand, fossil fuel can be devastating to the environment if it is extracted incorrectly, and it is not an infinite resource.
A promising renewable energy resource is the use of wave farms to create energy.  The ocean covers 70% of the earth's surface.  It is also about 97% of all water on Earth.  The abundance of the oceans is a major reason to explore wave farming as an option for energy. The goal is to predict the total power output based on the coordination of the wave energy converters (WECs) within a large wave farm.  By demonstrating the benefits of wave energy maybe we can change a few minds to invest in wave energy.

<img src="images/top20.png?raw=true" alt="Description" width="300" height="250"/>


---
[Charlotte's Neighborhood Crime Over Time Through Cluster Analysis (Python)](https://pmb-7684.github.io/Data_Mining_Clustering_Project_4/){:target="_blank"}

For this project, the data was explored through clustering analysis. Again, explored how crime has evolved over time in different communities. The difference is clustering was used to explore if certain neighborhood belongs to the same cluster. Acquired data from [CMPD Data Portal.](https://data.charlottenc.gov/datasets/charlotte::cmpd-incidents-1/about){:target="_blank"}

---
[Relational Database for Fictional Recreational Vehicle (RV) Park (MySQL)](https://pmb-7684.github.io/Database_Project_RV/){:target="_blank"}

Designed and implemented a relational database (Db) for the fictional *Hit the Road RV Park* which is situated on 50 acres in Western North Carolina.  The park contains RV parking and a garage for maintenance.   

<img src="images/schema.png "/>

---
[Charlotte Mecklenburg Police Department - Shiny App (R)](https://pmb-7684.github.io/shiny_CMPD/){:target="_blank"}

• Packages needed for installation.
```
install.packages(c("shiny", "shinydashboard", "shinythemes", "data.table", "tidyverse", "DT", "shinyWidgets", "caret", "randomForest", "rpart", "rattle", "rpart.plot", "RColorBrewer"))
```
• The shiny::runGitHub() code to run app in RStudio.

`shiny::runGitHub('shiny_CMPD', 'pmb-7684', ref = "main")`

ShinyApp is to analyze a portion of the Charlotte Mecklenburg Police Department (CMPD) crime data. The data is located at the City of Charlotte's [Open data portal](https://data.charlottenc.gov/){:target="_blank"}.  The CMPD incidents are located [here.](https://data.charlottenc.gov/datasets/cmpd-incidents-1/explore){:target="_blank"}  As of November 30, 2022, there were 542,153 observations with 25 variables (or features). 

The app contains an About page, a Data Exploration page which allows the user to select features (columns) and filter the rows of the data. The results are used to create categorical charts and summaries. This data set does not contain any numerical variables. This tab is divided into three sub tabs named Instructions, Data Selection, Visualization and Summary, a Modeling page that creates three supervised models - generalized linear regression model, classification tree, and a random forest model. This tab is divided into three sub tabs named Model Info, Model Fitting, and Prediction, and finally a Data page that allows the user to scroll through the data set and subset it by rows and columns. The user also has the ability to save the subsetted data as a .csv file, pdf, or as a copy.

---
[The Right Conditions for COVID-19 (PDF)](/pdf/BAN Week 6 - Final Report_pmbailey.pdf){:target="_blank"}

This capstone project focused on sixteen different universal conditions that could contribute to a person being infected with COVID-19.  The project completed in November 2020 as part of a capstone. World wide Coronavirus (COVID-19) data set which contained 50,350 observations and 41 variables. Used the programming language R to clean the data.

* Optimized linear, Lasso, Random Forest regressor, and other Machine learning techniques to determine the number of deaths from COVID-19 in 2020.
* Used Tableau to visualize important points in the data.
* Created a report addressing my question - why is a person infected with COVID-19? This question is based on if the following conditions contribute to being infected.  Those conditions were stringency index, population, population density, portion of the population over age 65, GDP per capita, extreme poverty, cardiovascular death rate, diabetes prevalence, smoker or not, number of hospitals, life expectancy and human development index.
<br><br>
The report of my findings on COVID-19 is located [here.](/pdf/BAN Week 6 - Final Report_pmbailey.pdf)
<br><br>
<img src="images/StngencyIndex.png "/>

---
[The COVID-19 Effects on Crime in Chicago (R)](/pdf/Chicago- Final Project 08.16.2020 PMBailey.pdf){:target="_blank"}

Explored the effects of COVID-19 on the crime rate in Chicago, Illinois so far in 2020.  Chicago has been known for having a high crime rate especially murder rate.  In 2019, 492 individuals lost their lives and 567 were killed in 2018.  So, in 2020 was there a significant effect on crime in general due to the pandemic, social distancing, and state government mandates?"  

* Acquired data from the [City of Chicago portal](https://data.cityofchicago.org/Public-Safety/Crimes-2019/w98m-zvie){:target="_blank"}
* The data set contained over 260,000 observations and 22 variables. Compared the period from 01/01/2019 to 08/01/2019 (pre COVID-19) to 01/01/2020 to 08/01/2020 (beginning months of the pandemic).
* Acquired data from [data.gov](https://covid.cdc.gov/covid-data-tracker/#county-view?list_select_state=Illinois&data-type=CommunityLevels&list_select_county=17031){:target="_blank"} for the COVID cases in Chicago. Note: link to the original website is no longer active.  The web site above from the CDC provides similar information.
* Acquired geospatial data from the [portal](https://data.cityofchicago.org/Public-Safety/Boundaries-Police-Districts-current-/fthy-xz3r){:target="_blank"} as well.

The report on my findings is located [here.](/pdf/Chicago- Final Project 08.16.2020 PMBailey.pdf)

<img src="images/primaryTypeDIff.png" alt="Description" width="250" height="200"/>

---
[Crime in Chicago and Being Arrested: Project Overview (R)](/pdf/Course Project Phase2.pdf){:target="_blank"}

Used machine learning techniques to predict the likelihood that a person would be "Arrested". Data set comes from the City of Chicago’s Data Portal and contains information about crime in Chicago in 2018. Models were built to predict the likelihood that a person would be Arrested."  We reduced the size of the dataset by sampling 15,000 observations from the original dataset, which contained 267,000 observations.  
  
* Optimized Classification tree, Logistic regression, Stacking, Random Forest, K-fold regression, and Regression with stepwise (Backwards and Forward). Three were discussed in this presentation: Classification, Logistic regression, and Stacking.
<br><br>
The presentation on my findings is located [here.](/pdf/Course Project Phase2.pdf)
<br><br>
<img src="images/Classification.png?raw=true"/>
<img src="images/logistic.png?raw=true"/>

---
[Walmart Streamlit App](https://simpleapp-lszmrlwqdxlcsuckbnwv37.streamlit.app/){:target="_blank"}

My first deployed web app using Streamlit.  This is simple app uses `yfinance` to retrieve stock information on Walmart.  It requests opening prices, closing prices, volume of stock exchanged and dividends paid for Walmart and creates simple visualizations.

---

### Group R and Python Projects
---
[Auto Theft and Social Disorganization Theory (Python)](https://pmb-7684.github.io/Grp_Project_AutoTheft/){:target="_blank"}

Data Science 3601/3602 project focused on a problem involving the analysis of one or more data sets and the application of machine learning and data mining methods to better inform policing and crime prevention efforts and policies. Building models that can identify patterns in the community crime dataset to help organizations better understand community factors and crimes and give them an advantage when making decisions in their fight against crime, better policing and safer communities.  Our group focused on the effects of social disorganization and auto theft.

The report of our findings is located[ here.](/pdf/AUTO THEFT CRIME ANALYSIS.pdf) 
<br><br>
The updated research presentation can be viewed [here](/pdf/AutoTheftAnalysis_update_pmb.pdf){:target="_blank"}
<br><br>
The findings reinforce the importance of social structures in crime prevention, showing that weakened community cohesion and economic instability  contribute to higher rates of auto theft. Policies that strengthen communities, reduce housing vacancy, and create economic opportunities can address the base causes of auto theft, rather than simply its symptoms. 


---
[Anime Recommender System (Python)](https://kaihansen8.github.io/3162FinalProject/){:target="_blank"}

In this project, we focused on building a content-based recommendation system. This system generates suggestions based on content that another user has previously enjoyed. By using cosine similarity, we can compare features and identify those that match a user’s interest and taste. The goal is to create a way for users to discover new anime. 
<br><br>
The github repo is located [here](https://github.com/kaihansen8/3162FinalProject/tree/main){:target="_blank"} with the final jupyter [notebook available here.](https://github.com/kaihansen8/3162FinalProject/blob/main/Final_Group_Project.ipynb){:target="_blank"}
<br>

---
[Pokémon API (R)](https://pmb-7684.github.io/ST558_Project_2/){:target="_blank"}

A project that used resting APIs at [Poké Api.](https://pokeapi.co/){:target="_blank"} The vignette helps users on how to request information on their favorite Pokémon by name or ID from a resting API.  The information includes basic stats, training information, and moves.  There is an additional option to request information about berries.  Completed exploratory analysis with visualizations using data extracted from the api.

---
[Predictive Models for Online New Popularity Data Set (R)](https://pmb-7684.github.io/ST558_Project_3/){:target="_blank"}

The purpose of this repository is to create predictive models and automating R Markdown reports. Analysis are completed on the Online News Popularity Data Set from UCI. 
<br><br>
Additional information about this data can be accessed [here](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity){:target="_blank"}


---
<img src="images/XCharlotte-Skyline.jpg" alt="Description" width="300" height="300"/>
---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
