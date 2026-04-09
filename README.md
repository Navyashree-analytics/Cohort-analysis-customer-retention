# Cohort-analysis-customer-retention
1. 📌 Introduction
🔍 What is Cohort Analysis?

Cohort analysis is an analytical technique that groups users based on shared characteristics and analyzes their behavior over time. It helps in identifying patterns in the customer lifecycle, improving retention, and understanding how different groups of users interact with a product or service.

Businesses use cohort analysis to track customer trends over time and design targeted strategies for different user groups.

📂 Types of Cohorts
Time-based cohorts: Group customers based on when they first interacted with the business
Segment-based cohorts: Group customers based on product type or service level
Size-based cohorts: Group customers based on size or value
2. 🎯 Business Objective

The goal of this project is to perform time-based cohort analysis using Python to evaluate:

Customer retention
Order quantity trends
Revenue patterns

This helps stakeholders compare different customer cohorts and optimize product, marketing, and retention strategies.

3. 📊 Dataset Description

The dataset is sourced from Kaggle and contains 286,392 records with 36 columns, representing online sales transactions across various product categories in the United States from October 2020 to September 2021.

Key Features Used:
customer_id – Unique identifier for customers
order_id – Transaction ID
order_date – Purchase date
total_sales – Revenue per order
customer_since – Customer acquisition date

For this analysis, only relevant columns were selected to focus on cohort-based insights.

4. 🚀 Project Overview

This project performs time-based cohort analysis by grouping customers based on their acquisition period.

Due to a wide range of customer acquisition years (1978–2017), customers were grouped into 5-year bins, and all transactions (Oct 2020 – Sep 2021) were mapped to these cohorts.

🔑 Project Steps:
Data cleaning and preprocessing
Cohort assignment
Retention calculation
Analysis of quantity and revenue
Data visualization
5. 📊 Data Visualization
👥 Number of Customers per Cohort

Visualizes the distribution of customers across different cohorts

🔁 Customer Retention

Shows how many customers return over time

📦 Cohort Analysis by Quantity

Analyzes average number of items purchased

💰 Cohort Analysis by Revenue

Compares revenue contribution across cohorts

6. 📈 Key Insights
Customer Growth: The number of newly acquired customers has steadily increased over time
Retention Trends: All cohorts show similar patterns
Peak retention (~33%) in December (holiday season)
Secondary peak (~22%) in April (sales events)
Lowest retention in February and late summer/early autumn
Order Quantity:
Lower items per order during peak holiday season
Higher purchase volumes in March and July
Revenue Patterns:
Older cohorts tend to generate higher order values
Revenue peaks during December, March, and April
Lowest revenue observed in January and February
7. 💡 Recommendations
While acquiring new customers is important, retaining existing customers is more cost-effective
Long-term customers contribute significantly to revenue and should be prioritized
Suggested strategies:
Personalized customer experiences
Loyalty programs and incentives
Regular engagement and communication

Additionally, further analysis on Customer Acquisition Cost (CAC) can help optimize marketing investments.

🎯 Final Note (Optional Add in GitHub)

This project demonstrates how cohort analysis can provide actionable insights into customer behavior, helping businesses improve retention, optimize revenue, and make data-driven decisions.
