# Toronto Bikeshare Data

This project aims to investigate the usage patterns and trends of bikeshare data in Toronto for the year 2018. By analyzing various variables such as trip duration, trip start time, user type, and station information, we seek to gain insights into how the bikeshare system was utilized by different user groups and identify any patterns or trends that may emerge from the data.

## Code Summary

The code, written in R, performs the following tasks:

1. Merging Datasets: The code loads multiple CSV files from a folder and merges them into a single data frame using a loop.
2. Dataset Description: The code displays the variable names in the merged data frame.
3. Tables: The code generates the following tables:
   - Trip Duration (in Seconds) Summary By User Type: This table summarizes trip duration by user type, including the number of trips, average duration, median duration, minimum duration, and maximum duration.
   - Total Trips by Month for Each User Type: This table shows the total number of trips by month for each user type.
   - Top 10 Most Popular Starting Stations: This table displays the top 10 starting stations with the highest trip volumes.
   - Trip duration More than 30 minutes and More than 45 minutes: This table presents the number of trips with a duration exceeding 30 minutes and 45 minutes, segmented by user type.
4. Visualizations: The code creates the following visualizations:
   - Line Chart of Total Trips by Hour: This visualization depicts the total number of trips by hour of the day.
   - Stacked Bar Plot of Trip Volume by User Type and Month: This visualization illustrates the total number of trips by month and user type using a stacked bar plot.
   - Heatmap of Trips by Day of the Week: This visualization shows the total number of trips by day of the week and hour of the day using a heatmap.
5. Hypothesis Testing: The code performs a hypothesis test comparing trip duration between trips taken on weekdays versus weekends.
6. Bootstrapping: The code estimates the average trip duration for casual members using bootstrapping techniques.
7. Polynomial Regression: The code conducts polynomial regression analysis to examine the relationship between the number of trips and the hour of the day.
8. Cross Validation: The code analyzes the relationship between trip duration (in hours) and the hour of the day using cross-validation techniques.

By executing this code, researchers can gain valuable insights into the bikeshare usage patterns in Toronto for the year 2018.
