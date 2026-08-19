# Adventure_works-production-sales-analysis
# SQL Server and Power BI integration using the Microsoft AdventureWorks database

## Project Overview

This project demonstrates an end-to-end data analysis workflow using the Microsoft AdventureWorks 2014 sample database. AdventureWorks is a fictional manufacturing and retail business dataset that provides a realistic business context for analysing production, sales and financial data.

The project involved connecting Microsoft Power BI to a SQL Server database, importing selected AdventureWorks tables, analysing the data and developing interactive dashboards and visualisations to identify trends and performance across production and sales-related activities.

The project focuses on three key areas: Production Transaction Analysis, Currency Rate Trend Analysis and Sales Order Analysis. 

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

## Production Transaction Analysis
The Production.TransactionHistory table was analysed to understand changes in transaction activity, quantity and actual costs over time.
Analysis Performed: 
1. Created a month-to-month visual showing Actual Cost across different transaction types to identify changes in production-related costs over time.
2. Analysed monthly average quantities and categorised them into three groups: High Quantity, Mid Quantity & Low Quantity. The categories were based on defined quantity ranges and presented in a table alongside the average quantity.
3. Created a visual comparing Total Actual Cost across Transaction Types to identify which transaction types contributed most to overall costs.
4. Created KPIs showing the total sum of actual cost and total quantity.

<img width="1060" height="794" alt="ProductionTransaction" src="https://github.com/user-attachments/assets/d24d2202-bd4d-426f-b370-5a04333c72b5" />

## Currency Rate Trend Analysis
The Sales.CurrencyRate table was analysed to understand currency exchange rate trends and movements over time.
Analysis Performed:
1. End-of-Day Rate & Average Rate by Year
2. Compared yearly End-of-Day Rates with Average Rates to identify changes in currency rates over time.
3. Average Rate by Currency Code
4. Analysed average exchange rates across different Currency Codes to compare currency performance.
5. Created a KPI showing the total number of days covered by the currency rate data, providing context for the period of analysis.

<img width="1058" height="794" alt="CurrencyAnalysis" src="https://github.com/user-attachments/assets/213e9e5d-2846-411a-88a0-e9cfd618424c" />
   
## Sales Order Analysis
The Sales.SalesOrderDetail table was analysed to understand sales order activity, product performance and pricing trends.
Analysis Performed:
1. Analysed the total number of products ordered across different years to identify changes in order volume.
2. Compared yearly line totals to understand changes in sales value over time.
3. Created KPIs showing number of products represented in the sales order data, average Unit Price, count of Products
4. Created a visual comparing unit prices across different Product IDs, helping to identify differences in product pricing.

<img width="1110" height="790" alt="SalesOrder" src="https://github.com/user-attachments/assets/0c2ea4f5-e072-4d2c-bdaa-5644646964a6" />

## Project Workflow
The project followed an end-to-end data analytics workflow: AdventureWorks → SQL Server → Power BI → Data Analysis → Visualisation → Dashboard
1. Imported the AdventureWorks 2014 database into SQL Server Management Studio.
2. Connected Power BI to the SQL Server database.
3. Imported the Production.TransactionHistory, Sales.CurrencyRate and Sales.SalesOrderDetail tables.
4. Explored and analysed the datasets to understand their structure and business context.
5. Created calculations and KPIs required for the analysis.
6. Developed visuals to identify trends, comparisons and performance patterns.
7. Combined relevant visuals into interactive Power BI dashboards.
8. Used the dashboards to communicate key findings from the production, currency and sales data.

## Key Skills Demonstrated
SQL Server & SSMS, SQL Data Analysis, Power BI, Data Visualisation, Dashboard Development, KPI Development, Trend Analysis, Data Aggregation, Business Data Analysis, Data Interpretation, Power BI & SQL Integration.

## Project Outcome
The project demonstrates the ability to work with a realistic relational business dataset, connect SQL Server with Power BI and transform raw data into meaningful analysis and interactive dashboards.

It also demonstrates an understanding of how different areas of business data — including production transactions, currency rates and sales orders — can be analysed to identify trends, monitor performance and support data-driven decision-making.



