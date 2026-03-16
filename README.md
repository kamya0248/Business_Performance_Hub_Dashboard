# Business Insights 360 – Power BI Analytics Dashboard

⚠️ **Note:** Due to GitHub file size limitations, the Power BI `.pbix` file is hosted externally.

📥 **Download the full Power BI dashboard here:**  
[Download PBIX](https://drive.google.com/file/d/1i1iRga7PLa1Ro1NUZyZZxb7OUuyO_iQq/view?usp=sharing)

![Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiM2YzYzk1OTctYWMzZC00OTk4LWI3ZjktMDIwNmUzZjI1ODUwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=013d02798cc90688b0e7)

---

# Project Overview

**Business Insights 360** is an end-to-end business intelligence solution developed for **AtliQ Hardware**, a global hardware manufacturer, to enable leadership teams to make **data-driven decisions** across multiple business functions.

The company previously relied on **large Excel files and manual analysis**, which made it difficult for regional managers and executives to quickly analyze performance across markets. This project introduces a centralized **Power BI dashboard** that consolidates enterprise data and provides interactive insights into **Finance, Sales, Marketing, and Supply Chain operations**.

The solution enables leadership to **“start the day with analysis”**, quickly identify performance trends, and support strategic decisions such as pricing, promotions, supply chain planning, and product launches.

---

# Business Problem

AtliQ Hardware faced several operational challenges:

- Business decisions were primarily based on **manual Excel analysis**
- Data was **fragmented across multiple systems**
- Regional managers struggled to analyze performance across markets
- Lack of a **centralized analytics platform**
- Difficulty identifying trends in:
  - Revenue
  - Profitability
  - Market share
  - Forecast accuracy

---

# Solution

Develop a centralized **Power BI enterprise dashboard** that:

- Consolidates data from multiple sources
- Provides **real-time interactive analytics**
- Enables **cross-department insights**
- Supports **executive-level decision making**

The dashboard provides analytics across key business functions:

- Finance
- Sales
- Marketing
- Supply Chain
- Executive overview

---

# Dashboard Architecture

The Power BI solution is built using a **multi-page analytical dashboard** designed for different business stakeholders.

## Main Pages

### 1. Home Page
Navigation hub for accessing different analytical views.

### 2. Info Page
Contains dashboard documentation, refresh details, and system data sources.

### 3. Finance View
Financial performance analysis including **Profit & Loss reporting**.

### 4. Sales View
Customer and product performance analysis.

### 5. Marketing View
Market share and revenue trends across product segments.

### 6. Supply Chain View
Forecast accuracy and operational performance metrics.

### 7. Executive View
High-level strategic KPIs for leadership.

### 8. Support Page
User support, issue reporting, and documentation links.

---

# Key Business KPIs

The dashboard tracks several critical metrics used by leadership teams.

## Revenue Metrics

- Net Sales
- Gross Sales
- Revenue by Market
- Revenue by Channel

## Profitability Metrics

- Gross Margin %
- Net Profit %
- Cost of Goods Sold (COGS)

## Operational Metrics

- Forecast Accuracy %
- Net Error
- Absolute Error

## Market Metrics

- Market Share %
- Competitor comparison
- Regional growth

---

# Data Sources

The dashboard integrates data from multiple enterprise sources.

## Primary Data Sources

- MySQL Databases
- Enterprise sales and forecast systems

## Additional Sources

- Excel files
- CSV datasets

The dataset contains **millions of rows covering sales data from 2019 to 2025**.

---

# Data Model

The Power BI model follows a **Star Schema architecture**.

## Tables Used

- **Fact Tables:** 8  
- **Dimension Tables:** 7  
- **Support Tables:** 11  

### Key Fact Tables

- fact_sales_monthly
- fact_forecast_monthly
- fact_actuals_estimates
- manufacturing_cost
- freight_cost
- post_invoice_deductions
- operational_expense
- marketshare

### Key Dimension Tables

- dim_customer
- dim_product
- dim_market
- dim_date
- category
- fiscal_year
- sub_zone

This model supports **complex analytical queries** and efficient filtering across multiple business dimensions.

---

# Data Transformation

Data preparation and transformation were performed using **Power Query**.

Major transformation tasks included:

- Data cleaning
- Data type standardization
- Column creation
- Data reshaping
- Relationship building
- Integration of multiple data sources

---

# Key Features

The dashboard includes several advanced Power BI features.

## Interactive Filters

Users can slice data by:

- Region
- Market
- Customer
- Product category
- Time period

## Navigation System

Interactive navigation buttons allow users to move across views.

## Performance Matrix

Visual analysis of **product and customer profitability**.

## Benchmark Analysis

Compare performance against:

- Previous year
- Targets
- Benchmarks

## Market Share Analysis

Visual comparison between **AtliQ and competitors**.

## Forecast Accuracy Tracking

Supply chain analytics for **forecast reliability**.

---

# Example Insights

Using this dashboard, business leaders can answer questions such as:

- Which markets are driving the highest revenue growth?
- Which customers generate the highest margins?
- Which products are underperforming?
- How accurate are demand forecasts?
- Which regions have declining profitability?

---

# Tools & Technologies Used

- Power BI
- DAX
- Power Query
- MySQL
- Excel
- CSV Data Sources

---

# Screenshots

Dashboard screenshots can be found in the **`/screenshots`** folder.

Example pages include:

- Home Page
- Finance View
- Sales View
- Marketing View
- Supply Chain View
- Executive View

---

# Project Outcome

The **Business Insights 360** dashboard enables:

- Faster decision making
- Reduced manual reporting effort
- Improved financial visibility
- Better cross-department collaboration
- Data-driven strategy development

The project supports **AtliQ Hardware’s initiative to embed analytics into everyday business operations.**

---

# Author

**Kamya Bhardwaj**  
