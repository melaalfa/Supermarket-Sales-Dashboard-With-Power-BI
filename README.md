# Exploratory Data Analysis on a Supermarket Sales with Power BI


## Problem Statement:
The growth of supermarkets in most populated cities are increasing and market competitions are also high. Supermarkets play a critical role in the retail sector, providing essential goods and services to customers. Effective decision-making based on data can help businesses optimize operations, understand customer behavior, and improve profitability. 
The objective is to perform Exploratory Data Analysis (EDA) on the supermarket sales dataset to uncover actionable insights that can help the supermarket management make data-driven decisions. Insights could focus on identifying high-performing branches, understanding customer preferences, analyzing payment methods, and determining factors influencing sales and customer ratings.

## Data Understanding :
Invoice id : Computer generated sales slip invoice identification number

Branch : Branch of supercenter (3 branches are available identified by A, B and C).

City : Location of supercenters

Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.

Gender : Gender type of customer

Product line : General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel

Unit price : Price of each product in $

Quantity : Number of products purchased by customer

Tax : 5% tax fee for customer buying

Total : Total price including tax

Date : Date of purchase (Record available from January 2019 to March 2019)

Time : Purchase time (10am to 9pm)

Payment : Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)

COGS : Cost of goods sold

Gross margin percentage : Gross margin percentage

Gross income : Gross income

Rating : Customer stratification rating on their overall shopping experience (On a scale of 1 to 10).

## Data Cleaning
Before diving into visualizations, we must ensure our data is clean and ready for analysis. Data cleaning involves checking for and handling missing values, correcting data types, and fixing any inconsistencies.
1.	Checking for Missing Values: We inspect each column for missing values or anomalies. Missing or incorrect data can skew our analysis and lead to inaccurate insights.
2.	Correcting Data Types: We ensure each column has the correct data type. For instance, the date column should be in date format, unit price and total sales should be in decimal format, and categorical data such as customer type and gender should be in text format.
3.	Fixing Date Formats: A common issue in datasets is inconsistent date formats. In our case, we need to replace slashes with dashes and ensure all dates are in a standard format.

## Data Visualization
Power BI offers a variety of visualization tools, from basic charts to advanced analytics tools.
1.	Categorical Data Visualization : For categorical data such as customer type, date, and gender, slicer and card are effective. These visualizations help us understand the distribution of different categories.
2.	Time Series Analysis : stack area charts are excellent for analysing prrofit trends over time. We can visualize profit sales trendline from January to march 2019
3.	Product Performance : Funnel, donut charts and pie charts can help us compare the performance of different product lines, rating poduct, sales by branch and payment category. We can identify top-selling products and underperforming categories.

## Conclusion of the Exploratory Data Analysis (EDA) on Supermarket Sales using Power BI:
The analysis of the supermarket sales dataset reveals valuable insights that can guide management in making data-driven decisions to optimize operations and improve customer satisfaction. Here are the key findings based on the Exploratory Data Analysis :
1.	Customer Demographics and Purchase Behavior:
   
o	Gender and Customer Type: The majority of customers were members using the store's membership card are women although the difference is not significant, indicating a strong loyalty base. Gender-wise, there was a balanced distribution, which suggests that the supermarket appeals equally to both male and female customers.

3.	Branch Performance:

o	Branch Comparison: From the funnel and pie charts, we observe that Branch A generates the highest revenue, followed by Branch B and C. Branch A also has the highest number of loyal (member) customers, which could imply the success of its membership programs or customer service quality.

4.	Product Line Performance:
   
o	Top and Underperforming Products: The donut charts reveal that categories such as "Food and Beverages" and "Electronic Accessories" are top-sellers, whereas categories like "Home and Lifestyle" "Sports and Travel,"  and "Healty and Beauty" perform below expectations. Focusing on these underperforming categories through targeted marketing campaigns or product adjustments could help increase sales in these areas.

o	Unit Sales: Products in high-demand categories tend to have higher sales volumes and a significant customer base, whereas low-performing products might benefit from promotional efforts or repositioning.

6.	Sales and Profitability:
   
o	Profit Trends: Using time-series analysis, it is evident that profitability aligns with the overall sales trend. Sales and profits generally follow similar patterns, with notable spikes in profits during certain months.

o	Payment Methods: A breakdown of payment methods shows a significant preference for e-wallets and cash over credit cards, suggesting that customers are more inclined to use digital payment methods. This could inform future investment in digital payment systems or special offers targeting credit card users.

8.	Customer Ratings:
   
o	Rating Analysis: Customer satisfaction is generally high, with most ratings falling between 6 and 7. However, there are a few outliers with very low ratings, indicating areas for improvement, such as customer service or product quality.

10.	Tax and Cost Analysis:
    
o	Impact of Taxes on Total Sales: Since a 5% tax is applied to each transaction, the total price paid by customers reflects this, and the analysis shows that customers tend to accept the tax without significant impact on their purchasing behavior.

o	Gross Profit Margin : The dataset also reveals insights into the supermarket’s gross profit margin percentages. These metrics are crucial for understanding profit generation. By focusing on optimizing high-margin products, the supermarket can increase its profitability.


Recommendations :
1.	Enhance Customer Loyalty Programs : Given that Branch A has the highest number of loyal (member) customers, expanding membership programs across all branches could foster greater customer loyalty and increase revenue
2.	Promote Underperforming Categories : Special promotions or discounts could be introduced for underperforming categories, such as "Healty and Beauty" "Home and Lifestyle" and "Sports and Travel," to boost their sales.
3.	Optimize Inventory Based on Time Trends : By analyzing the time of day and days of the week with peak purchasing activities, the supermarket can adjust stock levels and staffing to meet demand during high-traffic periods.
4.	Leverage Digital Payment Methods : With a clear preference for e-wallets and cash, the supermarket should continue investing in and promoting digital payment methods, potentially offering promotions or loyalty points for customers using credit cards or e-wallets.
5.	Improve Customer Service and Product Quality : To address the few low customer ratings, the supermarket should focus on enhancing its customer service and improving product quality. Training staff and ensuring consistent product availability could improve overall satisfaction.
6.	Optimize High-Margin Products : Focus on products with higher profit margins for strategic placement and marketing to maximize profitability, especially in high-performing categories.



