# Stock-Analytics-KPI-
A Semi-automated stock analytics dashboard (Just put a Financial Data)

## Objective
My goal here is to reduce the hassle involved in Financial Analysis of a business, by helping the analyst focus on the important components at a glance, so he could perform root cause analysis on the KPIs that are below the required benchmark while at same time noting the healthy factors of the company by looking at KPI above the benchmark.

## Process
Here are the various stages or process involved to achieve the final KPI measures.

### Input
Input hardcoded financial data (Balance sheet, Income statement and Cashflow statement) on at the specified components on the Financial Data sheet. In this case, Netflix (Ticker symbol: NFLX) financial data is inputted on the various items specified on each statement.  


### Staging
This stage works with automated sheet (no input from the Analyst is required in this sheet). Here, Excel Index and Match Formulas takes the required components from the Financial Data sheet. The specified components are calculated to get the various KPI. 
Eg for Current ratio, Index and match formulas lookup for Current Assets and Current liabilities from the financial data sheet and perform calculations on them to get the Quick Ratio KPI. 

### KPI
Here, each KPI measure is linked to the calculated components in the staging sheet.  And Conditional Formatting uses predetermined rules to indicate whether a KPI is above or below the specified benchmark (Green color indicator for a healthy/above benchmark, and red color indicator for poor/unhealthy benchmark).
