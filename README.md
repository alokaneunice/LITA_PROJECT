# LITA_PROJECT

[PROJECT OVERVIEW](#project-overview)

[DATA SOURCE](#data-source)

[TOOLS USED](#tools-used)

[EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)

[CALCULATING KEY METRICS](#calculating-key-metrics)

[EXCEL VISUALIZATION](#excel-visualization)


### PROJECT TITLE: SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE
### PROJECT OVERVIEW
The sales performance of a retail store using the provided sales data will be analyzed. The goal is to uncover key insights, such as top-selling products, regional performance, and monthly sales trends, and to present these findings in an interactive Power Bl dashboard.

### DATA SOURCE
The data used was provided by the Incubator Hub for LITA project. LITA is an acronym for LADIES IN TECH AFRICA, an initiative to empower women in the Technological ambience.
### TOOLS USED
- Microsoft Excel for data cleaning and analyses. [Download Here](www.microsoft.com)
- SQL for querying data
- Power BI for data visualizations
### EXPLORATORY DATA ANALYSIS
  1. Open the "LITA Capstone Dataset.xlsx" file in Excel.
     -  Highlight all the data, sort the data in descending or ascending order.
     - Using Conditional Formatting, check for the number of missing or blank cells within the specified range.

  2. Create Pivot Tables to display:
     - Total Sales by Product
     - Total Sales by Region
     - Monthly Sales Trends
  ### CALCULATING KEY METRICS
  1. Average Sales per product: where Total Sales is calculated as "quantity*unitprice"
     ```
     =AVERAGEIF(C2:C50001, "Shirt", H2:H50001)
     =AVERAGEIF(C2:C50001, "Shoes", H2:H50001)
     ```
  2. Total Revenue by Region: where Revenue is calculated as "quantity*unitprice"
     ```
     =SUMIF(D2:D50001, "North", H2:H50001)
     =SUMIF(D2:D50001, "South", H2:H50001)
     ```
### EXCEL VISUALIZATION
![lita sales datapng](https://github.com/user-attachments/assets/a1110135-cfeb-4553-ae22-ce4e87415468)

