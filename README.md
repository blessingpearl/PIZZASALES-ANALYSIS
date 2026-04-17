# PIZZA SALES ANALYSIS (first project)- POWERBI
## TABLE OF CONTENT
#### Project Overview
#### Tools And Technology
#### Datasets overview
#### Data Cleaning And Power BI Dashboard
#### Key Insights
#### Recommendations
#### Future Works 
#### Repository Structure

### Project  Overview
A pizza sales dataset was analyzed to track daily transactions, helping the restaurant understand customer preferences and optimize production. The goal was to minimize food waste by identifying top-selling pizzas (by size and type), peak sales periods, and revenue drivers. Using Power BI for data cleaning, transformation, and visualization, the analysis revealed insights into bestsellers, highest revenue streams, and ordering patterns.

### Tools And Technology
* Power Bi

Dataset Overview
Column:
pizza_id, order_id, pizza_name_id, quantity,order_date, order_time, unit_price, total_price, pizza_size, pizza_category, pizza_ingredients, pizza_name.

### Data Cleaning 
1. Extract, transform and Load in Power BI
2. Changed data type
3. Removed unwanted columns
4. Created a calender table using query editor for the purpose of creating days of week and name of days before loading datasets.

### Data Modeling
1. Pizza Table - Fact Table
2. Calender Table - dimension Table
3. Relationship connection between both is the Order Date column Pizza Sales table and Date column on the calender table

DAX measure:
1. Revenue = SUMX(quantity * unit price)
2. Total order = COUNT(order_id)
3. Average order =AVERAGE(order_id)

### Data visualization
Visuals used are; card, clustered bar chart and line chart

1. Card displays the 3 KPI which are, total order, revenue, and average order
2. Clustered bar chart displays the total order y pizza size, total order by pizza category, revenue by pizza category.
3. Line chart displaystotal order by time interval, total order by name of weekdays
   [view here]


 
