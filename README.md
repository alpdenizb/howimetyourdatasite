# IE 421 - US Flight Data Analysis
### How I Met Your Data - Team Members
- Alp Deniz Batuhan 123203096
- Emir Buğra Çakır 123203102
- Beste Eren 122203049
- Tuana Şen 122203052
### Data
We used US Flight Delays and Cancellations Data of 2015 by the DOT.
Link: https://www.kaggle.com/datasets/usdot/flight-delays
### How Did We Prepare the Data?
We first follow this procedures to ensure our data is ready.
### Fixing Airport Names: We fixed the airport names for October beacuse they were shown as letters.
### Cleaning: We remove the flights with no information and cancelled flights.
### Narrowing Scope: We focus on top 10 major US hubs to catch the most important trends.
### Time Standartization: We chahnged flights times clock format to 24 hour clocks. This way we could see the trends or busy times easily.
# Research Questions
### Q1-How does an initial departure delay in the morning amplify throughout an aircraft's daily 
rotation?
### Q2-How do temporal features (time of day, day of week, and seasonality) correlate with operational 
congestion at major U.S. hubs?
### Q3-To what extent can the variation in Arrival Delay (minutes) be explained by key operational 
variables using Linear Regression Analysis?
# Our Analyzed Modules
### 1-Interactive Airport Dashboard
We can see monthly airport congestion for each major US hub.
### 2-Heatmap of The Delay Propogation
Using heatmap we couuld analyze delay propogation through flights.We used  flights with more than rotations because the data structure becomes meaningful under this circumstances.
### 3-Flight Congestion Analysis
In our third module we used jointgrid to analyze the time relations between the day of the week and the day hours.We used hexbins instead of hexbins because our data is huge so using scatter plot desn't show significant results.
### 4-Predictive Model
We used linear regression model to predict how arrival delay changes due to departure delay.Our regression model can show the variance of the actual delays with 96 percent significance.
# Project Results
### Afternoon Stress
Our congestion analysis showed that aviation network reaches it's peak at 14.00-19.00. Passengers who fly this hours have more chance to get effected by delay more than other hours.
### Major Hub's Congestion Performance
Top hubs in the analysis (ATL and ORD) shows more stable congestion performance rather than other US hubs.Even if their traffic density are high they can operate well.
### Snowball Effect 
In our analysis a 30 minute of small delay generally turns into bigger delays at the end of the day.The system can not always tolerate this small delays.

### Website Link

