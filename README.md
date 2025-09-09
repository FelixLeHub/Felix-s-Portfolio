# Felix's Analysis Portfolio

## About

## Table of Contents
- About
- Portfolio Projects:
  - Hotel Revenue Dashboard
  - KMeans Cluster Analysis to Segment Mall Customers For Targeted Marketing Campaign
  - Data Cleaning
  - HR Analytics: Absenteeism Dashboard
  - Bike Rental Store Dashboard
  - Project Overview Dashboard

## Portfolio Projects

### Hotel Power BI Dashboard

**Skills:** Data Visualization, Dashboards

**Tools:** Power BI, Microsoft SQL Server Management Studio

**Code:** 
- SQL: [HotelRevenue_Dataset.sql](HotelRevenue_Dataset.sql)
- Dashboard: [Hotel_Revenue_Dashboards.pbix](Hotel_Revenue_Dashboards.pbix)
- Dashboard Picture: [HotelRevenue_Dashboard.png](HotelRevenue_Dashboard.png)

**Dataset:** Revenue_History.xlsx

**Description:** This project is focused on analyzing and visualizing a dataset of hotel revenue over the years. It involved importing the dataset into Microsoft SQL Server Management Studio to create the data warehouse that I would link to Power BI. With Power BI, I created dashboards that tell the story of the hotel's revenue over the years.

**Objective:** Develop a database to analyze and visualize hotel booking data to answer the following questions:
  1. Is revenue growing year by year?
  2. Should the parking lot space be increased?
  3. What trends can be seen from the data?

**Results:** The dashboard reveals that revenue was increasing year by year, except in 2020 because the year hasn't ended yet. Although there is a trend indicating car space usage going up, the year to year increase are gradual and the hotel won't need to increase the parking space.
   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### KMeans Cluster Analysis to Segment Mall Customers For Targeted Marketing Campaign

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
### Data Cleaning 2 Datasets

**Skills:** Data Cleaning

**Tools:** Python, Pandas

**Code:** 
- Dataset 1: [CustomerCall_Clean.ipynb](CustomerCall_Clean.ipynb)
- Dataset 2: [Hotel_Booking_Clean.ipynb](Hotel_Booking_Clean.ipynb)

**Dataset:** 
- Dataset 1: [Customer_List.xlsx](Customer_List.xlsx)
- Dataset 2: [Hotel_Booking.csv](Hotel_Booking.csv)

**Objective:** Clean up messy call list data for future analysis

**Challenges:** It was difficult to clean and format the phone number as it had lots of different symbols and unique characters. As well as, some number has phone extention that needed to be factored into formula when standardizing format.

**Results:** Cleaned data ready for analysis

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### HR Analytics: Absenteeism Dashboard

**Skills:** Data Visualization, Dashboards

**Tools:** Power BI, Microsoft SQL Server Management Studio

**Code:**
- SQL: [Absentee_dataset.sql](Absentee_dataset.sql)
- Dashboard: [Absentee_Dashboard.pbix](Absentee_Dashboard.pbix)
- Dashboard Picture: [Absentee_Dashboard.png](Absentee_Dashboard.png)

**Dataset:**
- [Absenteeism_at_work.csv](Absenteeism_at_work.csv)
- [compensation.csv](compensation.csv)
- [Reasons.csv](Reasons.csv)

**Description:** The HR department requests a dashboard to be created so that they can better analyze the workforce absences. This project involves joining the 3 CSV files into one data table, but only containing the columns necessary to create the dashboard requested. After the table is prepared, it will be exported into Power BI for visualization.

**Objective:** Create visualization dashboards for analysis and insights into the workforce's absence.

**Results** What we noticed was that workers are more likely to take a leave of absence on a Monday, especially during the Spring time. Most of whom are junior position staff members. However, this can be due to the higher number of junior positions as compared to middle and senior management positions. HR should be prepared for a shortage in staff during this time and prepare accordingly.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Bike Rental Store Dashboard

**Skills:** Power BI Dashboard, SQL

**Tools:** Power BI, Microsoft SQL Server Management Studio

**Code:**
- SQL: [Bikeshop_datasheet.sql](Bikeshop_datasheet.sql)
- Dashboard: [BikeShop_Dashboard.pbix](BikeShop_Dashboard.pbix)
- Dashboard Picture: [BikeRental_Dashboard.png](BikeRental_Dashboard.png)

**Dataset:** 
- [bike_share_yr_0.csv](bike_share_yr_0.csv)
- [bike_share_yr_1.csv](bike_share_yr_1.csv)
- [cost_table.csv](cost_table.csv)

**Description:** The project consists of 3 CSV files that showcase the bike rental store's revenue for the 1st and 2nd years, as well as the cost for operating the service. Using SQL, the 3 files were joined together into a single table but only with the necessary columns needed to create the revenue dashboard. The table is then imported in Power BI for data visualization purposes.

**Objective:** Create a visualization dashboard to understand the sales revenue of he bike rental service
- Can the service increase its service pricing?

**Results:** 
From the dashboard, the data is telling us that even though the service price had increased from 2021 - 2022, demand also increased correspondingly at an even higher percentage increase. This gives us a positive elasticity, meaning that the rental service can increase pricing for the following year as well.

Conservative increase: Considering the substantial increase last year, a more conservative increase might be prudent to avoid hitting a price ceiling where demand starts to drop.
An increase in the range of 10-15% could test the market's response without risking a significant loss of customers.
Price Setting:
- If the price in 2022 was $4.99, a 10% increase would make the new price around $5.49
- A 15% increase would set the price at approximately $5.74

Recommendation Strategy:
- Market Analysis: Conduct further market research to understand customer satisfaction, potential competitive changes, and the overall economic environment. This can guide whether
leaning towards the lower or higher end of the suggested increase.
- Segmented Pricing Strategy: Consider different pricing for casual vs registered users, as they may have different price sensitivities.
- Monitor and Adjust: Implement the new prices, but be ready to adjust based on immediate customer feedback and sales data. Monitoring closely will allow you to fine-tune
your pricing strategy without committing fully to a price that might turn out to be too high.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Project Overview Dashboard

**Skills:** Power BI Dashboard, SQL, Data Organization

**Tools:**

**Code:** 
- SQL: [ProjectOverviewDashboard_datasheet.sql](ProjectOverviewDashboard_datasheet.sql)
- Dashboard: [ProjectOverviewDashboard.pbix](ProjectOverviewDashboard.pbix)
- DashboardPicture: [ProjectOverviewDashboard.png](ProjectOverviewDashboard.png)

**Dataset:**
- [completed_projects.csv](completed_projects.csv)
- [departments.csv](departments.csv)
- [employees.csv](employees.csv)
- [Head_Shots.csv](Head_Shots.csv)
- [project_assignments.csv](project_assignments.csv)
- [projects.csv](projects.csv)
- [upcoming projects.csv](upcoming projects.csv)

**Description:** This project focuses on creating visual dashboards for analysis. It requires organizing and combining the 5 CSV files into one structured table accessible for reporting and data visualization. The goal of the dashboard i to help manage the workforce, to better understand the financial risks of each project, and to monitor the project health more effectively.
**Note:** The department budgets are set at 2-year intervals.

**Objective:** 
- Create a visualization dashboard to understand the sales revenue of the bike rental service
- Identify departments and projects in the red. Understand which departments or projects are over budget or underperforming.
- Can a year's budget cover the project expense?

**Results:** 

Finalizing the dashboard revealed that only one project within the HR department is in the red by -$25,000. It is expected that all other projects' budgets will be in the clear with just a year's department budget.
Recommendation:
- Fund Reallocation: Although the HR department project is expected to go over budget, other departments are expected to have remaining capital after their project that can be redistributed to assist the HR department.
- Re-evaluate project scope: Determine if there were features that the project can cut back on to remain within the department yearly budget, or if the project schedule could be delayed to the following year to raise more capital for the project.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
