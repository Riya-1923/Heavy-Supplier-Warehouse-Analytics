# Heavy Supplier, Inventory & Warehouse Analytics

## Project Overview

This project is part of the CadetX Virtual Work Experience Programme.

The objective is to analyze warehouse, inventory, supplier, customer, and sales data to improve inventory management, warehouse efficiency, supplier performance, and demand forecasting using Data Analytics and Data Science techniques.

## Team Members

- BI Analyst

## Progress

### ✅ Week 1 – Data Exploration

- Repository setup
- Data loading
- Dataset profiling
- Data quality assessment
- Exploratory Data Analysis (EDA)
- Business questions
- KPI identification

### ✅ Week 2 – Data Cleaning & Preparation

- Standardized column names
- Removed duplicate records
- Handled missing values
- Cleaned text fields
- Converted date columns
- Data quality validation
- Saved cleaned datasets

### ✅ Week 3 – Product & Inventory Analysis

- Product summary
- Inventory valuation
- Category-wise inventory analysis
- Fast-moving products
- Slow-moving products
- ABC (Pareto) classification
- Inventory health assessment
- Business recommendations

### ✅ Week 4 – Warehouse Operations & Efficiency

- Warehouse stock summary
- Warehouse capacity analysis
- Warehouse utilization analysis
- Stock movement analysis
- Product category distribution
- Operational bottleneck detection
- KPI dashboard
- Business recommendations

### ✅ Week 5 – Inventory Health & Turnover Analytics

- Inventory value analysis
- Inventory turnover calculation
- Fast-moving product identification
- Slow-moving product analysis
- Dead stock detection
- Inventory aging analysis
- ABC (Pareto) classification
- Reorder and safety stock analysis
- KPI dashboard
- Business recommendations

### ✅ Week 6 – Advanced Inventory Analytics

- Inventory availability analysis
- Stock status classification
- Product criticality analysis
- Category-wise inventory analysis
- Branch performance scoring
- Warehouse utilization analysis
- Operational risk dashboard
- KPI dashboard
- Business recommendations

### ✅ Week 7 – Supplier & Procurement Analytics

- Supplier contribution analysis
- Procurement value analysis
- Purchase order analysis
- Supplier reliability analysis
- Supplier delivery performance
- Supplier dependency risk
- Critical product supplier analysis
- Supplier KPI dashboard
- Business recommendations

### ✅ Week 8 – Customer Analytics & Segmentation

- Customer profile analysis
- Customer purchase behaviour analysis
- Customer recency, frequency and monetary (RFM) analysis
- RFM scoring and customer segmentation
- Champion customer identification
- Loyal customer analysis
- Potential customer analysis
- At-risk customer identification
- Inactive customer analysis
- High-value customer analysis
- Customer analysis by industry segment
- Customer analysis by region
- Customer analysis by branch
- Sales channel analysis
- Customer KPI dashboard
- Business insights and recommendations

### ✅ Week 9 – Predictive Customer Analytics

- Customer revenue analysis
- Customer purchase frequency analysis
- Customer lifespan analysis
- Customer Lifetime Value (CLV) estimation
- CLV-based customer segmentation
- Customer churn indicator analysis
- Customer risk scoring
- Customer risk segmentation
- High-value customer risk analysis
- Retention opportunity analysis
- Industry-level customer risk analysis
- Regional customer risk analysis
- Branch-level customer risk analysis
- Predictive customer KPI dashboard
- Customer value visualization
- Customer risk visualization
- Business insights and recommendations

### ✅ Week 10 – BI & KPI Integration Dashboard

* Integrated key findings from Weeks 1–9 into one Power BI dashboard
* Combined Inventory, Warehouse, Supplier, Procurement, and Customer analytics
* Integrated customer RFM and predictive customer analytics
* Added KPI cards for overall business performance
* Added interactive slicers for:

  * Region
  * Branch
  * Product Category
  * Supplier
  * Customer Type
  * Customer Segment
  * Customer Risk Level
  * Year
* Added business performance charts
* Added inventory and warehouse analysis visuals
* Added supplier and procurement analysis visuals
* Added customer segmentation and customer risk visuals
* Added estimated Customer Lifetime Value (CLV) analysis
* Added high-value customer risk analysis
* Added key business insights section
* Added detailed customer and supplier analysis tables
* Created a consolidated BI dashboard for overall project analysis
* Prepared final project documentation and GitHub repository

## Dataset

The project consists of 12 CSV datasets:

- branches.csv
- customer_analystics.csv
- customer_branch_analysis.csv
- customer_channel_analysis.csv
- customer_clv_analysis.csv
- customer_risk_final.csv
- customer_segment_summary.csv
- customers.csv
- inventory.csv
- invoices.csv
- payments.csv
- products.csv
- purchase_header.csv
- purchase_lines.csv
- sales_header.csv
- sales_lines.csv
- stock_ledger.csv
- suppliers.csv

## Repository Structure
```text
Heavy-Supplier-Warehouse-Analytics/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   ├── Week1_Data_Exploration.ipynb
│   ├── Week2_Data_Cleaning.ipynb
│   ├── Week3_Product_Inventory_Analysis.ipynb
│   ├── Week4_Warehouse_Analytics.ipynb
│   ├── Week5_Inventory_Health_Analytics.ipynb
│   ├── Week6_Advanced_Inventory_Analytics.ipynb
│   ├── Week7_Supplier_Procurement_Analytics.ipynb
│   ├── Week8_Customer_Analytics.ipynb
│   └── Week9_Predictive_Customer_Analytics.ipynb
│
├── Power Bi/ 
│   ├──dashboard.pdf
│   └── Week10_BI_KPI_Integration_Dashboard.pbix
│
├── docs/
│   ├── Data_Dictionary.md
│   ├── Data_Quality_Report.md
│   ├── Data_Cleaning_Report.md
│   ├── Product_Inventory_Report.md
│   ├── Warehouse_Analytics_Report.md
│   ├── Inventory_Health_Report.md
│   ├── Advanced_Inventory_Report.md
│   ├── Supplier_Procurement_Report.md
│   ├── Predictive_Customer_Analytics_Report.md
│   └── BI_KPI_Dashboard_Report.md
│
├── sprint-notes/
│   ├── Week1.md
│   ├── Week2.md
│   ├── Week3.md
│   ├── Week4.md
│   ├── Week5.md
│   ├── Week6.md
│   ├── Week7.md
│   ├── Week8.md
│   ├── Week9.md
│   └── Week10.md
│
└── README.md
```

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git
- GitHub