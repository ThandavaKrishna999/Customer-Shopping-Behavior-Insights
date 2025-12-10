# Customer-Shopping-Behavior-Insights

End-to-End Data Analytics Project (Python • SQL • Power BI)


📌 Project Overview

This project analyzes customer shopping behavior using a dataset of 3,900 retail transactions.
The goal is to uncover insights into:

Customer spending patterns

High-value customer segments

Product performance

Seasonal trends

Subscription adoption

Discount behavior


This project demonstrates a complete analytics workflow using Python, PostgreSQL (SQL), Power BI, and DAX.


🧹 1. Python – Data Cleaning & Preparation

Key tasks performed:

Loaded dataset using pandas

Inspected structure with .info() and .describe()

Imputed missing values in review_rating

Renamed columns to snake_case

Engineered new features:

age_group

purchase_frequency_days


Removed redundant column promo_code_used

Exported cleaned dataset to SQL database


See: notebooks/data_cleaning.ipynb


---

🗄 2. SQL – Business Analysis

Performed structured analysis using MySQL.

Revenue by gender

High-spending customers using discounts

Top 5 highest-rated products

Standard vs Express shipping behavior

Subscribers vs non-subscribers

Discount-dependent products

Customer segmentation (New, Returning, Loyal)

Top 3 products per category

Repeat buyers & subscription correlation

Revenue contribution by age groups



📊 3. Power BI Dashboard

A 3-page interactive dashboard was created to visualize insights.

Page 1 – Customer Overview

Total Revenue

Average Purchase Amount

Discount Usage

Revenue by Category & Season

Age & Gender Distribution


Page 2 – Customer Segmentation

Repeat Customer %

Subscriber %

Avg Lifetime Spend

High/Medium/Low Value Segments

Top Customers


Page 3 – Product Insights

Category Revenue

Top Products

Seasonal Trends

Average Rating by Category


📌 Key Performance Indicators (KPIs)

KPI Name	Description

Total Revenue	Total sales across all purchases
Total Customers	Distinct customer count
Repeat Customer %	Returning customer ratio
Subscriber %	Proportion of customers with subscription
Avg Purchase Amount	Average spend per transaction
Avg Lifetime Spend	Total spend per customer
Avg Review Rating	Customer satisfaction
Units Sold	Number of purchases made



💡 Business Insights

Subscribers spend significantly more than non-subscribers

Loyal customers generate the majority of revenue

Clothing category is the strongest revenue contributor

Fall season shows the highest purchase activity

Express shipping users tend to spend more

Some products are highly discount dependent



🎯 Recommendations

Promote subscription benefits to increase retention

Strengthen loyalty rewards for high-value customers

Reduce discount dependency on low-margin products

Promote highly-rated products in campaigns

Target middle-aged customers with personalized offers



📎 Included Files

✔ Python Cleaning Notebook

✔ SQL Analysis Script

✔ Power BI Dashboard (.pbix)

✔ Project Report (PDF)

✔ Presentation Slides (PPTX)



🙋‍♂ About the Project

This project demonstrates end-to-end analytics skills:

Python for cleaning & feature engineering

SQL for structured business analysis

Power BI for dashboards

DAX for KPIs

Business storytelling for insights

✅ A repo banner image
✅ A LinkedIn project announcement post
Just tell me!
