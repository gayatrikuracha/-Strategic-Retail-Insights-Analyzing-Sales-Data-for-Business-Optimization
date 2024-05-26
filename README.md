# Strategic Retail Insights: Analyzing Sales Data for Business Optimization

# Project overview
This project analyzes a retail orders dataset to extract meaningful insights such as identifying top-selling products, understanding regional sales performance, and comparing year-over-year sales growth. The objective is to provide data-driven recommendations that can help improve business decisions in the retail sector.

# Data Sources
The dataset used in this project is sourced from Kaggle. It contains detailed information about retail orders, including product details, sales, discounts, and profits.

# Tools
The following tools and libraries were used in this project:
 -  Python: For data manipulation and analysis.
 -  pandas: For data manipulation and cleaning.
 -  zipfile: For extracting files from zip archives.
 -  sqlalchemy: For database interaction.
 -  MYSQL: For storing and querying the data.
 -  Kaggle API: For downloading the dataset.
 
# Data Cleaning
- Reading Data: The dataset was read into a pandas DataFrame, with null values handled appropriately.
- Renaming Columns: Column names were converted to lower case, and spaces were replaced with underscores for consistency.
- Deriving New Columns: New columns such as discount, sale_price, and profit were derived from existing columns.
- Date Conversion: The order_date column was converted to a datetime format.
- Dropping Unnecessary Columns: Columns that were not needed for analysis, such as list_price, cost_price, and discount_percent, were dropped.

# Exploratory Data Analysis
1. Top 10 Highest Selling Products
We identified the top 10 products with the highest total sales. The sales were aggregated by product ID and ordered in descending order.

2. Top 5 Highest Selling Products in Each Region
This analysis found the top 5 products with the highest sales in each region by aggregating sales by region and product ID and then ranking the products within each region.

3. Month-over-Month Growth Comparison for 2022 and 2023 Sales
We compared the sales growth month over month for the years 2022 and 2023 by aggregating the sales by month and year and then comparing the sales for each month across the two years.

4. Highest Sales Month for Each Category
This analysis determined the month with the highest sales for each product category by aggregating sales by category and month, then ranking the months within each category.

5. Subcategory with Highest Growth by Profit in 2023 Compared to 2022
We identified the subcategory that experienced the highest profit growth from 2022 to 2023 by aggregating sales by subcategory and year and calculating the growth in sales between the two years.

# Findings
- Top-Selling Products: The analysis revealed the top products that contribute significantly to the total sales.
- Regional Performance: Certain regions had higher sales for specific products, indicating regional preferences and trends.
- Year-over-Year Growth: The month-over-month comparison showed growth trends and highlighted peak sales periods.
- Category Performance: Some categories had specific months with significantly higher sales, which can inform inventory and marketing strategies.
- Profit Growth: Identified subcategories with the highest profit growth, helping to focus on high-growth areas.

# Recommendations
- Inventory Management: Focus on stocking top-selling products and preparing for peak sales months.
- Regional Strategies: Tailor marketing and sales strategies to regional preferences.
- Growth Opportunities: Invest in subcategories and products showing significant year-over-year growth.
- Marketing Campaigns: Plan marketing campaigns around months with historically high sales to maximize impact.

# Limitations
- Data Coverage: The dataset may not cover all possible variables influencing sales, such as external market factors.
- Time Period: The analysis is limited to the years 2022 and 2023, which may not capture longer-term trends.

# References
- Dataset : [Link](https://www.kaggle.com/datasets/ankitbansal06/retail-orders)
- Python Code :[Link]
- Sql Code : [Link]
