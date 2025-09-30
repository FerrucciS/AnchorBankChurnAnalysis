# Anchor Bank Churn Analysis

## Project Background

Anchor Bank, established in 2016, is a European financial institution providing secure and modern banking to clients in Germany, Spain, and France.

As an emerging company, Anchor Bank wants to investigate customer churn with the aim of 
1. Increasing customer satisfaction.
2. Reducing risk.
3. Maximising revenue.
4. Build trustworthiness and customer loyalty.

This project thoroughly analyses customer data in order to uncover insights that will support Anchor Bank's growth and reputation.

Insights and recommendations are provided on the following key areas:
- __Churn Trend Analysis__: How has churn evolved over time, and how does it differ across regions? Which customer segments of customers show the highest exit rates?
- __Product Performance__: How do customer engagement and satisfaction vary by product holding? Are certain product combinations linked to higher churn?
- __Customer Profiles__: Which demographic and behavioural characteristics (e.g., age, gender, credit rating, activity level) are most associated with churn?
- __Retention Priorities__: Where should Anchor Bank focus its efforts to achieve the biggest impact in reducing churn?

An interactive PowerBI report can be downloaded [here](Bank.pbix.
The findings are presented in two layers:
- __Overview (Page 1)__: High-level trends and key customer segments at risk.
- __Drivers (Page 2)__: Deeper analysis of underlying casues of churn and actionale recommendations.

## Data Modelling 

To support the churn analysis, a data model was developed in PowerBI using a star schema design. This design ensures clear relationships between the fact table and dimension tables.
- __Fact Table__: Bank_churn.
- __Dimension Tables__: Date, CustomerInfo, ActiveCustomers, Credit_card, Exit_Customer, Geography.

![Star Schema Diagram](images/DataModel.png)


## Executive Summary


## Churn Trends

![Overview](images/ChurnRateOverview.png)

## Churn Causes

![Insights](images/ChurnRateInsights.png)
