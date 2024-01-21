# Survival Analysis and Churn Rate Calculation for an Internet Service Provider

## Contents
1. [Project Description](#project-description)
2. [Data Description](#data-description)
3. [Exploratory Analysis with Visualization](#exploratory-analysis-with-visualization)
4. [RFM Analysis](#rfm-analysis)
5. [Survival Analysis (Kaplan-Meier and Logrank Tests)](#survival-analysis-kaplan-meier-and-logrank-tests)
6. [Churn Rate](#churn-rate)
7. [Conclusion](#conclusion)

## Project Description
This project aims to perform a survival analysis on an internet service provider company's data to calculate churn rates over various years. We utilize the Kaplan-Meier method for survival curve estimation and conduct Log rank tests to assess survival differences between genders and age groups, aiming to identify factors influencing customer churn and develop targeted strategies for improving customer loyalty and business sustainability.

## Data Description
The dataset contains transactional data from an internet service provider, covering January 2016 to the present, with 143,869 records. Each record includes:
- Account ID
- Payment amount
- Payment method
- Payment date
- Customer gender (generated with Python)
- Customer age (generated with Python)
- Age group (generated with Python)
- Village of the customer

## Exploratory Analysis with Visualization
We visualized the company's yearly revenue to identify trends and anomaly years. Analysis showed dynamic patterns in revenue over the years, indicating potential stagnation or decline in upcoming years.

## RFM Analysis
RFM analysis was conducted using customer transaction data. Customers were segmented into four categories based on their RFM scores: 'Leaving Customers,' 'Risky Customers,' 'Potential Loyalists,' and 'Champions.' This helped in identifying diverse customer engagement and retention challenges.

## Survival Analysis (Kaplan-Meier and Logrank Tests)
The Kaplan-Meier analysis focused on customer retention between 2020 and 2022, with survival curves plotted to view customer retention trends. Log rank tests were conducted to compare survival curves across different demographics, focusing on gender and age groups. The analysis revealed significant differences in customer retention across RFM segments.

## Churn Rate
The churn rate, a crucial business metric, was calculated yearly and by gender. Analysis revealed a declining churn rate over the years, with noticeable differences between male and female customers in recent years.

## Conclusion
The project highlighted the need for targeted strategies to convert risky customers into loyal ones and personalized retention strategies for high-risk segments. The findings suggest the potential effectiveness of gender-specific marketing tactics to address varying churn trends.
