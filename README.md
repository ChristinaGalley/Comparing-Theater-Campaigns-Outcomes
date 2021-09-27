# **Comparing-Theater-Campaigns-Outcomes**
Analysis of Theater Outcomes Based on Launch dates and Funding Goals.
---
###**Overview of Project**
---
This project entails the analysis of theater play outcomes in the setting of launch dates compared to funding goals. The purpose of this analysis is to create a context of competitor theaters' play outcomes to compare the outcome of Louise's play *Fever* to.
---
###**Analysis and Challenges**
---
To perform this analysis, I began with determining the Theater Outcomes Based on Launch Date. To do this created a stacked column line graph, as shown, based on a pivot table displaying successful, failed, and cenceled outcomes per month filered by Parent Category and Year. I then calculated the percentage of sucessful, failed and canceled outcomes using said code: . A line graph was constructed comparing the funding goal amount (x-axis) to the percentage (y-axis) of each outcome (successful failed, and canceled). One difficulty encountered was the amount of canceled donations. There were zero cancelations, so I had to use an IFERROR code as follws: to prevent an error due to the inabilty to divide by zero and instead retain the value of zero in the "percentage canceled" column.
---
###**Results**
---
######*Conslusions:*
There are two comlusions I draw concerning the theater outcomes by launch date: plays launched in the summer months, ie. May June July, are much more successful than plays launched in the other seasons/months, and an increase in failed outcomes from plays launched in the Winter months, ie. October November December. Looking at the outcomes based on goals, it can be concluded that generally the higher the goal amount, the higher the chance of outcome failure. However, there is an increase in successful outcomes aorund the 40000 range.
---
######*Limitations:*
The limitations of this analysis include the year range, countries, and particular theaters the data was taken from. This data analysis may be an accurate presentation of loical outcomes in the past, but it does not provide the most up to date information and would not be a reliabale source for determining outcomes in general of all theaters in all countries.
---
######*Additional Analysis:*
Additional representations of data to consider for further analysis include outcomes of theaters in a particular country vs launch date to determin peak seasons per location. This could be displayed by a pivot table with country filered and a line graph displaying monlthy outcomes for a single country for each of the documented years. You could determine a popssible trend from year to year between peak seasons.
