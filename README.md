# Telco Customer Churn Analysis Report

## Project Background:

The telecommunications industry is highly competitive, and customer retention is crucial for long-term business success. In these industries churn rate is a key factor in the success of the business. Customer Churn refers to where a customer stops using a company’s services. Having a high churn rate signifies a high percentage of customers leaving/cancelling the service provided by the business which can be due to a variety of different reasons. Having a high churn rate is unstainable for growth leading in to low reduced revenue coming into the business.
The company is experiencing a significant number of customers leaving its services. However, it is unclear which customer groups are most likely to churn or which factors contribute to a customer leaving. This project analyses customer churn data to identify the key factors that contribute to customer churn and to explore how the business can improve customer retention and reduce customer loss.

## Dataset:

The dataset contains customer data of the telecommunications company. It contains 21 tables and over 7000 records of customer records that contain details such as CustomerID, contract type, service type, tenure, monthly charge and other customer information.

## Main Question:

What factors influence customer churn and how can the company reduce the churn rate?

### Key questions:

•	What is the overall churn rate?

•	Which customer segments experience the highest churn? 

•	Does customer tenure (length of time with the company) impact churn?

•	Do monthly charges ore total charges affect likelihood of churn?

•	Do different internet services or payment methods show different churn patterns?

## Telco Customer Churn Analysis Dashboard

<img width="940" height="416" alt="image" src="https://github.com/user-attachments/assets/0c6df615-ffa6-4504-9452-5e7072b49753" />

## Overview of Findings:

The analysis revealed an overall churn rate of 26.54%, meaning that approximately one if four customers leave the company. This relatively high churn rate indicates that customer retention can be improved and can become a significant challenge in the future for the business and highlights the need to identify key churn drivers.

### Churn Rate by Contract Type:

Churn behaviour varied significantly by contract type:

•	Month-to-month customers experienced the highest churn rate of 42.71%(1,655 customers) leaving the service, making month-to-month contracts being the highest contributor to the churn rate as out of 1,869 customers churned 1,655 of those customers comes from month-to-month contracts.	

•	Customer on one-year contracts showed substantially lower churn rate of 11.27%(166 customer)

•	Two-year contract customers had the lowest churn rate 2.83% with only 48 customers leaving.

The data suggests that longer contract commitments are strongly associated with improved customer retention. Customers on flexible, month-to-month contract are more likely to switch provides, while long-term contracts increase customers stability.

<img width="919" height="488" alt="image" src="https://github.com/user-attachments/assets/3f8dfa9c-bb76-4161-9af6-7a7c1ca3e3f9" />

### Churn Rate by Tenure Group:

Customer tenure was found to be a major factor influencing churn rate. The churn rate decreases steadily as customer tenure increases. Nearly half the customers within the first year churned (47.44%), indicating that early-stage customers are the most vulnerable. In contrast customers over the 5 years mark demonstrated strong loyalty, with a very low churn rate (6.61%). This suggests that improving the early customer engagement and onboarding could significantly reduce the churn rate.

<img width="910" height="484" alt="image" src="https://github.com/user-attachments/assets/1808adc1-736d-44c6-9e42-a45a94e569be" />

### Churn Rate by Monthly Charge Group:

Customers were grouped into pricing bands to examine the relationship between monthly charges and churn:

•	Customers paying £0-30 per month showed the lowest churn rate of 9.8%

•	Customers in the £30-60 range experienced moderate churn rate of 26.08%

•	The £60-90 group has the highest churn rate of 33.74%

•	Customer paying £90 showed the second highest churn rate of 32.86%

These results indicate that as monthly chargers rise the churn rate increases. Higher-paying customers may perceive that the service does not qualify to pay over £90 a month, making pricing and service quality critical factors in retention.

<img width="914" height="501" alt="image" src="https://github.com/user-attachments/assets/91506440-3927-4626-8b34-ff11c2205cf9" />

### Churn Rate by Internet Service:

Analysis by internet service type revealed notable differences between the services:

•	Fibre optic customers had the highest churn rate of 41.89%, with 1,297 customers leaving the service.

•	Customers who have Digital Subscriber Line (DSL) showed a moderate churn rate of 18.96% with 459 customers leaving the service.

•	Customers who have no internet service churned the least with a 7.4% churn rate and 113 customers leaving the service.

The analysis suggests that potential service quality, pricing or relatability issues could be associated with the internet service having a higher churn rate.

<img width="896" height="501" alt="image" src="https://github.com/user-attachments/assets/3a970ebd-a824-42a0-8ba2-60016984f227" />

### Churn Rate by Payment Method:

Customer Churn Rate shows that customers using electronic check have the highest churn rate. Out of 2,365 customers using the payment method 1,071 has left the service resulting in a 45.29% churn rate. Other payment method like mailed check(19.11%), bank transfer (16.71%) and credit card(15.24%) show considerable lower and relatively similar churn rates.

<img width="923" height="510" alt="image" src="https://github.com/user-attachments/assets/e0ad8c5d-70c8-4d3c-a7c7-bf562eab3b32" />

## Recommendations:

Based upon the uncovered insights, the following recommendations have been provided:

### Improve Retention of New Customers

New customers (0–1 year tenure) were identified as the highest-risk group, with a churn rate of 47.44%.

•	Implement a structured customer onboarding programme during the first 3–6 months.

•	Provide welcome emails, tutorials, or setup guidance to ensure customers understand how to use services effectively.

•	Offer early-stage incentives such as discounts, free add-ons, or loyalty rewards for customers who remain beyond their first year.

Focusing on early engagement could significantly reduce churn during the most vulnerable period of the customer lifecycle.

### Encourage Longer-Term Contracts:

Month-to-month contract customers churned at substantially higher rates than customers on one-year or two-year contracts.

•	Introduce price incentives or bundled benefits for customers who switch from month-to-month to longer-term contracts.

•	Promote long-term contracts during renewals or customer service interactions.

•	Offer flexible exit options or trial periods to reduce customer hesitation when committing to longer contracts.

Increasing long-term contract adoption can help stabilise the customer base.

### Review Pricing and Value for High-Cost Customers:

Customers paying £60–90 and £90+ per month showed the highest churn rates, indicating potential dissatisfaction with price-to-value perception.

•	Review pricing structures for premium plans to ensure they remain competitive.

•	Introduce value-added features for high-paying customers, such as faster speeds, priority support, or exclusive benefits.

•	Conduct targeted surveys to understand specific reasons for dissatisfaction among premium customers.

Improving perceived value can help retain high-revenue customers.

### Address Issues with Fiber Optic Services:

Fiber optic customers experienced the highest churn among internet service types.

•	Investigate service quality issues such as installation problems, outages, or performance reliability.

•	Provide proactive customer support and technical follow-ups for fibre optic customers.

•	Consider tailored retention offers or service guarantees for customers experiencing repeated issues.

Improving service reliability and communication could reduce churn within this segment.

### Promote Automated and Reliable Payment Methods:

Customers using electronic check payment methods exhibited higher churn than those using bank transfers or credit cards.

•	Encourage customers to switch to automated payment methods by offering small discounts or incentives.

•	Simplify the payment process and improve billing transparency.

•	Communicate payment confirmations and reminders clearly to reduce friction.

Improving the payment experience may help increase customer satisfaction and retention.

### Implement Proactive Churn Monitoring:

The analysis shows that churn risk can be identified based on customer characteristics such as tenure, contract type, pricing, and service type.

•	Develop a churn monitoring framework using these factors to flag high-risk customers.

•	Target at-risk customers with personalised retention offers or proactive support.

•	Consider implementing predictive churn models in future analyses.

Proactive intervention can help prevent customer loss before churn occurs.
