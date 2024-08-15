# [SQL]Google Ecommerce Analytics
## I. Introduction
This project contains an eCommerce dataset that I will explore using SQL on Google BigQuery. The dataset is based on the Google Analytics public dataset and contains data from an eCommerce website.
## II. Dataset Access
The eCommerce dataset is stored in a public Google BigQuery dataset. To access the dataset, follow these steps:
- Log in to your Google Cloud Platform account and create a new project.
- Navigate to the BigQuery console and select your newly created project.
- In the navigation panel, select "Add Data" and then "Search a project".
- Enter the project ID "bigquery-public-data.google_analytics_sample.ga_sessions" and click "Enter".
- Click on the "ga_sessions_" table to open it.
## III. Exploring the Dataset
In this project, I will write 08 query in Bigquery base on Google Analytics dataset

### Query 01: calculate total visit, pageview, transaction for Jan, Feb and March 2017 (order by month)
- SQL code
![](https://github.com/user-attachments/assets/22a577cf-e253-4f07-86b5-c2840aee6840)
- Query results
![](https://github.com/user-attachments/assets/dcf453ef-e376-4ef2-9ea2-c855778eb7c0)
### Query 02: Bounce rate per traffic source in July 2017 (Bounce_rate = num_bounce/total_visit) (order by total_visit DESC)
- SQL code
![](https://github.com/user-attachments/assets/c1a0aefb-2c46-4b1b-8653-0a55f85c46e5)
- Query results
![](https://github.com/user-attachments/assets/8e160da1-42c3-4600-9ad5-e326a1969560)
### Query 3: Revenue by traffic source by week, by month in June 2017
- SQL code
![](https://github.com/user-attachments/assets/f010d619-c535-4069-b614-d490d64e6beb)
- Query results
![](https://github.com/user-attachments/assets/8df2d5ee-45a6-47f7-a1db-e52faa58e81d)
### Query 04: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017.
- SQL code
![](https://github.com/user-attachments/assets/63a8a433-6d75-467a-8d9a-912b115029f1)
![](https://github.com/user-attachments/assets/836955b7-0b93-4f82-85cd-24a552a14979)
- Query results

![](https://github.com/user-attachments/assets/b3aab64b-d2d3-47dc-acde-2e0d3d999a57)
### Query 05: Average number of transactions per user that made a purchase in July 2017
- SQL code
![](https://github.com/user-attachments/assets/4af8b0c5-6423-4ac3-a13d-3bf36c0010b2)
- Query results

![](https://github.com/user-attachments/assets/9c8f6866-f85d-49d7-ac5e-794f863d0800)
### Query 06: Average amount of money spent per session. Only include purchaser data in July 2017
- SQL code
![](https://github.com/user-attachments/assets/68768db2-b6cd-46e8-9a10-fc1b4bdec494)
- Query results

![](https://github.com/user-attachments/assets/49006e9b-d113-449c-9785-6cdd7b292540)
### Query 07: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered.
- SQL code
![](https://github.com/user-attachments/assets/60016fa9-41b8-443e-b583-ccee375cd3e9)
- Query results

![](https://github.com/user-attachments/assets/0df634d4-1e33-4d23-a201-ac4e8415bd3f)
### Query 08: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017. The output should be calculated in product level.
- SQL code
![](https://github.com/user-attachments/assets/87e7ba1d-06aa-41b6-bf38-1cac0baf4f62)
- Query results

![](https://github.com/user-attachments/assets/c7503b9d-50be-4237-bda0-a714462f6b68)

## IV. Conclusion
- In conclusion, my analysis of the eCommerce dataset using SQL queries on Google BigQuery's Google Analytics platform has uncovered numerous significant insights.

- Through this exploration, I've extracted valuable data on key metrics including total visits, pageviews, transaction counts, bounce rates, and revenue distribution across traffic sources. These findings are poised to inform and shape future business strategies.

- The next phase involves visualizing these insights using powerful tools such as Power BI or Tableau, allowing for a deeper understanding of key trends and patterns within the data.

- Overall, this project has highlighted the effectiveness of combining SQL with big data platforms like Google BigQuery in extracting meaningful insights from extensive datasets, demonstrating its potential for data-driven decision making in eCommerce.
