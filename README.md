# Data-Analytics-Portfolio-Project

**Customer Churn Analysis Pipeline**
**Project Overview**
This project is a data analytics pipeline focused on evaluating customer churn. By extracting data from a relational SQLite database, the project cleans, transforms, and analyzes customer subscriptions, support tickets, and demographics to uncover actionable business insights.  

**Tech Stack & Data Architecture**

L**anguages & Libraries:** Python, Pandas, NumPy, Matplotlib, and Seaborn.  
**Database:** SQLite using the customer_churn.db file.  
**Data Sources:** Three core database tables merged for analysis including db_customer, db_subscription, and db_support.  

**Key Data Processing & InsightsData**
Cleaning: Standardized gender categories, mapped missing country data using state information, converted strings to datetime formats, and removed unnecessary columns.  

**Feature Engineering:** Created a churn_flag to identify lost customers, calculated tenure_days to measure customer lifespan, and categorized churn_risk into low, medium, and high tiers. 

**Overall Churn Metrics:** Calculated a baseline churn rate of 28.57% and a retention rate of 71.43%.  Financial Impact: Identified the exact revenue at risk caused by churned users.  

**Customer Support Correlation:** Found a strong positive correlation (0.77) between support escalations and customer churn, alongside a 19.05% escalation rate.  

**Visualizations:** Generated time-series charts for monthly churn trends, bar charts for churn rate by state and plan type, and a correlation heatmap for encoded features.  