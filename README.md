# pandas_data_science_task
In this project, I used Python Pandas & Python Matplotlib to analyze and answer business questions of 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

Started by cleaning the data. Tasks during this section include:

Drop NaN values from DataFrame.
Removing rows based on a condition.
Change the type of columns (to_numeric, to_datetime, astype).
Once I cleaned up the data a bit,  then I moved to the data exploration section. In this section I explored 5 high levels business questions related to the data:

What was the best month for sales? How much was earned that month?
Which city sold the most product?
What time should we display advertisements to maximize the likelihood of customer’s buying product?
What products are most often sold together?
What product sold the most? Why do you think it sold the most?
To answer these questions, I walked through many different pandas & matplotlib methods. They include:

Concatenating multiple CSVs together to create a new DataFrame (pd.concat)
Adding columns
Parsing cells as strings to make new columns (.str)
Using the .apply() method
Using groupby to perform aggregate analysis
Plotting bar charts and line graphs to visualize our results
Labeling the graphs
