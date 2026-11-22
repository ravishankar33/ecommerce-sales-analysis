# E-commerce Sales Analysis

## Objective
Analyze order data to understand sales performance by channel and over time.

## Data
- 138,116 orders and 46 columns (Kaggle e-commerce dataset)
- No duplicate rows
- Missing delivery days were limited to Cancelled, Pending and Returned orders, so they were left as null
- Empty return status values were filled with "Not Returned"
- Analysis uses Completed orders only (113,559), since the other statuses did not generate sales

## Key Findings
1. **Mobile App is the top channel** with 57.6M in sales, followed by Website (50.3M), Marketplace (21.8M) and Social Media (14.5M).
2. **Profit margin is about 41% across all channels.** Mobile App leads because of order volume, not better margins.
3. **Sales were flat from 2021 to 2025**, moving from 29.3M to 28.6M (a 2.5% drop). Order count fell only 0.7%, so most of the drop came from a lower average order value.
4. **Profit has a long upper tail:** a small number of orders earn far above the typical profit, and a few orders make a loss.

## Tools
Python, pandas, matplotlib

Dataset: https://www.kaggle.com/datasets/datascikhan/e-commerce-sales-and-customer-analytics
