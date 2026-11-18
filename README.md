# Retail Returns EDA: Impact on Sales and Financial Outcomes

## Project Overview
This project explores how product returns affect retail sales performance and financial outcomes using a synthetic e-commerce dataset.

The objective is to analyse return patterns, quantify the financial value of returned items and identify areas where businesses can improve their return management.

## Research Question
**How do product returns affect retail sales performance and financial outcomes?**

## Dataset
The project uses a synthetic e-commerce dataset from [SQLShed](https://sqlshed.com/practice-datasets/ecommerce-orders/).

It contains seven related tables:

| Table | Rows | Description |
|---|---:|---|
| categories | 24 | Product categories |
| customers | 12,000 | Customer information |
| products | 2,000 | Product details |
| orders | 90,000 | Order information |
| order_items | 215,000 | Individual items in orders |
| payments | 95,000 | Payment records |
| returns | 12,000 | Product return records |

**Total records:** 426,024

The tables are connected through logical relationships using customer, order, product, category and order-item identifiers.

## Project Workflow

1. **Phase 1 – Data Inspection and Understanding**
2. **Phase 2 – Data Cleaning and Validation**
3. **Phase 3 – Exploratory Data Analysis**
4. **Phase 4 – Business Insights and Recommendations**
5. **Phase 5 – Final Presentation and Documentation**

## Key Findings

- The overall item return rate was approximately **5.58%**.
- The returned net item value was approximately **493,541.42**.
- The most common return reason was `changed_mind` (31.16%).
- Damaged and not-as-described products together accounted for approximately **52.05%** of returns.
- Sprinklers had the highest category return rate at approximately **6.11%**.
- Power Tools had the lowest category return rate at approximately **4.89%**.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Limitations

- The dataset is synthetic and does not represent actual transactions from a real retailer.
- Return timestamps contain inconsistencies, including records dated before their corresponding orders.
- Refund value does not directly represent profit loss.
- Product recovery, handling costs and resale outcomes were not fully evaluated.

## Project Files

- **Notebook:** Complete analysis and visualisations.
- **Report:** Detailed project documentation.
- **Presentation:** Summary of findings and recommendations.

## Conclusion

This analysis examines product return patterns and their relationship with retail sales and financial outcomes. It identifies common return reasons, category-level differences and the financial value associated with returned items.

The findings can help demonstrate how exploratory data analysis can support better return management and business decision-making.
