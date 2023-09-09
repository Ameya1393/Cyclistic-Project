# Cyclistic-Project

![Cyclistic logo](https://github.com/Ameya1393/Cyclistic-Project/assets/84855509/481ce457-2613-4e99-9c68-873b52b66e8e)

## Project Description:
This project provides a comprehensive description of the key milestones and actions undertaken throughout the Cyclistic Project, which I successfully completed as part of the Data Analytics Professional Certificate program.

## Scenario: 
You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of
marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your
team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will
design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your
recommendations, so they must be backed up with compelling data insights and professional data visualizations.

# AIM: The primary objective of this data analytics project is to analyze the available dataset comprehensively in order to provide insightful answers to the following three key questions:
## Three questions that will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

## Link to the Data Being used : 
1. https://divvy-tripdata.s3.amazonaws.com/index.html
2. New York BikeShare data available on BigQuery

## I answered the above-mentioned questions using these three tools:
1. Excel
2. SQL using BigQuery
3. Data Visualization

## Excel-
I opened my spreadsheet application and followed these steps:

1. I ensured that columns were made consistent and combined into a single worksheet where relevant.
2. I cleaned and transformed the data to prepare it for analysis.
3. I conducted a descriptive analysis of the data.
4. I ran calculations in one file to gain a better understanding of the data layout. Specifically, I calculated the mean of ride_length, the maximum ride_length, and the mode of day_of_week.
5. I created pivot tables to quickly calculate and visualize the data. For instance, I calculated the average ride_length for members and casual riders, as well as the average ride_length for users by day_of_week. I also calculated the number of rides for users by day_of_week.
6. I opened another file and performed the same descriptive analysis steps, exploring different seasons to make initial observations.

After working with the individual spreadsheets, I merged them into a full-year view.
Finally, I exported a summary file for further analysis.

### Important Excel Functions Used - VLOOKUP, CONCATENATE, SUMIF, COUNTA, DATE, IFERROR, MIN and MAX.

## SQL- 
I opened BigQuery and proceeded with the following steps:

1. I imported the excel sheets into the database.
2. I began by exploring the data, examining the total number of rows, distinct values, as well as calculating the maximum, minimum, and mean values for relevant columns.
3. To consolidate relevant data, I utilized JOIN statements to combine various tables into a unified table.
4. Afterward, I created summary statistics to gain a comprehensive overview of the dataset.
5. During my analysis, I identified interesting trends and saved this valuable information into a separate table for future reference.
6. I prepared two Excel sheets, referred to as "Result Tables," containing the essential Key Performance Indicators (KPIs) that I intended to visualize during the data visualization phase.

### Important SQL Functions Used - OUTER JOIN, INNER JOIN, SELECT, WHERE, GROUP BY, ORDER BY, DATE functions, CAST and ROUND.

## I have attached a few Screenshots of the SQL code used for the Project -


## Tableau Data Visualization Overview-

1. I imported Excel sheets generated from BigQuery, specifically named "Result Table1" and "Result Table 2."
2. Employing Tableau, I meticulously crafted an interactive dashboard, incorporating all pertinent Key Performance Indicators (KPIs).
3. The visualization prominently highlights trends in bike usage, encompassing daily, monthly, and yearly patterns, in addition to geographical insights displayed on a city map.
4. Furthermore, I presented seasonal trends for stations, showcasing trip counts and average trip durations for both customers and subscribers.

### Significance of the Interactive Dashboard:
This meticulously designed interactive dashboard serves as a powerful tool for project stakeholders. It facilitates a comprehensive comparison and contrast of bike usage based on critical metrics, enabling stakeholders to extract invaluable insights from the project's data.


# Conclusion: Leveraging the Interactive Dashboard to Address the Key Three Questions Using Provided Data: 
### Incorporating the Interactive Dashboard has proven to be instrumental in addressing the pivotal three questions utilizing the dataset at hand. This project furthermore helped in guiding the future of the marketing program to increase the number of overall subscribers.

### Access the Interactive Dashboard - https://public.tableau.com/app/profile/ameya.dhurde/viz/CyclisticDashboard_16906929536540/SummerTrends







