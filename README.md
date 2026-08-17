Synthetic Fraud Detection Dashboard

📊 Project Overview

Synthetic Fraud Detection is an interactive Microsoft Power BI dashboard designed to analyze transaction data and identify patterns associated with fraudulent activity. The project uses a synthetic fraud dataset and presents transaction, customer behavior, account, device, merchant, location, card, and fraud-risk insights through multiple dashboard pages.

The dashboard helps users explore fraud patterns using interactive filters and visualizations. It can be used as a portfolio project for demonstrating skills in Power BI, data visualization, exploratory data analysis, business intelligence, and fraud-risk analysis.

🎯 Objectives

Analyze transaction activity and transaction amounts.

Understand the distribution of fraudulent and non-fraudulent transactions.

Identify transaction types associated with higher fraud activity.

Analyze user transaction behavior and daily transaction counts.

Examine account balance patterns related to fraud.

Compare fraud activity across devices and channels.

Analyze merchant categories and their transaction behavior.

Explore geographical transaction and fraud patterns.

Study card type and card-age relationships with fraud.

Identify important fraud risk factors.

Provide a consolidated summary of fraud activity.

🗂️ Dataset

The Power BI model uses the table:

synthetic_fraud_dataset1

Important fields used in the dashboard include:

Transaction_ID – Unique transaction identifier

User_ID – Unique user identifier

Date – Transaction date

Transaction_Type – Type of transaction

Transaction_Amount – Monetary value of the transaction

Fraud_Label – Fraud indicator

Daily_Transaction_Count – Number of transactions made by a user per day

Account_Balance – Account balance associated with the transaction

Device_Type – Device used for the transaction

Merchant_Category – Merchant classification

Location – Transaction location

Card_Type – Type of payment card

Card_Age – Age of the card

Previous_Fraudulent_Activity – Previous fraudulent activity indicator

📑 Dashboard Pages

The report contains 10 Power BI pages:

1. Overview Dashboard

Provides a high-level view of total transactions, fraud activity, transaction amounts, and fraud distribution. It also includes filters for transaction ID, transaction type, and date.

2. Transaction Type Analysis

Analyzes transaction volumes and transaction amounts across different transaction types, including their relationship with fraud labels.

3. User Behavior

Examines daily transaction counts and user-level behavior. Scatter and line charts help identify unusual transaction patterns.

4. Account Balance Risk

Analyzes account balances across transactions and over time, with fraud activity included for risk comparison.

5. Device & Channel

Analyzes fraud activity by device type and shows how fraud patterns change across devices and time periods.

6. Merchant Category

Examines transaction amounts and transaction counts across merchant categories while comparing fraudulent activity.

7. Location Analysis

Provides geographical analysis of transaction amounts and transaction activity, along with fraud indicators by location.

8. Card Profile

Analyzes transaction amounts and fraud activity across card types and examines the relationship between card age and fraudulent activity.

9. Fraud Risk Factors

Uses a decomposition tree and comparative charts to explore fraud based on transaction type, device type, location, and previous fraudulent activity.

10. Summary & Prediction

Provides a consolidated fraud summary using fraud distribution, fraud trends over time, total fraud activity, transaction amount, and user-level information.

📈 Key Visualizations

The report includes a variety of Power BI visualizations:

KPI Cards

Donut Charts

Line Charts

Clustered Bar Charts

Clustered Column Charts

Pie Charts

Treemaps

Maps

Scatter Charts

Decomposition Trees

Interactive Slicers

🔍 Interactive Filters

The dashboard provides interactive slicers for:

Transaction ID

Transaction Type

Date

These filters allow users to drill into specific transactions, transaction categories, and time periods.

🛠️ Tools & Technologies

Microsoft Power BI

Power BI Desktop

Data Visualization

Exploratory Data Analysis

Business Intelligence

Fraud Risk Analysis

Synthetic Transaction Dataset

📊 Analysis Performed

The dashboard focuses on several important fraud-analysis dimensions:

Transaction-level analysis

Transaction-type analysis

User behavior analysis

Account balance analysis

Device/channel analysis

Merchant-category analysis

Location-based analysis

Card-profile analysis

Fraud risk-factor analysis

Overall fraud summary

The combination of these views enables users to investigate potential relationships between transaction characteristics and fraudulent activity.

🚀 How to Use

Install Microsoft Power BI Desktop.

Open the Power BI project/report file included with this project.

Allow Power BI to load the data model.

Navigate through the 10 dashboard pages.

Use the available slicers to filter the report.

Hover over charts to view detailed values.

Use the visual interactions to compare fraud activity across different dimensions.

Note: The dataset used in this project is synthetic and is intended for analysis, visualization, and educational/portfolio purposes. It should not be treated as real financial or banking data.

💡 Business Value

Fraud detection is an important application of data analytics in banking and financial services. This dashboard demonstrates how transaction data can be transformed into actionable insights by combining multiple dimensions such as transaction type, user behavior, device, merchant, location, card profile, and historical fraud activity.

The report can help analysts investigate unusual patterns, compare risk factors, and communicate fraud-related insights through an interactive visual interface.

📁 Project Structure

Synthetic-Fraud-Detection/
│
├── Synthetic Fraud Detection.pbix
└── README.md

👨‍💻 Author

Rajib Maity

B.Tech – Computer Science & Engineering (AI & ML)

Institute of Engineering & Management (IEM), Kolkata

📌 Project Type

Data Analytics | Power BI | Fraud Detection | Business Intelligence | Data Visualization

