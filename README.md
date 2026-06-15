# Insurance Data Analysis 

### Dashboard Link : 


### Data Source: MSSQL SERVER 


## Problem Statement: 
The goal of this project is to analyze insurance data and develop an interactive Power BI dashboard that provides insights into customer demographics, policy status, claim amounts, and overall insurance performance. The solution helps stakeholders monitor key metrics, identify trends, and make informed business decisions through data-driven analysis.


### Steps followed:


- Step 1: Created a database named Insurancedb in Microsoft SQL Server. Using the Import Task feature, successfully imported the Insurance dataset into the MSSQL Server database for further data analysis and processing.
- Step 2: Successfully integrated SQL Server with Power BI Desktop and loaded the dataset for reporting, data modeling, and business intelligence analysis.
- Step 3: Performed data type validation and data profiling of the insurance dataset using Power Query to ensure data accuracy, consistency, and quality before analysis.
- Step 4: Implemented three slicers to facilitate data filtering based on Claim Number, Customer ID, and Policy Number. Additionally, a text box was added to prominently display the report title, "PRISM INSURANCE PVT. LTD."
- Step 5: On the first report view page, three card visuals have been added to display the total amounts for claims, coverage, and premium, and a multi-row card has been added to show the total counts by gender (male and female).
- Step 6: A ribbon chart has been added to visualize the number of claims by claim status.
- Step 7: Implemented a conditional column in Power Query to segment customers into age groups: Young (25 years and below), Young Adult (26 to 49 years), and Elder (50 years and above), enabling age-based analysis and reporting.
- Step 8: Designed a line chart to illustrate claim amounts by age group on the report dashboard, facilitating demographic-based claims analysis and trend identification.
- Step 9: Added a conditional column to determine the policy status (Active or Inactive) based on the policy end date criteria, as shown in the figure.

<img width="922" height="417" alt="Image" src="https://github.com/user-attachments/assets/5c92865e-5803-4659-b627-de1d107531d8" />

- Step 10: Added a donut chart on the first report page to visualize the distribution of policies by status, highlighting the count of Active and Inactive policies.
- Step 11: Designed a second report page with a detailed table visualization and configured drill-through functionality, allowing users to navigate and filter records based on Policy Type.
- Step 12: Implemented Row-Level Security (RLS) based on Policy Type to ensure users can access and view only the data relevant to their assigned policy categories.


