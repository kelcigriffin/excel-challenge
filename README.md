# excel-challenge
# Crowdfunding Report:
•  Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
1.	Based on data from the years 2010-2020, completed crowdfunding campaigns have a success rate of 57%.
2.	The most common category of campaign falls under “theater”, whose success rate is 54.6%,  but the most successful campaign category is “film & video” with a success rate of 57%.
3.	July is the most popular time to start a crowdfunding campaign, and has the highest number of successful campaigns.
•	What are some limitations of this dataset? 
Our current data shows us counts, instead of percentages. We can compare to understand popularity and competition with other campaigns, but it does not show us the percentages we’d need to understand how competitive or successful one category is, vs another of a different sample size. 
Additionally, including live campaigns in the total count throws off the stats for successes and fails.
•	What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
It would be beneficial to create pivot tables and charts to display the percentage of campaigns that succeed, broken down by category and sub category. This would help further specify the most successful types of campaigns. Contrary to that, we could use the same types of tables and charts to see the least successful categories, least popular categories, and least successful/popular months. This way, if we uncover an unpopular timeframe with a high rate of success, we can recommend starting a campaign during that time so there is less competition. 
STATISTICAL ANALYSIS:
Median is a better way to summarize the data, because there are significant outliers present in both categories ("successful" and "failed"). The median will give us a more accurate look at the trends, because it is influenced less by the outliers than a strict average (mean) would be. 

Successful campaigns appear to have more variability. This makes sense to me, because there are significantly more backers in the total pool of successful campaigns in comparison to failed campaigns. 
	
	

# Code Sources and Locations:

For the task of dividing "category & subcategory" into two separate columns on the main Crowdfunding worksheet (Column R), I googled "pull first and last names from excel and create two columns". This was the best example I could think of to use, to help me extract data and split into 2 columns. (I picked up that phrasing from reading the google search results. I can now articulate this as "excel formula for extracting data). I took this code and modified it to fit my needs:
Step 1: Enter the formula "=LEFT(A2, FIND(" ", A2, 1) - 1)" in a blank cell (e.g., B2) to extract the first name. Step 2: Enter the formula "=RIGHT(A2, LEN(A2) - FIND(" ", A2, 1))" in another blank cell (e.g., C2) to extract the last name.
Source: [wps.com](https://www.wps.com/academy/how-to-split-first-and-last-name-in-excel-quick-tutorials-1863889/)https://www.wps.com/academy/how-to-split-first-and-last-name-in-excel-quick-tutorials-1863889/

To help me answer the statistical analysis question of "median vs mode", I googled "is mean or median better for skewed data". Google returned this information:
"For distributions that have outliers or are skewed, the median is often the preferred measure of central tendency because the median is more resistant to outliers than the mean."
Source: https://online.stat.psu.edu/stat200/lesson/2/2.2/2.2.4/2.2.4.1#:~:text=For%20distributions%20that%20have%20outliers,to%20outliers%20than%20the%20mean.

Additionally, I consulted our course materials several times in order to remind myself how to build charts, how to write efficient formulas, and how to interpret the info last excel sheet "Stats Summary", so I could properly answer questions. I think inserting a box plot was the correct way to visualize data and determine the outliers?

I followed the link provided in the challenge in order to help me create the "Date Created Conversion" and "Date Ended Conversion" columns (N and O) in the main Crowdfunding sheet.
Source: https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html
