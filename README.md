# Adventure_works-production-sales-analysis
# SQL Server and Power BI integration using the Microsoft AdventureWorks database

## Project Overview

This project demonstrates an end-to-end data analysis workflow using the Microsoft AdventureWorks 2014 sample database. AdventureWorks is a fictional manufacturing and retail business dataset that provides a realistic business context for analysing production, sales and financial data.

The project involved connecting Microsoft Power BI to a SQL Server database, importing selected AdventureWorks tables, analysing the data and developing interactive dashboards and visualisations to identify trends and performance across production and sales-related activities.

The project focuses on three key areas: Production Transaction Analysis, Currency Rate Trend Analysis and Sales Order Analysis. 

## Project Objective

The objective of this project was to transform raw business data from the AdventureWorks database into meaningful insights that can be used to understand production transaction activity, currency rate movements and sales performance.

The project aimed to:
Analyse production transactions to identify changes in actual costs, transaction types and average quantities over time.
Categorise monthly average production quantities into High, Mid and Low Quantity groups to make changes in production activity easier to interpret.
Analyse currency rate data to identify trends and movements in exchange rates over time and differences between currencies.
Analyse sales order data to understand product demand, sales value, product pricing and changes in sales activity over time.
Develop interactive Power BI dashboards and visualisations that communicate these findings clearly and support data-driven business decision-making.

The overall objective was therefore to demonstrate how SQL Server and Power BI can be used together to transform relational business data into actionable insights and interactive reporting solutions.

## Tools Used
### Microsoft SQL Server / SSMS
Used to:
Import and manage the AdventureWorks 2014 database.
Query and explore relational business data.
Prepare and retrieve the required datasets for analysis.
Establish the database environment used for the Power BI connection.

### Microsoft Power BI
Used to:
Connect directly to the AdventureWorks SQL database.
Import and analyse the Production.TransactionHistory, Sales.CurrencyRate and Sales.SalesOrderDetail tables.
Create calculated measures and KPIs.
Develop interactive visuals and dashboards.
Analyse trends and communicate findings through data visualisation.

## Data Cleaning

No data cleaning was necessary for this particular project. The selected AdventureWorks tables were already structured and suitable for analysis, with the required fields available in the appropriate format. Therefore, the project focused primarily on data exploration, analysis, calculation of measures and KPIs, visualisation, and dashboard development rather than performing extensive data cleaning transformations.

## Production Transaction Analysis
The Production.TransactionHistory table was analysed to understand changes in transaction activity, quantity and actual costs over time.
Analysis Performed: 
1. Created a month-to-month visual showing Actual Cost across different transaction types to identify changes in production-related costs over time.
2. Analysed monthly average quantities and categorised them into three groups: High Quantity, Mid Quantity & Low Quantity. The categories were based on defined quantity ranges and presented in a table alongside the average quantity.
3. Created a visual comparing Total Actual Cost across Transaction Types to identify which transaction types contributed most to overall costs.
4. Created KPIs showing the total sum of actual cost and total quantity.

<img width="1060" height="794" alt="ProductionTransaction" src="https://github.com/user-attachments/assets/d24d2202-bd4d-426f-b370-5a04333c72b5" />

## Outcome

The production analysis provides a clearer view of how production costs and quantities changed over time and how costs differed between transaction types. The quantity classification also makes it easier to identify periods of relatively high, medium or low production activity. These findings support the project objective of using business data to understand production activity, cost behaviour and operational performance.

## Currency Rate Trend Analysis
The Sales.CurrencyRate table was analysed to understand currency exchange rate trends and movements over time.
Analysis Performed:
1. End-of-Day Rate & Average Rate by Year
2. Compared yearly End-of-Day Rates with Average Rates to identify changes in currency rates over time.
3. Analysed Average Rate by Currency Code to compare exchange rate behaviour across different currencies.
4. Created a KPI showing the total number of days covered by the currency rate data, providing context for the period of analysis.

<img width="1058" height="794" alt="CurrencyAnalysis" src="https://github.com/user-attachments/assets/213e9e5d-2846-411a-88a0-e9cfd618424c" />

## Outcome

The currency analysis provides an overview of how exchange rates changed over the period covered by the dataset and highlights differences in average rates between currencies. The supporting Power BI visuals make these movements easier to compare and interpret, contributing to the project objective of identifying currency trends that may be relevant when analysing financial and international business activity.

## Sales Order Analysis
The Sales.SalesOrderDetail table was analysed to understand sales order activity, product performance and pricing trends.
Analysis Performed:
1. Analysed the total number of products ordered across different years to identify changes in order volume.
2. Compared yearly line totals to understand changes in sales value over time.
3. Created KPIs showing number of products represented in the sales order data, average Unit Price, count of Products
4. Created a visual comparing unit prices across different Product IDs, helping to identify differences in product pricing.

<img width="1110" height="790" alt="SalesOrder" src="https://github.com/user-attachments/assets/0c2ea4f5-e072-4d2c-bdaa-5644646964a6" />

## Outcome

The sales order analysis provides insights into changes in sales activity, sales value and product pricing. The visuals allow differences in product performance and pricing to be identified more easily. This supports the project objective of using sales data to understand sales activity, product-level performance and pricing patterns.

## Project Workflow
The project followed an end-to-end data analytics workflow:
AdventureWorks 2014 → SQL Server → Power BI → Data Validation & Cleaning Assessment → Data Analysis → Visualisation → Dashboard → Business Insights

1. Imported the AdventureWorks database into SQL Server Management Studio.
2. Connected Power BI to the SQL Server database.
3. Imported the Production.TransactionHistory, Sales.CurrencyRate and Sales.SalesOrderDetail tables.
4. Explored and analysed the datasets to understand their structure and business context.
5. Created calculations and KPIs required for the analysis.
6. Developed visuals to identify trends, comparisons and performance patterns.
7. Combined relevant visuals into interactive Power BI dashboards.
8. Interpreted the results to identify insights relating to production, currency rates and sales performance.
9. Presented the findings through interactive dashboards designed to support data-driven decision-making.
   
## Key Skills Demonstrated
### Technical Skills: 
SQL Server & SSMS, SQL Data Analysis, Microsoft Power BI, Power BI & SQL Integration, Data Visualisation, Dashboard Development, KPI Development, Data Aggregation.

### Analytical Skills:
Trend Analysis, Business Data Analysis, Data Interpretation, Performance Analysis, Comparative Analysis, Insight Generation, Data-Driven Decision-Making

## Project Outcome
The project achieved its objective of transforming raw data from the AdventureWorks database into meaningful business analysis and interactive Power BI dashboards.

The analysis provided insights into:
Production: Changes in actual costs, transaction types and production quantities over time.
Currency: Exchange rate movements over time and differences in average rates between currencies.
Sales: Changes in product order activity, sales value and product pricing.

The resulting dashboards and visualisations demonstrate the ability to take data from a relational SQL Server database, analyse it using Power BI and present the results in a clear and interactive format.

Overall, the project demonstrates how SQL and Power BI can be combined to turn raw business data into insights that help organisations understand performance, identify trends and support data-driven decision-making.



