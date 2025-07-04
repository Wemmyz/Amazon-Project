# Amazon-Project
This project focuses on analysing and visualizing dataset using Microsoft Excel.
The goal is to derive key business insights related to product performance, pricing strategy and customer feedback, and present the findings through interactive Excel dashboard.
## Dataset Description
The dataset includes simulated Amazon product listings with the following fields:

•	Product_name

•	Category & Main_Category

•	Actual_price & Discounted_price

•	Discount_percentage

•	Rating

•	Rating_count (Number of reviews)
### Objectives
1.	Determine how discounts impact product ratings.
   
2. Identify top-performing products by combining rating and review count.
	
3. Analyze which categories offer the most discounts.

4.	Visualize product rating distribution.

5.	Build an Excel Dashboard to summarize and communicate insights.
### Key Metrics & Calculations

•	Discount Percentage
=1 - (discounted_price / actual_price)

•	Total Potential Revenue
=actual_price * rating_count

•	Rating_Review_Score (Weighted metric to rank products)
=rating + (rating_count / 1000)

•	Rating Bucket
Rounded to the nearest 0.5 for distribution analysis

•	Price Bucket
Categorized into ranges (e.g., 200-300, 301–400, etc.)
#### Dashboard Features
An interactive Excel dashboard was created with the following components:

•	Bar Chart – Top 5 products by combined rating & reviews

•	Column Chart – Average discount by category

•	Scatter Plot – Rating vs. Discount Percentage

•	PivotTable – For dynamic filtering by category and rating

The dashboard provides a high level summary and can be used by decision-makers to identify promotional strategies, pricing optimizations, and high-performing products.
##### Tools Used

•	Microsoft Excel for cleaning [Download here](https.//.www.microsoft.com)

o	PivotTables

o	Charts

o	Calculated Columns

o	Conditional Formatting
###### Flies Included

•	Amazon Data – Cleaned and calculated dataset

•	Amazon Pivot Table– Base analysis with pivot summaries

•	Amazon Dashboard – Final dashboard with chart

Insights Discovered

•	Products with higher discounts didn’t necessarily have lower ratings.

•	A few key products dominate in terms of both quality (rating) and popularity (reviews).

•	Some categories consistently offer higher discounts, likely as a strategy to boost sales.

•	Review count alone is not enough — combined metrics better reflect product impact.

What i learnt

•	How to clean and structure raw product data for analysis.

•	How to use Excel's visualization and data modeling tools for storytelling.

•	How to design a user-friendly dashboard that communicates insights clearly.
