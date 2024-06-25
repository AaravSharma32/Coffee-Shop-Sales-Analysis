# Coffee-Shop-Sales-Analysis
# Data Analysis by using SQL
I cleaned and prepared a coffee shop dataset, imported it into a MySQL database, and started analyzing it based on the problem statement. Here's a summary of the steps and queries I executed:

1. I executed a query to view all the data and then began addressing the problem statement.
2. I wrote a query to calculate total sales by month, using the formula Sum(Transaction qty * Unit price).
3. I used window functions to determine the sales difference, order difference, total quantity sold difference, and growth from the previous month to the current month.
4. I found the total sales, total orders, and total quantity sold for each day. Additionally, I compared these metrics between weekdays and weekends, calculating their differences.
5. I determined the total sales, total orders, and total quantity sold by store location on a monthly basis, as well as the average daily sales using a subquery.
6. I wrote queries to find daily and hourly sales for each respective month.
# Data Visualization by using Power BI
Open Power BI Desktop, import, and load the data.
Create a new table named "Date Table" using Power Query.
Add calculated columns in the Date Table, such as Month Year, Month Name, Day Number, Week Day, Week Number, and Day of Week.
Build relationships between the Date Table and the original data table using Power Pivot for data modeling.
Write DAX queries to create an interactive dashboard.
Here are some examples of the DAX queries:
1. I created an interactive dashboard to visualize the data and uncover clear insights, making it easy to explain the findings to non-technical individuals.
2. I established key performance indicators (KPIs) for Total Sales, Total Orders, and Total Quantity Sold, and created a slicer to filter the data by month to view the respective sales, orders, and quantities for each month.
3. Using DAX queries, I visualized sales, orders, and quantity sold(MoM) growth and differences with a line chart. Additionally, I created a heatmap calendar to display date-wise total sales, orders, and quantities for a selected month using tooltips. I also used a matrix chart to show day-wise and hour-wise total sales, orders, and quantities.
4. I developed a column bar chart to illustrate monthly sales trends, with below-average sales shown in a light color and above-average sales in a dark color, separated by a line. Furthermore, I used a clustered bar chart to display total sales, orders, and quantities based on product category and the top 10 product types. I also created a column bar chart to show total sales by store location, and a donut chart to compare weekend and weekday total sales, orders, quantities sold(MoM), and their differences.

   
   
