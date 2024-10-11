# pandas_data_science_task
In this project, I used Python Pandas and Python Matplotlib to analyze and answer business questions based on 12 months' worth of sales data from an electronics store.

Data Overview  

The dataset contains hundreds of thousands of purchases.
The data is broken down by month, product type, cost, purchase address, and more.
Steps in the Project  

1. Data Cleaning
   
-Dropped NaN values from the DataFrame.
-Removed rows based on specific conditions.
-Changed data types using functions like to_numeric, to_datetime, and astype.  

2. Data Exploration  

I explored the data to answer the following business questions:

What was the best month for sales?
Determined which month had the highest sales and the total earnings.

Which city sold the most products?
Analyzed sales data by city to find the top-performing locations.

What time should we display advertisements to maximize sales?
Investigated the time of purchase to find the best times for ads.

What products are most often sold together?
Identified product pairs frequently bought together.

What product sold the most? Why?
Found the best-selling product and explored reasons for its popularity.

3. Methods and Tools Used
   
Concatenation of CSV files using pd.concat to create a single DataFrame.
String parsing using .str to create new columns.
Groupby for aggregate analysis.
Visualized results using bar charts and line graphs.
Added labels and titles to graphs for better clarity.
