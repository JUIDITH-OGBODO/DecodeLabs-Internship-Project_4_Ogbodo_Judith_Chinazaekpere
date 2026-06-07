Project 4 Report
Sales Performance and Revenue Insights Dashboard

Executive Summary
This project focused on transforming raw sales transaction data into meaningful business insights through effective data visualization in Power BI. The dashboard was designed to provide stakeholders with a clear view of sales performance, customer acquisition channels, order fulfilment status, and unusual sales patterns (outliers).
Using visualization techniques, key metrics were analysed to identify trends, evaluate business performance, and support data-driven decision-making. Interactive slicers were incorporated to allow users to explore the data dynamically based on order status. The final dashboard successfully communicates complex sales information in a simple and actionable format.
Dataset Overview
Metric	Value
Total Rows	1,200
Total Columns	14
Missing Values	309
Duplicate Records	0
Unique Orders	1,200
	
Data Quality Findings
•	The dataset contained 309 missing values across several fields. 
•	No duplicate transaction records were found. 
•	Each Order ID was unique. 
•	Data cleaning was performed to ensure consistency and reliability before analysis. 

Key Statistics
KPI	Value
Total Revenue	$1.26 Million
Total Orders	1,200
Quantity Supplied	3,535
Average Sales	$1,053.97
Median Sales	$823.62
Outlier Count	8
Outlier Revenue Contribution	2.14%

Order Status Analysis
Order Status	Count
Cancelled	250
Returned	247
Pending	237
Shipped	235
Delivered	231
Observation
The distribution of order statuses is relatively balanced.
However:
•	Cancelled orders represent the highest category. 
•	Delivered orders represent the lowest category. 
•	The business should investigate the causes of cancellations and returns to improve fulfilment efficiency. 

Sales Trend Analysis
Yearly Trend
Year	Revenue
2023	$552,643
2024	$480,236
2025	$231,883
Observation
Sales revenue shows a declining trend across the years.
Possible reasons may include:
•	Reduced customer demand 
•	Increased competition 
•	Marketing performance decline 
•	Incomplete data for 2025 
This trend should be monitored closely.

Monthly Trend
Highest Sales Month:
	June ($170,616)
Strong Months:
•	May 
•	March 
•	January 
Lowest Sales Month:
	September ($69,322)
Observation
Sales appear strongest during the first half of the year and begin to decline after June.
This suggests possible seasonality in customer purchasing behaviour.

Product Performance Analysis
The dashboard shows:
Top Performing Products
1.	Chair 
2.	Printer 
3.	Laptop 
Lower Performing Products
•	Desk 
•	Phone 
Observation
Furniture and office-related products generated stronger sales compared to mobile devices.

Referral Source Analysis
Referral Source	Revenue
Instagram	$275,285
Email	$261,809
Google	$250,441
Facebook	$250,411
Referral	$226,816
Observation
Instagram generated the highest revenue and appears to be the most effective acquisition channel.
Referral programs generated the lowest revenue and may require optimization.

Outlier Analysis
Using the Interquartile Range (IQR) method:
•	Outlier Count = 8 
•	Outlier Revenue Contribution = 2.14% 
Observation
Only a small number of transactions were identified as outliers.
Although they represent just 8 transactions, they contributed over 2% of total revenue.
These transactions should be monitored because they may represent:
•	High-value customers 
•	Bulk purchases 
•	Potential data anomalies 

Slicer Functionality
The dashboard includes an interactive Order Status slicer.
Users can filter the entire dashboard by:
•	Delivered 
•	Shipped 
•	Pending 
•	Cancelled 
•	Returned 
Benefit
This allows stakeholders to:
•	Analyse performance by order status 
•	Compare revenue across fulfilment stages 
•	Identify operational bottlenecks 

Business Insights
Insight 1: Instagram is the strongest customer acquisition channel.
Insight 2: June generated the highest sales revenue.
Insight 3: Sales performance has declined year-over-year.
Insight 4: Cancelled and Returned orders collectively account for a significant portion of transactions.
Insight 5: A small number of outlier transactions contribute disproportionately to revenue.

Recommendations
1. Increase Investment in Instagram Marketing: Since Instagram generated the highest revenue, allocating more advertising resources to this channel may increase overall sales.
2. Improve Order Fulfilment Processes: High cancellation and return rates suggest operational inefficiencies that should be investigated.
3. Study High-Value Outlier Customers: Understanding purchasing behaviour of high-value customers may reveal opportunities for upselling and retention.
4. Optimize Referral Programs: Referral-generated sales are the lowest among acquisition channels and should be reviewed.
5. Investigate Post-June Sales Decline: Conduct further analysis to determine whether the decline is seasonal or driven by external business factors.

Conclusion
This project demonstrates how data visualization can transform raw sales data into meaningful business intelligence. Through interactive dashboards, trend analysis, referral source evaluation, and outlier detection, stakeholders can better understand sales performance and make informed decisions. The findings highlight opportunities to improve marketing effectiveness, reduce cancellations and returns, and maximize revenue growth through data-driven strategies.

