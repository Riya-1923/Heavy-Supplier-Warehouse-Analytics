# Predictive Customer Analytics

## Overview

Week 9 focuses on **predictive customer analytics** using historical sales and customer data. The analysis aims to understand customer purchasing behavior, estimate customer lifetime value, identify potential churn, and prioritize customers for retention efforts.

## Objectives

The main objectives of this analysis are to:

* Analyze customer revenue and purchase frequency
* Calculate customer lifespan
* Estimate Customer Lifetime Value (CLV)
* Identify potential churn risk
* Create customer risk scores
* Identify high-value customers who may be at risk
* Analyze potential customer retention opportunities

---

## 1. Customer Lifetime Value (CLV)

Customer Lifetime Value (CLV) was estimated using Average Order Value (AOV) and annual purchase frequency.

### CLV Formula

**Estimated CLV = Average Order Value × Annual Purchase Frequency**

Customers were then grouped into four CLV categories:

* **Low CLV**
* **Medium CLV**
* **High CLV**
* **Very High CLV**

This segmentation helps identify customers who generate greater revenue and may require different engagement and retention strategies.

---

## 2. Churn Risk Analysis

Customer recency was used as an indicator of potential churn risk. Recency measures the number of days since a customer's most recent purchase.

| Recency           | Churn Risk     |
| ----------------- | -------------- |
| 0–30 days         | Low Risk       |
| 31–60 days        | Moderate Risk  |
| 61–90 days        | High Risk      |
| More than 90 days | Very High Risk |

Customers with longer periods since their last purchase were considered more likely to require retention attention.

---

## 3. Customer Risk Scoring

A customer risk score was created using three key factors:

* **Recency** — How recently the customer made a purchase
* **Purchase Frequency** — How often the customer purchases
* **Customer Value** — The customer's revenue or estimated CLV

Combining these factors provides a broader view of customer health.

Customers with **high customer value and elevated churn risk** were identified as important retention opportunities.

---

## 4. Business Insights

The analysis provides several useful business insights:

* High-value customers with elevated churn risk should be monitored closely.
* Low purchase frequency may indicate potential customer disengagement.
* CLV can help prioritize customer engagement and retention activities.
* Risk scores can be used to segment customers based on their likelihood of disengagement.
* Customer risk and value can be compared across different industries, regions, and branches.
* Combining customer value with churn risk can help identify customers who may have a significant impact on future revenue.

---

## 5. Analysis Outputs

The following cleaned datasets were generated as part of the analysis:

```text
data/cleaned/customer_clv_analysis.csv
data/cleaned/customer_churn_analysis.csv
data/cleaned/customer_risk_scores.csv
data/cleaned/customer_predictive_summary.csv
```

### Output Files

| File                              | Description                                           |
| --------------------------------- | ----------------------------------------------------- |
| `customer_clv_analysis.csv`       | Customer-level CLV calculations and value segments    |
| `customer_churn_analysis.csv`     | Customer recency and churn-risk analysis              |
| `customer_risk_scores.csv`        | Combined customer risk scores                         |
| `customer_predictive_summary.csv` | Summary of customer value and predictive risk metrics |

---

## 6. Conclusion

Week 9 extends traditional customer analytics into **predictive value and risk analysis**. By combining customer revenue, purchase frequency, recency, CLV, and risk scores, businesses can better understand customer behavior and identify potential retention opportunities.

The analysis provides a foundation for future predictive analytics, including more advanced **customer churn prediction, retention modeling, and customer segmentation**.
