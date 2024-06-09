# Walmart sales Data Analysis and Visualization

### Dashboard Link : https://app.powerbi.com/groups/me/reports/f8856f17-fc31-47fa-8dd3-f90b17824656/ReportSection?experience=power-bi

## Description

Our aim with this datasets was to unravel the story hidden within the sales data and forecast the sales for the final quarter of 2012. We did found following observation

The Walmart Sales Analysis Dashboard offers a detailed examination of sales performance across Walmart stores. Through dynamic data visualization, it provides crucial metrics like total sales, top-selling products, regional sales distribution, and trends over time. Notably, it includes a predictive analytics feature for forecasting future sales based on historical data and market trends. This predictive capability equips stakeholders with valuable insights for strategic planning and decision-making, empowering them to optimize sales strategies and drive business growth.

It particulary look at how external factors like temp, distance, location etc affects sales in walmart.


### Steps followed 


**Step 1**: Load Data into Power BI Desktop

- Import the dataset from a CSV file into Power BI Desktop.

**Step 2**: Data Quality Check in Power Query Editor

- Open Power Query Editor.
- In the View tab, ensure to check "Column Distribution," "Column Quality," and "Column Profile" options under the Data Preview section.

**Step 3**: Enable Column Profiling for Entire Dataset

- Select "Column Profiling Based on Entire Dataset" to ensure comprehensive profiling beyond the default 1000 rows.

**Step 4**: Validate Data Integrity

- Confirm absence of errors and empty values in columns.

**Step 5**: Calculate Key Metrics using DAX

- Utilize DAX to calculate avg weekly sales, Region's Avg fuel price, Avg store size, Region's Avg temp.

![Screenshot 2024-06-09 125754](https://github.com/SagarKalauni/Power-BI-Projects/assets/141047160/be7c770b-e4e9-472d-9ac2-3a9df7d432aa)

**Step 6**: Create Size by store type graph


**Step 7**: Created a avg sales over years trean area chart


**Step 8**: Created a store type by sales pie chart


**Step 9**: Created a dax for holiday and non holiday transistions


**Step 9**: Created a avg temp by sale graph for all different types of store

**Step 10**: Created a avg fuel price by sale graph for all different types of store

**Step 11**: Created a avg weekly sales graph by Is holiday or Not.

**Step 12**: Created a top 10 store by sum of weekly sales.

**Step 13**: Created a sum of weekly sales by department.

**Step 14**: Finally forecasted the weekly sales for the last quater of 2012.

![Screenshot 2024-06-09 130605](https://github.com/SagarKalauni/Power-BI-Projects/assets/141047160/65d4e397-8165-49a4-b442-1fbd409c93f9)

# Key Findings



➢The biggest stores, Type 'A', have the highest maximum and average sizes.

➢The smallest stores, Type 'C', have the lowest maximum and average sizes.

➢Type 'B' stores fall in the middle in terms of size.

➢Minimum store size is similar across all types.

➢Sales increase significantly during the holiday season (November to December) every year.

➢On average, each store makes $15,981 in sales.

➢Average sales for 2012 appear lower than 2010, mainly because data for the last quarter of 2012 is missing. However, comparing the first three quarters, 2012 has higher average sales than 2010 and 2011.

➢Despite fewer holidays compared to non-holidays, average sales during both periods are similar, indicating high holiday sales for Walmart.

➢Larger stores (Type A) generally have higher sales compared to smaller ones (Type B and C).

➢Most Type C stores are located in regions with higher average temperatures.

➢Fuel prices seem consistent across all store types but show an increasing trend over the year.

➢51.11% of stores are Type A, 38.78% are Type B, and the rest are Type C.

➢Holiday season doesn't notably affect sales at Type C stores, suggesting they might be in rural areas with fewer people.

➢Department 92 is the highest-selling department at Walmart.

➢Store 20 is the top-selling store at Walmart.

➢Departments 88 to 95 and 38, 40 have notably high sales, indicating they might sell everyday items like food and groceries.

➢Some stores with high sales may be located in urban areas.

➢And more…

### Final Prediction
Our final prediction, backed by 95% confidence intervals, indicates that sales could reach a maximum of $50,965,404.847 on Nov 23. Interestingly, a quick Google search revealed that Nov 23 was Black Friday in 2012, adding more weight to our findings and making them even more logical and valid.

