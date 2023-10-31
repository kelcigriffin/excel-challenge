# excel-challenge

Code Sources and Locations:
For the task of dividing "category & subcategory" into two separate columns on the main Crowdfunding worksheet (Column R), I googled "pull first and last names from excel and create two columns". This was the best example I could think of to use, to help me extract data and split into 2 columns. (I picked up that phrasing from reading the google search results. I can now articulate this as "excel formula for extracting data). I took this code and modified it to fit my needs:
Step 1: Enter the formula "=LEFT(A2, FIND(" ", A2, 1) - 1)" in a blank cell (e.g., B2) to extract the first name. Step 2: Enter the formula "=RIGHT(A2, LEN(A2) - FIND(" ", A2, 1))" in another blank cell (e.g., C2) to extract the last name.
Source: [wps.com](https://www.wps.com/academy/how-to-split-first-and-last-name-in-excel-quick-tutorials-1863889/)https://www.wps.com/academy/how-to-split-first-and-last-name-in-excel-quick-tutorials-1863889/

To help me answer the statistical analysis question of "median vs mode", I googled "is mean or median better for skewed data". Google returned this information:
"For distributions that have outliers or are skewed, the median is often the preferred measure of central tendency because the median is more resistant to outliers than the mean."
Source: https://online.stat.psu.edu/stat200/lesson/2/2.2/2.2.4/2.2.4.1#:~:text=For%20distributions%20that%20have%20outliers,to%20outliers%20than%20the%20mean.

Additionally, I consulted our course materials several times in order to remind myself how to build charts, how to write efficient formulas, and how to interpret the info last excel sheet "Stats Summary", so I could properly answer questions. I think inserting a box plot was the correct way to visualize data and determine the outliers?
