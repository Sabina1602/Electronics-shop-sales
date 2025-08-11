**#Data Cleaning and Preparation**
I began the project by addressing data quality issues, specifically missing values across multiple categories. I first identified and counted these missing values using the **COUNTIF() function**. Following this, I performed several data transformations:
1. Standardized data formats for all values.
2. Applied **conditional formatting** to the order status column for better visualization.
3. Used the **Text to Columns** feature to separate first and last names.
4. Extracted the month from the date column using the **TEXT() function**.
5. Calculated the total profit and profit after discount.

To ensure accurate analysis, I created a new table that excluded missing values and inserted a new column for final profit, which accounted for returns and cancellations. I then used a combination of the **XLOOKUP() and UNIQUE()** functions to calculate the average customer feedback.

**#Sales and Profitability Analysis**
I conducted a comprehensive sales analysis using PivotTables and supporting visualizations.
**1. Top and Worst Sellers:** I identified the top and worst-performing sellers, factoring in returns and cancellations, and visualized the results with a chart.
**2. Monthly Sales Trends:** I analyzed the number of orders placed each month, supported by a line graph to show trends over time.
**3. Regional and Segment Performance:** I determined which segments and regions were most profitable, using a chart to provide a clear understanding of where to focus future efforts.

**#Profitability analysis**
For the profitability analysis, I focused on calculating the net income and the final income after accounting for returns and cancellations. Using a PivotTable, I discovered that the accessories category was ultimately more profitable. This finding was a key insight, as initial observations (before accounting for order status) had suggested that electronics were the better-performing category.
