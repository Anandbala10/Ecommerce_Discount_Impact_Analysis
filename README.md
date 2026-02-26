# Quarterly E-commerce Sales Performance & Discount Impact Analysis

## Objective
Conducted an in-depth Q4 2024 sales performance analysis to evaluate revenue trends, discount strategies, and return behavior for an e-commerce business. The goal was to identify revenue leakage, profitability risks, and high-impact operational insights.

---

## Dataset Overview
- Transaction-level sales data
- Order details, discount %, payment mode
- Return status & return reasons
- Product category & SKU-level information
- Q4 2024 time period

---

## Key Metrics Computed

| Metric | Value |
|--------|-------|
| Gross Merchandise Value (GMV) | ₹10,23,789 |
| Net Revenue | ₹9,09,607 |
| Average Order Value (AOV) | ₹2,621 |
| Total Returns | 180 |
| Return Rate | ~55% (Delivered Orders Basis) |

---

## Analysis Performed

- Revenue segmentation by category and SKU
- Weekly trend analysis using derived `Week_Start`
- Return rate calculation using conditional aggregation
- Discount effectiveness analysis across orders
- Identification of top-performing SKUs
- Revenue leakage assessment due to returns

---

## Key Insights

- ~55% return rate significantly reduced realized revenue despite strong GMV.
- Heavy discount periods showed increased order volume but reduced net profitability.
- Top 5 SKUs contributed a disproportionate share of total GMV.
- Certain categories exhibited higher-than-average return rates, indicating quality or expectation mismatches.
- Revenue concentration risk observed in limited product segments.

---

## Tools & Techniques Used

- Microsoft Excel
- Pivot Tables
- Advanced Excel formulas (SUMIFS, COUNTIFS, IF, WEEK-based aggregation)
- Data cleaning & anomaly correction (e.g., date validation issues)
- Descriptive and trend analysis

---

## Business Impact

This analysis highlights how high return rates and aggressive discounting can mask underlying profitability risks. The findings support strategic pricing optimization, return policy evaluation, and SKU-level inventory prioritization.

---

## Repository Structure

Ecommerce_Discount_Impact_Analysis/
│
├── data/
│ └── Ecommerce_Sales_Performance_Q4_2024.xlsx
├── visuals/
│ └── ORDERvsRETURN.png
│ └── TOP_5_SKUs.png
├── README.md
