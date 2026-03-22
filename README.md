# Sales Insights Analyzer

## Overview

This project performs an end-to-end exploratory data analysis (EDA) on the Superstore Orders dataset using Python and Pandas. It uncovers key patterns in sales performance, profitability, customer segmentation, and regional distribution across a four-year period (2014–2017). The analysis provides actionable insights to support business decision-making in retail operations.

---

## Objectives

- Explore and understand the structure and quality of the sales dataset
- Identify high-performing customer segments, product categories, and regions
- Analyze temporal trends in sales and profit across months and years
- Apply filtering and aggregation techniques to surface key business insights
- Visualize trends using Matplotlib

---

## Dataset

- **Source:** Superstore Orders Dataset (publicly available)
- **Records:** 9,994 rows × 21 columns
- **Date Range:** January 2014 – December 2017
- **Key Fields:** Order Date, Ship Date, Ship Mode, Customer Segment, Region, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit
- **Data Quality:** No missing values across all columns

---

## Key Insights

- **Regional Sales Performance:** The West region recorded the highest total sales at 725,457, followed by the East at 678,781. The South region had the lowest total sales at 391,721, indicating potential for targeted growth initiatives.

- **Customer Segment Profitability:** The Consumer segment generated the highest total profit at 134,119, followed by Corporate at 91,979 and Home Office at 60,298. Despite having fewer transactions, the Home Office segment recorded the highest average profit per order at 33.82.

- **Monthly Sales Trend:** Sales peaked in January and February, with a notable dip in June. A second recovery was observed from August onwards, suggesting seasonal demand patterns relevant for inventory planning.

- **High-Value Orders:** 468 out of 9,994 orders had individual sales exceeding 1,000 units of currency, representing high-ticket transactions primarily in Furniture and Technology categories.

- **Profitable Orders:** Approximately 80.6% of all orders (8,058 out of 9,994) recorded a positive profit, while the remaining 19.4% resulted in losses, often associated with high discount rates.

- **Discount Analysis:** No orders in the dataset had a discount exceeding 90%, confirming that heavy discounting (above 0.9) was not practiced. Losses were largely tied to discounts in the 0.45–0.8 range, particularly in the Furniture category.

---

## Tools and Technologies

- **Python 3** — Core programming language
- **Pandas** — Data loading, cleaning, filtering, and aggregation
- **Matplotlib** — Data visualization (line charts, bar charts, pie charts)
- **Google Colab** — Development and execution environment

---

## Analysis Performed

- Data loading and initial exploration (head, tail, info, describe, sample)
- Date conversion for Order Date and Ship Date columns
- Conditional filtering: Sales > 1000, Profit > 0, Quantity > 4, Region = "South"
- GroupBy aggregations: Sales by Region, Profit by Segment (sum and descriptive statistics)
- Monthly Sales trend visualization
- Daily Profit trend visualization
- Yearly Sales trend visualization (line, bar, and pie charts)

---

## Project Structure

```
Sales-Insights-Analyzer/
│
├── Sales_Insights_Analyzer.ipynb   # Main analysis notebook
└── README.md                       # Project documentation
```

---

## How to Run

1. Clone the repository or download the notebook file.
2. Upload `orders.csv` to your Google Drive under `MyDrive/python data set/`.
3. Open `Sales_Insights_Analyzer.ipynb` in Google Colab.
4. Run all cells sequentially to reproduce the analysis and visualizations.

---

## Author

**Tharun Kumar Srinivasan**  
Aspiring Data Analyst | Python | Power BI | SQL  
[LinkedIn](https://www.linkedin.com/in/tharunkumarsrini/) | [GitHub](https://github.com/Tharun-Design)

---

## License

This project is intended for educational and portfolio purposes only. The dataset used is publicly available and does not represent any proprietary business data.
