# Nestle Products Analysis - Sales Analysis (2018 - 2020)
This is a sales analysis of Nestle products sold in Australia.

## Introduction
I got this dataset from [10Alytics](https://www.linkedin.com/company/10alytics/) during my growth internship program.  This dataset tested my skills in data analysis and data visualization.

### Power BI Concepts Applied
- DAX Concepts: Calculated column, Calendar Table, .
- Data Modelling: Star Schema

## Problem Statement
The company wants to expand its business by adding new product lines. However, the Head of Growth and Strategy suggested that it was important to know the performance of the current products.
- What is the trend of total sales per product in the last 3 years?
- What is the monthly sales trend?
- Compare the different products based on the maximum and min revenue generated?
- Which location had the highest and lowest sales?
- Generate insights from the sales medium to help the Head of Growth take a decision?

## Data Sourcing
The data contains only a tables; Sales table of nestle product sales in different states/cities of Australia. The sales table has 18,115 Rows and 6 columns.
A Calendar table (2018-2020) was created with Date, year, month, quarter and day columns.

## Data Transformation/Cleaning
only little changes were made in this dataset because it is pretty clean.
<img of power query transformation>

## Data Modelling
Sales table connected to the calendar table resulting in star schema model. The Sales tabele is the fact table while the calendar table is the dimention table.
< img of the modelling scheme>

## Data Analysis and Visuals
### Trend of total sales per Product in the last 3 years

<IMG trend of total sales per product in the last 3 years>

### Monthly Sales Trend

<img of monthly sales trend>

### Compare the different products based on the maximum and min revenue generated?
<product of max rev>

### Location with the highest and lowest SSales?
<img of map>

### Generate insights from the sales medium to help the Head of Growth take a decision?
<img of Dashboard>

## Conclusion/Recommendation
- Most sales are made via Direct medium than online medium, since we are in the era of technology the online medium should be made easily accessible so that more sales can be made.
- Nes Cau, Nesquik Duo, and Nestle Drumstick.These products was not sold via online throughout 2020 but are sold directly. Further analysis needs to be carried out so we can find out why this happen.
- Generally more revenue is generated via the directsale(23.80Million) for the 3yrs. Nescafe generated more revenue online of over $3.1m followed by Kit Kat with over $1.9million.




