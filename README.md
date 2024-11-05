# Lita_class_Documentation

### Project Title: HR Attrition Data
---
[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](*#data-visualization)

### Project Overview
---
This data analysis aims to generate insight into  Hr attrition  over the past year. By analysing the various parameters in the data received, we seek to gather enough insight to make reasonable decisions and determine our data's best performance. 

### Data Sources
---
The primary data source used here is Data Sales.xlsx, which is open data that can be freely downloaded from an open source online or any other data repository site.

### Tools Used

- Ms. Excel (for data Cleaning and Analysis )
- SQL Server ( For Querying Data and Analysis)
- Power BI (for Data Visualization)
### Data Cleaning and Preparation

In the initial phase of the Data Cleaning and preparation, the following actions were performed:
1. Data loading and inspection
2. Handling empty variables
3. data cleaning and formatting
   
### Exploratory Data Analysis

EDA involved exploring of the Data to answer some questions about the Data such as:
- What is the Attrition Count by Department?
- What is the Total Number of Current Employees?
- What is the Attrition rate?
- What is the Average Age of Employees?
- The total number of Employee?
- Total Number of Attrition count?
- What is Attrition count by the Education field?
- The Sum of Attrition count by Gender?
### Data Analysis
---
---SQL
-- The total sales for each product category--

SELECT [Product] , SUM([Total Sales]) AS Total_Sales
FROM[dbo].[SalesData$]
Group By Product
----

---The number of sales transactions in each region--
SELECT [Region] , count( [Total Sales]) AS Total_Sales_Count
FROM[dbo].[SalesData$]
Group By [Region]
---
### Data Visualization
![hr attrition data](https://github.com/user-attachments/assets/5d1eaba7-9694-4b61-8863-2ae338b26487)

![hr data](https://github.com/user-attachments/assets/1b2d7032-10b8-40ac-98ff-3a58f871eb06)


