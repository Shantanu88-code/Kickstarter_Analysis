# Kickstarter_Analysis
#Performing analysis on kickstarter data to analyse trends

#Overview of Project:
The project is about Louise who wants to start a crowdfunding campaign to fund her play "Fever" with an estimate of over $10,000. With the help of multiple data organised and analysed, it would help Louise to understand specific factors and trends to make her campaign successful. The dataset contains different plays with different genres or subcategories, throughout different countries. It also states the the goal amount for each play and an actual amount pledged and whether it was successful or failed or canceled.

#Analysis:
The outcome of a particular project in a particular country is categorised as "Successful", "Failed", "Canceled" and "Live". It is further divided into parent category and subcategory. Based on the data, we figure out certain trends i.e. ideal goal amount, time to launch campaign, final outcomes and help Louise to be successful. Out of all categories, we see theatre (plays) had maximum successful outcomes.
![image](https://user-images.githubusercontent.com/86980240/131529104-d78676db-f7bd-4ae8-9ada-583a68e4895a.png)

#Challenges:
In the dataset, launch dates and end dates were not clearly mentioned in a date format. It basically looks like random digits. So, it was difficult to determine dates. We had to use a formula for Unix Time stamp converter to extract exact dates and change date settings in Home tab. We can use this formula : =(((J2/60)/60)/24)+DATE(1970,1,1)

#Conclusions and findings:
As we have analysed that Theater category had most number of projects and successful outcomes, we have further analysed few factors in theater outcomes by launch dates and outcomes by goals.
Theather outcomes by launch dates:
Factor 1 : Throughout the years, for the first quarter we see a fluctuation in amount of successful projects. From April to May, we see a spike with 111 successful project campaigns and also 52 failed ones . In the second half, we see the number of successful campaigns decreasing until December while number of failed projects keep fluctuating.
<img width="307" alt="Theater_outcomes_vs_launch" src="https://user-images.githubusercontent.com/86980240/131767244-a42d04f6-1098-4a21-ae37-6c747fb6367f.png">

Factor 2 : From March to May, there were no canceled projects even though we see a steady increase in the number of successful and also failed projects.
Theater outcomes by goals: 
Even though, theater is most successful category, we see a trend in goal outcomes. With goal amount of lesss than $1000, we see highest percentage of successful projects. As the amount increases by $5000, we see that percentage starts to dip and failed percentage starts to increase until $35000 and upto $45000. With the goal amount of $45000 and above failed significantly.

#Limitations summary and recommendations : 
After analysing this data and drawing a conclusion, there are a couple of limitations to this dataset and also other recommended graphs that can be further used  
1) Project categories in different countries:
We see a chart for overall Theater outcomes. However, we can not see in which country it has been the most successful and also how it fared in different countries according to launch dates. We could use another pivot table and chart to show the countries and the difference. Also, we could use another pivot chart to draw comparisons between different plays in Theatre category and their outcomes.
2) Difference in all categories outcomes for a particular month:
After analysing theater outcomes based on launch dates, we see June has been an excellent month to launch a campaign but different categories have different successful launching dates. A pivot chart showing all categories would be helpful to draw comparisons, e.g. Music category fared better than Theater in the month of February. 

