# [PYTHON] Cohort Analysis - Analyze User Retention Rate

# I.Introduction
# 1. Project Request

From Python, you will use KPMG transaction data to make a cohort to evaluate user engagement from their first transaction

# 2. About Cohort Analysis
**What is cohort and cohort analysis?**

A cohort is a collection of users who have something in common, and cohort analysis is a tool to measure their engagement over time. 
Cohort analysis helps to differentiate between actual improvements in user engagement and those that may be driven by growth, while vanity indicators do not provide the same level of insight.
**Three major types of Cohort**

- Time cohorts: customers who signed up for a product or service during a particular time frame.
- Behavior cohorts: customers who purchased a product or subscribed to a service in the past.
- Size cohorts: refer to the various sizes of customers who purchase the company’s products or services.

**Which type of cohort is for this project?**

Focus on performing Cohort Analysis based on Time(Time cohorts).
Customers will be divided into acquisition cohorts depending on the month of their first purchase.
The cohort index would then be assigned to each of the customer’s purchases, which will represent the number of months since the first transaction.

# II. Data Visualization with Python
MoM The number of customer

![image](https://github.com/uyennguyen307/Python_Cohort-Analysis-KPMG-transaction-data/assets/162019618/7d5b0710-f38f-4ad4-86e6-1da6427a1605)

MoM Retention Rate for Customer Transaction Data
![image](https://github.com/uyennguyen307/Python_Cohort-Analysis-KPMG-transaction-data/assets/162019618/c81f9504-4d36-493c-b330-655a1d9c9e97)

# III. Information/ Insights
Overall, 
- No more than 50% customers engage after first transaction, almost fluctuate from 25% - 48%
- From January to December, there was a gradual downtrend in the number of first transaction
- Customers who have first transaction from mid-year 4,5,6,7 tend to increase, and relatively higher than the rest months of the year.

In detail,
- In July 2017, there was a growth (from 34% to 48%) and also the highest retention rate (upto 48.1%) after 5 months since their first transaction
- In April 2017, it gained relatively high retention rate: 45.1% (4th month), 42.1% (5th month) ), and 42.7% (7th month).

# IV. Recommendation
- Retention rate is lower than 50% whether is good or not => Should observe more and consider which benchmark for retention rate is good
- There was a gradual downtrend in the number of first transaction from January to December => deep dive into marketing data & strategy to attract more users make the first transaction
- The Mid-year months have higher retention rates than other months -> need to dive into why (with relevant data, and visualization of other data) to apply to other months of the year.
