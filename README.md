# Adventure_Work_PowerBI_Dashboard
Adventure Work is a leading industry delivering high quality products in Automobile platform. Leadership is interested to know about Products Sales performance. 

# Objective
Develop a Power BI Dashboard to provide immense Business Insights on their key product performances, few KPIs which guides in making informed business decisions.

# Steps
* Import: Import csv files and choose the sheets, file required to load the data.
* Power Query Editor:
    * Perform Data Cleansing by eliminating duplicates, errors. Analyze through column profiling, column distribution to ensure integrity of data.
    * Use Merge or Append queries to transform into one source of table.
    * Create conditional columns to derive Income group, Age group, etc
* Data Modeling:
    * Identify Fact and Dimension tables
    * Create a relationship (Cardinality: 1 to Many) between Fact and Dimension, sub dimension tables using Star and Snowflake Schema
* Data Reporting
    * Cards
        * To report Total Revenue, Profit, Orders, Return Rate%
        * To track the performance of Monthly Revenue, Orders, Retruns equipped with highlight section of Good/ Bad using function.
        * To determine Revenue per customer, Top Customer and their total orders and revenue generated.
    * Line Chart
        * To find the Revenue trend against the Quarter of year
        * Find the difference between total profit and adjusted profit
        * Area Chart is used to highlight the sections of performance against each quarter for Orders, Returns, Revenue, Returns%.
    * Field Parameter: Added field paramter to select dynamically on the Area Chart instead of relying on one field.
    * Table
        * To display Top 10  products along with its Orders, Revenue, Returns& - by using conditional formatting based on numbers.
        * To display Top 100 customers along with total orders and revenue.
    * Clustered Bar Chart: To identify Total Order vs Each category of products.
    * Pie Chart: To figure out the composition of Orders based on Income Level and Orders based on Occupation
    * Gauge Card: To have a eye on Monthly Orders, Revenue vs Target using functions to showcase the Good/ Bad trend.
    * Slicers: Date slicers, Total revenue or revenue per customer slicers, Zoom slicers within Line Charts are all added to enhance more interactivity.
    * Tooltip: Create custom tooltip as a report page to give quick glance on weekly orders on quarter basis.
    * Bookmarks: Utilized customized buttons as bookmarks for inter interacitivity and provide quick visual view on insights.
# Insights
    * Total revenue summed up to approximately 25M with a Profit of 10.5M
    * Revenue has boosted in the Q1 of 2022
    * Accessories category has topped in total orders placed (~17k) whilst the Bikes category yielded maximum revenue of 23.6M with ~14k orders.
    * Water Bottle - 30 oz has topped to be most ordered product with 3.9k orders.
    * Sports 100-Helmet Blue has higher return rate of 3.33%
    * Tires and Tubes sub category accounted for most ordered product type
    * Mr. Maurice Shan is the highest revenue generated customer with total revenue of $12.4k from 6 orders.
    * Average Income level group contributed to maximum order ~11.6k
    * Professional Occupation type contributed to maximum of 7.9k orders
      
      
