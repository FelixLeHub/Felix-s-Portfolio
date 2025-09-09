# Felix's Analysis Portfolio

## About

## Table of Contents
- About
- Portfolio Projects:
  - Portfolio Project 1: Hotel Revenue Dashboard
  - Portfolio Project 2: KMeans Cluster Analysis to Segment Mall Customers For Targeted Marketing Campaign
  - Portfolio Project 3: Data Cleaning
  - Portfolio Project 4: HR Analytics: Absenteeism Dashboard
  - Portfolio Project 5: Bike Rental Store Dashboard
  - Portfolio Project 6: Project Overview Dashboard

## Portfolio Projects

### Portfolio Project 1: Hotel Power BI Dashboard

**Skills:** Data Visualization, Dashboards

**Tools:** Power BI, Microsoft SQL Server Management Studio

**Code:** 
- SQL: HotelRevenue_Dataset.sql
- Dashboard: HotelRevenue_Dashboard.png

**Dataset:** Revenue_History.xlsx

**Description:** This project is focused on analyzing and visualizing a dataset of hotel revenue over the years. It involved importing the dataset into Microsoft SQL Server Management Studio to create the data warehouse that I would link to Power BI. With Power BI, I created dashboards that tell the story of the hotel's revenue over the years.

**Objective:** Develop a database to analyze and visualize hotel booking data to answer the following questions:
  1. Is revenue growing year by year?
  2. Should the parking lot space be increased?
  3. What trends can be seen from the data?

**Results:** The dashboard reveals that revenue was increasing year by year, except in 2020 because the year hasn't ended yet. Although there is a trend indicating car space usage going up, the year to year increase are gradual and the hotel won't need to increase the parking space.
   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Portfolio Project 2: KMeans Cluster Analysis to Segment Mall Customers For Targeted Marketing Campaign

**Skills:** Exploratory Data Analysis, KMeans Algorithm, Cluster Analysis (Univariate, Bivariate, Multivariate clusters)

**Tools:** Python, Pandas, Seaborn, Matplotlib, SKlearn

**Code:** [Customer_Segmentation.ipynb](Customer_Segmentation.ipynb)

**Dataset:** [Mall_Customers.csv](Mall_Customers.csv)

**Description:** The project focused on analyzing a dataset of mall customers. The dataset contains columns for CustomerID, Gender, Age, Annual Income, and Spending Score. This project involved loading the CSV file in Python to perform exploratory data analysis (EDA) using histograms, KDE plots, box plots, and scatter plots. Then, using KMean algorithm, I perform cluster analysis for univariate, bivariate, and multivariate variables to complete the objective. Creating summary statistics and visuals to identify the details of each cluster.

**Objective:** Identify the most important shopping group based on age, income, and shopping score to assist the marketing team in forming a marketing strategy.
  
**Results:**
- Identified the most important cluster being the one with **high annual income and high spending scores**. This cluster has a **female majority**, meaning the marketing campaign should target products popular to this demographic to attract them.
- There is also an opportunity to market popular products on sale for the cluster with low annual income but high spending score.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Portfolio Project 3: Data Cleaning 2 Datasets

**Skills:** Data Cleaning

**Tools:** Python, Pandas

**Code:** 
- CustomerCall_Clean.ipynb
- Hotel_Booking_Demand.ipynb

**Dataset:** 
- Customer_List.xlsx
- Hotel_Booking.csv

**Objective:** Clean up messy call list data for future analysis

**Challenges:** It was difficult to clean and format the phone number as it had lots of different symbols and unique characters. As well as, some number has phone extention that needed to be factored into formula when standardizing format.

**Results:** Cleaned data ready for analysis

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Portfolio Project 4: HR Analytics: Absenteeism Dashboard

**Skills:** Data Visualization, Dashboards

**Tools:** Power BI, Microsoft SQL Server Management Studio

**Code:**
- SQL: Absentee_Datasheet.sql
- Power BI: Absentee_Dashboard.pbix

**Dataset:**
- Absenteeism_at_work.csv
- compensation.csv
- Reasons.csv

**Description:** The HR department requests a dashboard to be created so that they can better analyze the workforce absences. This project involves joining the 3 CSV files into one data table, but only containing the columns necessary to create the dashboard requested. After the table is prepared, it will be exported into Power BI for visualization.

**Objective:** Create visualization dashboards for analysis and insights into the workforce's absence.

**Results** What we noticed was that workers are more likely to take a leave of absence on a Monday, especially during the Spring time. Most of whom are junior position staff members. However, this can be due to the higher number of junior positions as compared to middle and senior management positions. HR should be prepared for a shortage in staff during this time and prepare accordingly.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Portfolio Project 5: Bike Rental Store Dashboard

**Skills:** Power BI Dashboard, SQL

**Tools:** Power BI, Microsoft SQL Server Management Studio

**Code:**
- SQL: Project6.sql
- Power BI: BikeShop_pbix

**Dataset:** 
- bike_share_yr_0.csv
- bike_share_yr_1.csv
- cost_table.csv

**Description:** The project consists of 3 CSV files that showcase the bike rental store's revenue for the 1st and 2nd years, as well as the cost for operating the service. Using SQL, the 3 files were joined together into a single table but only with the necessary columns needed to create the revenue dashboard. The table is then imported in Power BI for data visualization purposes.

**Objective:** Create a visualization dashboard to understand the sales revenue of he bike rental service

**Results:**

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Portfolio Project 6: Project Overview Dashboard

**Skills:** Power Bi Dashboard, SQL

**Tools:**

**Code:** 
- SQL: Project7.sql
- Power Bi: Project7_ProjectOverviewDashboard.pbix

**Dataset:** 

**Objective:** Create a visualization dashboard to understand the sales revenue of he bike rental service

**Results:**

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
