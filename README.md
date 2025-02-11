## Customer Churn Dashboard

## Problem Statement
Customer retention is a critical challenge for businesses, particularly in the subscription-based services sector. High churn rates can result in revenue loss and increased customer acquisition costs. This dashboard aims to analyze factors influencing customer churn, providing actionable insights to enhance customer retention strategies.

## Overview
This **Customer Churn Dashboard** provides an interactive visualization of key metrics related to customer retention and churn analysis. The dashboard helps identify patterns and insights into factors influencing churn, allowing businesses to take proactive measures.

## Features
- **Customer Churn Analysis**: Visualizes the proportion of customers who churned vs. those who stayed.
- **Tenure vs. Tech Support Tickets**: Shows the relationship between customer tenure and the number of tech support tickets raised.
- **Payment Method Insights**: Displays customer distribution by different payment methods.
- **Internet Service Impact**: Examines churn based on internet service type (Fiber optic, DSL, or No internet service).
- **Monthly Charges Breakdown**: Aggregates monthly charges across different internet services.
- **Demographic Segmentation**: Provides gender-based churn statistics and senior citizen distribution.
- **Paperless Billing Influence**: Highlights churn rates for customers with and without paperless billing.

## Dashboard Visuals & Titles
1. **Churn Distribution** - Count of customer churn.
2. **Tech Support Tickets by Tenure** - Relationship between tenure and the number of tech tickets.
3. **Customer Distribution by Payment Method** - Bar chart displaying counts per payment method.
4. **Churn Breakdown by Internet Service** - Internet service impact on churn rate.
5. **Monthly Charges by Internet Service** - Sum of monthly charges categorized by internet service type.
6. **Churn Analysis by Gender** - Gender-based churn statistics.
7. **Paperless Billing & Churn** - Churn count based on paperless billing status.
8. **Key Metrics Summary** - Total customers, number of tech tickets, total & average monthly charges.

## Process Overview
### 1. Data Loading
- Extracted customer data from SQL databases and CSV files.
- Used **Python (Pandas)** for loading datasets efficiently.

### 2. Data Cleaning & Preparation
- Removed missing or duplicate values to ensure data consistency.
- Standardized column names and formatted date fields.
- Performed outlier detection and handled inconsistent entries.
- Merged multiple data sources (customer demographics, transactions, and churn labels).

### 3. Data Transformation & Feature Engineering
- Created derived metrics such as **churn rate, average tenure, and total monthly charges**.
- Encoded categorical variables like **payment method and internet service** for better analysis.
- Aggregated customer behaviors to gain deeper insights.

### 4. Creating Visuals
- Designed **interactive Power BI dashboards** with key KPIs.
- Implemented **bar charts, pie charts, and line graphs** to present trends.
- Used slicers and filters to enhance user experience and data exploration.
- Created **DAX measures** to calculate important business metrics dynamically.

## Technologies Used
- **Power BI**: For interactive data visualization.
- **Python (Pandas, NumPy)**: Data cleaning, preprocessing, and merging datasets.
- **SQL**: Querying and extracting relevant customer data.

## How to Use
1. Open the **Power BI** `.pbix` file.
2. Apply filters to explore insights dynamically.
3. Analyze customer churn trends and identify key business actions.

## Business Insights
- Higher churn is observed among **Fiber Optic users** compared to DSL users.
- Customers with **electronic payment methods** show higher churn rates.
- **Senior citizens** tend to have slightly higher churn rates.
- Paperless billing users have a **higher churn rate** compared to non-paperless users.
- The number of tech tickets decreases as tenure increases, except for a sudden rise at longer tenure periods.

## Future Improvements
- Incorporate **predictive analytics** for churn forecasting.
- Add **customer segmentation** based on spending behavior.
- Introduce **geographical insights** for location-based churn patterns.

## Contributing
If you’d like to enhance this dashboard or improve data visualization, feel free to **fork this repository** and submit a pull request with your changes.

## Author
Developed by itsyourpavan. Connect with me for further discussions on **data analytics and visualization!**

