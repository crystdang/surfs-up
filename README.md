# Module 9 Challenge: Surfs Up Analysis
## by Crystina Dang using Python v3.9.12

### Overview of the analysis: 

The purpose of this analysis was to convince the the investor, W.Avy, that the surf and shake shop in Oahu would be an ideal location by reviewing the weather patterns of the past, specifically June and December.

### Results: 

*The following image provides the summary statistics of all the of the June temperatures recorded in Oahu:*
![This is an image](https://github.com/crystdang/surfs-up/blob/main/Images/June_temps.png)


*The following image provides the summary statistics of all the of the December temperatures recorded in Oahu:*
![This is an image](https://github.com/crystdang/surfs-up/blob/main/Images/Dec_temps.png)


The three key differences of the two months are:
1.
2.
3.

### Summary: 

Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)




### Summary: 
**How many roles will need to be filled as the "silver tsunami" begins to make an impact?**

*The following image provides the total number of retiring titles using SUM() from the retiring_titles table:*
![This is an image](https://github.com/crystdang/Pewlett-Hackard-analysis/blob/main/Images/total_retiring.png)


As shown above, **72,458** roles will need to be filled to maintain the company's current needs.
Most of the retiring employees are senior titles, so the promotion of (junior) Engineers and (junior) Staff and hiring for the junior positions should be consider.


**Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?**

*The following image provides the total of mentorship elibile titles using COUNT() and GROUP BY from the mentorship_eligibility table:*

![This is an image](https://github.com/crystdang/Pewlett-Hackard-analysis/blob/main/Images/total_eligible.png)


As shown above, **1,549** employees are eligible to participate in the mentorship program. As this table was created using only one birth year, the number could be considerably higher if other years or merit was additionally considered.


*The following image provides the breakdown of current active titles using COUNT() and GROUP BY where to_date is '9999-01-01' of from the titles table:*


![This is an image](https://github.com/crystdang/Pewlett-Hackard-analysis/blob/main/Images/current_titles.png)

To create a fuller picture, the above image provides a view into the current totals and reveals that the management team will be greatly reduced and this should be on high priority.
