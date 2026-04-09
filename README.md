#  Cohort Analysis

## I. Introduction

### 1. About Cohort Analysis

**What is cohort analysis?**

**Cohort analysis** is an analytical technique that categorizes and divides data into groups (**cohorts**), with common characteristics prior to analysis. This technique helps us isolate, analyze, and detect patterns in the lifecycle of a user, to optimize customer retention, and to better understand user behavior in a particular cohort.

Businesses use **cohort analysis** to understand the trends and patterns of customers over time and to tailor product and service offers to the identified cohorts.

**Three major types of Cohort**
- **Time-based**: groups customers based on the time they started using a company’s products or services.
- **Segment-based**: groups customers by the type of product or level of service they signed up for.
- **Size-based**: groups customers based on their size.


### 2. Business Questions
Using Python to create time-based cohorts analysis that allows stakeholders to assess and compare retention, order items quantity and order revenue from different cohorts of customer to optimize and tailor products and services offers to these specific cohorts.

### 3. About the Dataset

The dataset is from Kaggle ([Link](https://www.kaggle.com/datasets/ytgangster/online-sales-in-usa)), consists of 36 columns and 286392 entries, records online sales data of different products, several merchandise and electronic in different states in USA from October 2020 to September 2021. 

Overview of dataset:

![image](https://github.com/mytrannn22/Cohort-Analysis/assets/140190425/73316003-dead-4395-874a-d9711ddb0007)


Since the goal of this project is to analysize time-based cohorts, let's extract just necessary columns as follows:

![image](https://github.com/mytrannn22/Cohort-Analysis/assets/140190425/78e863b3-6e5e-42bf-9dcb-6876845a0c4e)


### 4. About this Project

This project focuses on performing time-bases Cohort Analysis: Customers will be divided into acquisition cohorts depending on the years that they become customers. Due to the wide spread of customer acquisition years (from 1978 to 2017), this project will create 5-year-bins and then assign each of customer’s transaction from October 2020 to September 2021 into these bins. 

The goal of this project is to point out the significant trends and patterns in retention rate, order items quantity and revenue of different customer cohorts based on their acquirement time, then give recommendations to optimize sales and marketing strategies to improve overall performance.

The project will follow these steps:

1. Install the environment
2. Import and clean the dataset
3. Assign cohorts
4. Calculate retention rates
5. Segment data by Quantity and Revenue 

## II. Data Visualization

### 1. Number of Customers per Cohort
![image](https://github.com/mytrannn22/Cohort-Analysis/assets/140190425/afde96c7-c254-44be-82b8-36d287123f11)


### 2. Customer Retention and Retention Rate
![image](https://github.com/mytrannn22/Cohort-Analysis/assets/140190425/1f2f6b91-ce06-4d49-9622-6ed0dd2e6321)

![image](https://github.com/mytrannn22/Cohort-Analysis/assets/140190425/243e155e-921b-4ef0-82fc-e7faf72348a4)

### 3. Cohorts by Quantity
![image](https://github.com/mytrannn22/Cohort-Analysis/assets/140190425/d0adcd6b-c3c2-4cde-8b95-856468d6ebb4)


### 4. Cohorts by Revenue
![image](https://github.com/mytrannn22/Cohort-Analysis/assets/140190425/0ef4b796-e34a-4c7a-bcbd-7fad8a8abe54)


## III. Key Insights 
Key Insights
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
- 
## IV. Recommendations

While acquiring new customers is important, retaining existing customers is more cost-effective
Long-term customers contribute significantly to revenue and should be prioritized
Suggested strategies:
Personalized customer experiences
Loyalty programs and incentives
Regular engagement and communication

Additionally, further analysis on Customer Acquisition Cost (CAC) can help optimize marketing investments.
