# Retail Sales & Customer Analytics Using Python

## Project Overview
This project analyzes historical online retail transaction data to understand sales performance, product performance, customer purchasing behaviour, and customer value.

The analysis uses Python libraries to clean, transform, analyze, and visualize retail transaction data. It also applies RFM (Recency, Frequency, Monetary) analysis to group customers into meaningful segments.

## Business Objectives
- Analyze overall revenue, orders, and units sold.
- Identify monthly sales trends.
- Find top-performing products and countries.
- Understand one-time and repeat customer behaviour.
- Identify high-value customers using RFM analysis.
- Generate business insights and recommendations.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- JupyterLab

## Dataset
**Source:** UCI Machine Learning Repository – Online Retail Dataset

The dataset contains transactions from December 2010 to December 2011.

It includes invoice numbers, product descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

## Project Workflow
1. Loaded and explored the raw dataset.
2. Checked missing values, duplicate records, and invalid transactions.
3. Cleaned the sales data and calculated transaction revenue.
4. Analyzed overall sales and monthly revenue.
5. Identified top products and countries.
6. Analyzed customer purchase frequency and revenue.
7. Performed RFM customer segmentation.
8. Compared revenue and order value across customer segments.
9. Created visualizations to communicate the findings.
10. Developed business recommendations.

## Key Business Results

| Metric | Result |
|---|---:|
| Total Revenue | £10,642,110.80 |
| Total Orders | 19,960 |
| Identified Customers | 4,338 |
| Units Sold | 5,572,420 |
| Average Order Value | £533.17 |
| Repeat Customers | 65.58% |
| UK Revenue Contribution | 84.59% |

## Key Insights
- November 2011 recorded the highest monthly revenue.
- The Regency Cake Stand 3 Tier was the highest-revenue merchandise product after excluding selected postage and manual entries.
- The United Kingdom contributed approximately 84.59% of total sales revenue.
- Approximately 65.58% of identified customers made more than one purchase during the observed period.
- Champions represented approximately 8% of identified customers and generated 43.85% of identified-customer revenue.
- Champions had the highest average order value among the customer segments.

## Customer Segmentation
RFM analysis was used to segment customers based on:
- **Recency:** How recently a customer purchased.
- **Frequency:** How often a customer purchased.
- **Monetary:** How much a customer spent.

The project uses the following segments:
- Champions
- Loyal Customers
- Potential Loyalists
- New Customers
- At Risk
- Lost Customers
- Needs Attention

## Business Recommendations
- Introduce loyalty rewards and personalized offers for high-value customers.
- Run targeted campaigns to encourage inactive customers to purchase again.
- Improve the customer experience to increase repeat purchases.
- Explore opportunities to grow sales in markets outside the United Kingdom.
- Promote popular merchandise products.
- Use historical monthly sales patterns to support inventory and marketing planning.

## Project Structure
```text
Retail-Sales-Customer-Analytics-Python/
├── data/
│   ├── Online Retail.xlsx
│   ├── cleaned_retail_data.csv
│   ├── customer_rfm.csv
│   └── order_analysis.csv
├── notebooks/
│   └── retail_sales_analysis.ipynb
├── outputs/
│   └── Analysis charts (.png)
└── README.md
```

## Important Notes
- The analysis uses historical data from 2010–2011 and does not represent current retail performance.
- Customer-level analysis excludes transactions without a CustomerID.
- Overall sales metrics include valid sales transactions with and without a CustomerID.
- The repeat-customer metric measures repeat purchases within the observed dataset period; it is not a formal cohort-retention calculation.
- December 2011 contains only partial-month data.
- RFM segment definitions are starter business rules created for this project.

## Author
**Chandan Prasad**

GitHub: [Chandanprasad7](https://github.com/Chandanprasad7)