# Credit Risk & Receivables Analytics Dashboard

## Overview

An interactive Power BI dashboard for analyzing customer receivables, payment behavior, outstanding dues, and credit risk.

The dashboard brings together sales, collections, customer risk, recency, and team-level receivables into a single view for monitoring outstanding balances and collection performance.

## Business Problem

Businesses that sell on credit need visibility into:

- Sales versus collections
- Outstanding receivables
- Customers with high or critical credit exposure
- Customer payment behavior
- Team-wise outstanding dues
- Customers with the highest outstanding balances

This dashboard provides a consolidated view of these metrics to support receivables monitoring and collection follow-up.

## Key Metrics

| KPI | Value |
|---|---:|
| Total Sales | ₹19.59 Cr |
| Total Payments | ₹16.85 Cr |
| Outstanding Due | ₹2.73 Cr |
| Collection Efficiency | 86.05% |
| Critical Clients | 18 |
| Customers Analyzed | 200 |

## Dashboard Analysis

### Sales & Collections

Tracks monthly sales and payment collections to compare sales activity with cash collections.

### Credit Risk

Customers are segmented into:

- Low
- Medium
- High
- Very High
- Critical

This provides a view of customer credit exposure and helps identify accounts requiring closer monitoring.

### Customer Recency

Analyzes customer activity based on collection recency and groups customers into different recency categories.

### Team-wise Outstanding

Compares outstanding receivables across teams to identify where balances are concentrated.

### Top Debtors

Highlights customers with the highest outstanding balances for collection follow-up.

### Client Receivables

Provides customer-level information including:

- Sales
- Payments
- Outstanding dues
- Credit risk
- Sales frequency
- Payment frequency
- Recency status

## Tools & Technologies

- Power BI
- DAX
- Power Query
- Excel / CSV
- Data Modeling
- Data Visualization

## Project Structure

```text
├── README.md
├── CreditData.csv
├── assets/
│   └── dashboard.png
└── PowerBI/
    └── Credit_Risk_Receivables_Dashboard/
        ├── Credit_Risk_Receivables_Dashboard.pbip
        ├── Credit_Risk_Receivables_Dashboard.Report/
        └── Credit_Risk_Receivables_Dashboard.SemanticModel/
```

## Dashboard Preview
<img width="1536" height="1024" alt="dashboard" src="https://github.com/user-attachments/assets/97a5c172-2301-48ef-b76c-b6a343792930" />


## Dataset

The project contains receivables data covering 200 customers, including sales, payments, outstanding balances, customer teams, credit risk, payment frequency, and recency information.

## Outcome

The dashboard provides a consolidated view of receivables performance and customer credit exposure, helping identify outstanding balances, collection patterns, and customers requiring attention.
