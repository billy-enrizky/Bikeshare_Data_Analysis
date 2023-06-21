# Project Title: Toronto Apartment Evaluation

As researchers, our overall research question is to investigate the usage patterns and trends of bikeshare data in Toronto for the year 2018. We aim to analyze various variables, such as trip duration, trip start time, user type, and station information, to gain insights into how the bikeshare system was utilized by different user groups, and to identify any patterns or trends that may emerge from the data. Here is a summary of what the code (Using R) does:
1.	Merging Datasets from multiple CSVs: The code loads all CSV files in a folder and merges them into a single data frame using a loop.
2.	Description of the Dataset: The code displays the names of the variables in the merged data frame.
3.	Tables: The code creates the following tables:
•	Trip Duration (in Seconds) Summary By User Type: This table summarizes the trip duration by user type, including the number of trips, average duration, median duration, minimum duration, and maximum duration.
•	Table of Total Trips by Month for each user type
•	The Top 10 Most Popular Starting Stations
•	Trip duration More than 30 minutes and More than 45 minutes: This table shows the number of trips with a duration of more than 30 minutes and more than 45 minutes by user type.
4.	Visualizations: The code creates the following visualizations:
•	Line Chart of Total Trips by Hour: This visualization shows the total number of trips by hour of the day.
•	Stacked bar plot of trip volume by user type and month: This visualization shows the total number of trips by month and user type.
•	Heatmap of trips by day of the week: This visualization shows the total number of trips by day of the week and hour of the day.
5. Hypothesis Testing: Trip duration Between Trips taken on weekdays versus weekends.
6. Bootstrapping: Estimating the average trip duration for casual members
7. Polynomial Regression: Analyzing between the number of trips and hour of the day.
8. Cross Validation: Analyzing between Trip Duration (in hour) and hour of the day
