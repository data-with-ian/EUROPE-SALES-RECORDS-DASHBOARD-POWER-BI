# EUROPE SALES RECORDS DASHBOARD – POWER BI

### PROJECT OVERVIEW

In this project, I analyzed a Europe Sales records dataset and developed an interactive dashboard using Power BI to visualize sales performance across various European countries.

![Europe sales records dashboard](https://github.com/user-attachments/assets/31acb058-c896-4e09-8403-97f74ae4d504)

![COUNTRIES DASHBOARD](https://github.com/user-attachments/assets/a12992d9-3acf-45c7-b49d-0fcd0c458560)



### TABLE OF CONTENTS

1.	[DATA SOURCE](#data-source)
2.	[TOOLS USED](#tools-used)
3.	[DATA PREPARATION](#data-preparation)
4.	[DATA ANALYSIS](#data-analysis)
5.	[KEY INSIGHTS](#key-insights)
6.	[RECOMMENDATIONS](#recommendations)
   
### DATA SOURCE

I sourced the dataset from Kaggle and retrieved as a CSV file.

Dataset URL: https://www.kaggle.com/datasets/mustafabayar/europe-sales-records

The dataset comprises 1331 entries and 14 columns, including:

•	Region: Geographical area within Europe where the sale was made.

•	Country: Specific country where the sale occurred.

•	Item type: Type of product sold.

•	Sales channel: Medium through which the sale was made.

•	Order Priority: Priority level assigned to the order using alphabets.

•	Order date: Date on which the order was placed.

•	Order ID: Unique identifier for each order.

•	Ship date: Date on which the order was shipped to the customer.

•	Units Sold: Quantity of items sold in the order.

•	Unit Price: Selling price of one unit of the item.

•	Unit Cost: Cost incurred to produce one unit of the item.

•	Total Revenue: Total income generated from the sale of the items, calculated as Units Sold * Unit Price.

•	Total Cost: Total cost associated with the items sold, calculated as Units Sold * Unit Cost.

•	Total Profit: Total profit from the sale, calculated as Total Revenue – Total Cost.

### TOOLS USED

##### Power BI Desktop: 
Utilized Power Query, Power View, and Power Map.

### DATA PREPARATION

In the data preparation phase, I loaded the dataset into Power BI Desktop's Power Query section and performed data cleaning and transformation.

##### Power Query:

•	Removed the "Region" column as it was redundant (only one region, Europe, was covered).

•	Added two custom columns by transforming the "Order Date" column into "Order Month" and "Order Year".

### DATA ANALYSIS

After cleaning and transforming the data, I loaded it into the Power View section for data analysis and visualization tasks. Subsequently, I created a Power BI dashboard for data presentation.

### KEY INSIGHTS

The following key insights were generated from the data analysis and visualization:

•	Total Units and Overall Cost: Total units sold from the sales were 7M and overall cost incurred to produce the items was €1.20B.

•	Overall Profit and Revenue: Total profit from the sales was €501.68M and total revenue was €1.70B.

•	Country with the Highest Overall Profit: Andorra, with €15.41M, while Monaco had the lowest overall profit at €4.80M.

•	Item with the Highest Overall Profit: Cosmetics, with €92.72M, while fruits had the lowest overall profit at €1.43M.

•	Year with the Highest Overall Profit: 2012, with €87.88M, while 2017 had the lowest overall profit at €39.00M.

•	Month with the Highest Overall Profit: January, with €52.81M, while August had the lowest overall profit at €32.76M.

•	Sales Channel with the Highest Overall Profit: Offline, with €253.71M, while Online had the lowest overall profit at €248.00M.

•	Order Priority with the Highest Overall Profit: M, with €136.96M, while L had the lowest overall profit at €114.88M.

### RECOMMENDATIONS

I developed some recommendations to the European countries to strategically enhance sales performance, optimize operational efficiency, and capitalize on opportunities identified through my thorough analysis of the Europe sales records dataset. Each recommendation aims to leverage data insights to drive informed decision-making and achieve sustainable growth in sales and profitability.

##### 1.  Allocating More Resources to High-Profit Countries and Items

•	Allocate more resources and marketing efforts towards countries and product categories that have consistently shown high profitability (e.g., Andorra for cosmetics).

##### 2. Optimize Sales Channel Strategies

Given the higher profitability of offline sales channels compared to online, consider strategies to strengthen offline sales efforts.

##### 3. Enhance Operational Efficiency

•	With a significant total cost incurred, focus on optimizing production and supply chain efficiencies to reduce costs.

##### 4. Seasonal and Monthly Analysis for Sales Planning

•	Given the variation in profitability across months (e.g., January vs. August), develop targeted marketing and sales promotions during peak months.

##### 5. Improve Order Priority Management

•	Prioritize orders with higher profitability (e.g., 'M' priority) to streamline operations and maximize overall profit margins.

##### 6. Invest in Data-Driven Decision Making

•	Continue leveraging Power BI for ongoing analysis and reporting to monitor sales performance metrics and identify emerging trends.

##### 7. Customer Segmentation and Targeting

•	Implement targeted marketing campaigns and personalized promotions to enhance customer engagement and loyalty, thereby driving sales and profitability.
