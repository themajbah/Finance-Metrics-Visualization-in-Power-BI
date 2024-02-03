# Finance-Metrics-Visualization-in-Power-BI

Project Scope:
This analysis focuses on the Financial Performance Metrics of a leading manufacturer and exporter of computer accessories, operating in over 25 countries.
 The dataset comprises a largel SQL database, including a Fact table of transactional data  of five years , from 2018 to 2020, having 7 million transactional records. 
Additional dimensional tables were obtained for descriptive purposes.

Challenge:
The primary challenge involved preparing the data for visualization that will give the right insightful perspective of business. 
Building Data Model.

ETL:
-Extract, Transform, Load (ETL) processes. I extracted the data from MySQL and performed transformations in Power Query.

M-Query:
utilized the M Query to clean the data. The data, initially in a calendar form, required M Query for handling null values, redundant data, and data trimming and conversion data type.

Data Model:
I developed a data model  building star schema connecting Fact Table with dimension table.


DAX:
Significant emphasis was placed on Data Analysis Expressions (DAX) functions. 
 DAX functions is used such as SUM, SUMEX, DIVIDED, CALCULATE, SWITCH, SELECTEDVALUES, IF, HASNOVALUE, and MAX,

 Dax Code
 
Project Outcomes:
- The company is experiencing rapid growth in terms of operations and gross margin but is simultaneously facing a decline in net profit. 
- To understand the reasons behind the declining net profit, I generated a financial report- that can be customized by product or market or segment. User can get the insight from any perspective they need.
- I identified the solution to the company's substantial expenditure on operating costs and pinpointed annual losses.
- Additionally, I identified the top five markets with losses, suggesting areas where the company should focus its efforts.

Project link : (https://github.com/themajbah/Finance-Metrics-Visualization-in-Power-BI/blob/main/Finance%20Performance%20Project%20(1).pdf)
Dashboard Link: https://app.powerbi.com/groups/e7729ff6-6730-4bb7-b3d3-b109e9c6ffc9/reports/6c1b3d43-df4c-42f8-905d-5e115904ca73/ReportSection605a3cc59430e5e3cd4a?experience=power-bi
