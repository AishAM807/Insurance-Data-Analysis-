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

# Report Snapshot (Power BI DESKTOP)

<img width="961" height="496" alt="Image" src="https://github.com/user-attachments/assets/928d28d8-0762-4991-ba7b-f89efc47b240" />

- Step 11: Designed a second report page with a detailed table visualization and configured drill-through functionality, allowing users to navigate and filter records based on Policy Type.
- Step 12: Implemented Row-Level Security (RLS) based on Policy Type to ensure users can access and view only the data relevant to their assigned policy categories.

<img width="1060" height="610" alt="Image" src="https://github.com/user-attachments/assets/a9f7433e-d6cc-4ac8-9f34-6f9039aba217" />

 # Report Snapshot (Power BI DESKTOP)

<img width="973" height="497" alt="Image" src="https://github.com/user-attachments/assets/0c4c9644-4b4f-46d3-a6ab-e477609cc816" />

- Step 13: Loaded the Customer Feedback dataset and performed Sentiment Analysis to evaluate customer opinions, identify satisfaction trends, and gain actionable business insights.
- Step 14: Created a new "Sentiment Score" column using Power Query's Text Analytics functionality to measure customer sentiment.
- Step 15: Based on the calculated sentiment scores, a custom column was created to categorize customer feedback into three groups: Excellent, Good, and Needs Improvement.
- Step 16: Developed a third report view page incorporating a Word Cloud visual for customer feedback text analysis, a bar chart to represent the distribution of customers across feedback categories, and a detailed table view displaying customer names, sentiment scores, and complete feedback comments for comprehensive sentiment analysis.
 
  # Report Snapshot (Power BI DESKTOP)

<img width="1070" height="495" alt="Image" src="https://github.com/user-attachments/assets/13d5c3db-0f2d-4c18-ad4f-13709c6e9f99" />



# Insights

- Total Customer Feedback Records: 97
- Excellent Feedback: 39 customers (40.2%)
- Good Feedback: 33 customers (34.0%)
- Needs Improvement Feedback: 25 customers (25.8%)
- Total Positive Feedback (Excellent + Good): 72 customers (74.2%)
- Customers Requiring Improvement: 25 customers (25.8%)
- Difference Between Positive and Negative Feedback: 47 customers
- Excellent Feedback Exceeds Good Feedback By: 6 customers
- Excellent Feedback Exceeds Needs Improvement By: 14 customers
- Positive-to-Improvement Feedback Ratio: 2.88: 1
- Nearly 3 out of every 4 customers (74.2%) reported a positive experience.
- Approximately 1 out of every 4 customers (25.8%) identified areas needing improvement.
- The largest feedback category is Excellent, representing 40.2% of all responses.
- The smallest feedback category is Needs Improvement, representing 25.8% of all responses.
- Customer satisfaction rate (Excellent + Good): 74.2%
- Customer improvement rate: 25.8%

Executive Summary:

- 97 customer feedback records were analyzed.
- 72 customers (74.2%) provided positive feedback.
- 39 customers (40.2%) rated their experience as Excellent.
- 33 customers (34.0%) rated their experience as Good.
- 25 customers (25.8%) indicated that improvements are needed.
Overall customer sentiment is predominantly positive, with nearly three times more positive responses than improvement-related feedback.
