All the data loaded from Sql data base here, we have used import method to load data to power BI,
When loading data from SQL into Power BI, we mainly considered about data cleaning that is ensure accuracy and efficiency in analysis. 
If it is any duplicate, we removed duplicates, handled some missing values, standardized data format mainly dates, corrected the data types, removed some unnecessary columns, checked some outliers (unusual data point)
In Power BI’s Power Query Editor, the tools for evaluating and cleaning data include Column Quality, Column Profile, and Column Distribution. These tools provide insights into the data quality and help identify issues such as missing values, data types, and value distributions. 
Using R visualizations in Power BI ,it comes with a few drawbacks:
Performance: R visuals can be slower to render than native Power BI visuals, especially with large datasets or complex scripts.
Interactivity Limitations: R visuals are not as interactive as standard Power BI visuals. They don’t support cross-filtering or direct interaction with other visuals.
R visuals may not render properly when exported to PDF or PowerPoint

R Dashboard

This dashboard presents two visualizations for analyzing Sales by Category and Sales by Territory:
1.	Heatmap of Sales by Category (left side):
o	This heatmap shows sales across different categories over the years 2011 to 2014.
o	Each year is represented with a shaded bar, where darker shades of blue indicate higher sales.
o	From the color gradient, it appears that sales were highest in 2013 (darker blue) and lower in 2011 and 2014.
o	This visualization helps quickly identify peak sales years for different categories, allowing for a clear comparison over time.
2.	Sales by Territory (right side):
o	This scatter plot displays sales data broken down by territory.
o	Each dot represents a sales transaction in one of the territories, and the dots are spread horizontally to show the total sales amount.
o	Territories like the United Kingdom, Southwest, Southeast, and Northwest have a higher concentration of sales points, indicating more transactions or higher sales.
o	Some territories, such as Australia and Canada, show fewer dots, suggesting lower overall sales or fewer transactions.
o	The horizontal spread of dots in some territories (e.g., United Kingdom) reaching near the $150,000 mark indicates significant sales transactions in these areas.

