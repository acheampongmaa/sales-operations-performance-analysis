# Sales & Operations Performance Analysis

**Excel • Power Query • Business Intelligence**

## Overview

This project analyzes sales performance, profitability, customer segments, product performance, and operational efficiency using the Superstore dataset.

The analysis follows an end-to-end business analytics workflow:

**Business Problem → Data Cleaning → Data Preparation → Analysis → Dashboard → Insights → Recommendations**

The objective was to identify performance trends, profitability drivers, operational inefficiencies, and potential areas for business improvement.

---

## Business Task

To understand sales trends, profitability drivers, and operational performance indicators in order to identify growth opportunities, reduce losses, and improve business operations.

### Key Business Questions

1. How are sales and profits trending over time?
2. Which regions, customer segments, and product categories drive profitability?
3. Where is the business losing money?
4. Are there operational inefficiencies such as long shipping times or delayed orders?
5. What strategic actions could improve performance in the next quarter?

---

## Stakeholders

The analysis was designed around the information needs of:

- VP of Operations
- Sales Director
- Finance Manager
- Supply Chain Manager
- BI / Data Analyst Team

---

## Data Preparation

The dataset was reviewed and prepared before analysis.

### Data Cleaning

The cleaning process included:

- Inspecting columns and validating data types
- Resolving inconsistent date formats
- Converting order and ship dates into appropriate date fields
- Standardizing state names
- Creating additional analytical fields using Excel and Power Query

### Derived Fields

Several fields were created to support the business analysis:

| Field | Purpose |
|---|---|
| Month | Monthly trend and seasonality analysis |
| Quarter | Quarterly performance analysis |
| Profit Margin | Measures profitability relative to sales |
| Discount Amount | Quantifies the financial impact of discounts |
| Shipping Time | Measures delivery performance |
| Loss Flag | Identifies loss-making transactions |
| Delayed Order Flag | Classifies orders as delayed or on-time |

---

## Analysis Areas

The analysis focuses on five major areas:

### 1. Sales Performance

- Total sales
- Monthly sales trends
- Sales performance over time
- Regional performance
- Product and category performance

### 2. Profitability

- Total profit
- Profit margin
- Profit by region
- Profit margin by product category
- Loss-making sub-categories

### 3. Customer Analysis

- Customer segment performance
- Consumer, Corporate and Home Office segments
- Regional and segment-level performance

### 4. Operational Performance

- Average shipping time
- Shipping time by ship mode
- On-time vs delayed orders
- Identification of operational inefficiencies

### 5. Decision Support

The dashboard translates the analysis into practical business recommendations covering:

- Pricing and discount management
- Regional growth opportunities
- Category profitability
- Loss reduction
- Fulfilment and delivery performance

---

## Dashboard

The project includes an interactive Excel dashboard designed to provide a management-level overview of sales and operational performance.

### Key Performance Indicators

The dashboard presents:

- Total Sales
- Total Profit
- Profit Margin
- Average Shipping Time

### Interactive Analysis

Users can filter the dashboard by dimensions including:

- Year
- Category
- Region
- Customer Segment

### Visualizations

The dashboard includes:

- Monthly Sales vs Profit Trend
- Profit by Market Region
- Profit Margin by Category
- Top Loss-Making Sub-Categories
- Average Shipping Time by Ship Mode
- On-Time vs Delayed Orders
- Priority Actions for the Next Quarter

---

<img width="1139" height="637" alt="image" src="https://github.com/user-attachments/assets/fde6f502-e10c-4c96-8971-c1d41c3c13f9" />


## Key Findings

The analysis identified several areas requiring management attention.

### Profitability

The analysis highlights significant differences in profitability across regions and product categories.

### Loss-Making Products

Several sub-categories contribute disproportionately to losses, creating opportunities for pricing, discount, cost, or product-level intervention.

### Operational Performance

Shipping performance varies by shipping mode, while a measurable proportion of orders are delayed.

### Regional Performance

Profitability is concentrated in stronger-performing regions, suggesting opportunities to prioritize investment and growth in profitable markets.

---

## Recommendations

Based on the analysis, the following actions were identified:

- Review pricing and discount strategies for loss-making sub-categories.
- Investigate the profitability of Tables, Bookcases, Phones, Chairs and Machines.
- Optimize Standard Class fulfilment to reduce delivery delays.
- Prioritize growth investment in stronger-performing regions.
- Review Furniture category profitability and identify opportunities for margin improvement.
- Target loss-making orders to reduce the proportion of unprofitable sales.

---

## Tools & Techniques

### Tools

- Microsoft Excel
- Power Query

### Analytical Techniques

- Data cleaning and transformation
- Data type validation
- Feature/column creation
- Descriptive analytics
- Trend analysis
- Profitability analysis
- Operational performance analysis
- KPI development
- Interactive dashboard design
- Business recommendations

---

## Project Workflow

```text
Business Questions
        ↓
Data Inspection
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Derived Metrics
        ↓
Exploratory Analysis
        ↓
Dashboard Development
        ↓
Insights
        ↓
Business Recommendations
