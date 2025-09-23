📌 Project Overview

This project is a Power BI Dashboard built from raw telecom customer data.
The dashboard provides business insights into customer churn, revenue, and service adoption, helping decision-makers identify risk factors, optimize revenue streams, and improve retention strategies.

⚙️ Data Source

Input File: telecom_customer_data.xlsx (or equivalent Excel file)

Key Columns:

CustomerID, Gender, SeniorCitizen, Partner, Dependents

Tenure, Contract, PaymentMethod, MonthlyCharges, TotalCharges

Services (PhoneService, InternetService, OnlineSecurity, etc.)

Churn status

🛠️ Data Preparation

Performed in Power Query & DAX inside Power BI:

Converted TotalCharges to numeric and handled missing values.

Created calculated columns:

Customer Segment (New, Growing, Mature, Loyal)

Services Count

Churn Binary

Customer Lifetime Value (CLV)

Defined measures for KPIs:

Total Customers, Churn Rate, Monthly Revenue, Average Tenure

Revenue at Risk, Average Revenue per User (ARPU), Adoption Rates

📊 Dashboard Structure
Page 1 – Executive Overview

KPI Cards: Total Customers, Churn Rate, Monthly Revenue, Avg. Tenure

Churn by Customer Segment (Clustered Column)

Distribution by Contract Type (Donut Chart)

Monthly Charges Distribution (Histogram)

Service Adoption Rates (Horizontal Bar Chart)

Revenue by Customer Segment (Clustered Column)

Page 2 – Churn Analysis

Churn Rate by Tenure (Line Chart)

Churn by Payment Method (Bar Chart)

Internet Service vs Churn (Matrix)

Services Count Impact on Churn (Scatter Plot)

High-Risk Customers Table (filter: Churn = No)

Page 3 – Revenue Analysis

Revenue by Contract Type (Dual-Axis Column Chart)

Customer Value Distribution (Scatter Plot: tenure vs MonthlyCharges)

Service Revenue Contribution (Treemap)

Payment Method Performance (Matrix with conditional formatting)

🎛️ Interactive Features

Slicers: Customer Segment, Gender, Contract Type, Senior Citizen

Drill-Through: Customer detail analysis page

AI Visuals: Key Influencers for churn, Decomposition Tree for revenue

Alerts: Churn rate >30%, revenue drop alerts

🎯 Insights & Recommendations

High churn risk among month-to-month contracts and customers with fewer services.

Bundled services adoption reduces churn and increases CLV.

Electronic payment methods show better retention vs mailed checks.

Revenue growth opportunities lie in upselling to loyal, long-tenure customers.

Recommendations:

Focus retention campaigns on new and month-to-month customers.

Promote bundled service packages to increase adoption.

Encourage customers to switch to automatic/electronic payments.

Target loyal customers with premium upgrades to maximize revenue.