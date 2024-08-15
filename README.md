# [SQL]Google Ecommerce Analytics
## Introduction
This project contains an eCommerce dataset that I will explore using SQL on Google BigQuery. The dataset is based on the Google Analytics public dataset and contains data from an eCommerce website.
## Exploring the Dataset
In this project, I will write 08 query in Bigquery base on Google Analytics dataset
### Query 01: calculate total visit, pageview, transaction for Jan, Feb and March 2017 (order by month)
- SQL code
![](https://github.com/user-attachments/assets/22a577cf-e253-4f07-86b5-c2840aee6840)
- Query results
![](https://github.com/user-attachments/assets/dcf453ef-e376-4ef2-9ea2-c855778eb7c0)
### Query 02: Bounce rate per traffic source in July 2017 (Bounce_rate = num_bounce/total_visit) (order by total_visit DESC)
- SQL code
- Query results
### Query 3: Revenue by traffic source by week, by month in June 2017
- SQL code
- Query results
### Query 04: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017.
- SQL code
- Query results
### Query 05: Average number of transactions per user that made a purchase in July 2017
- SQL code
- Query results
### Query 06: Average amount of money spent per session. Only include purchaser data in July 2017
- SQL code
- Query results
### Query 07: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered.
- SQL code
- Query results
### Query 08: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017. The output should be calculated in product level.
- SQL code
- Query results
