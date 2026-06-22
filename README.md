# Financial Dashboard — Power BI Project

![Financial Dashboard Preview](./assets/financial-dashboard-preview.png)

## 📌 Project Overview

This Power BI project presents an interactive **Financial Dashboard** designed to analyze business performance across sales, orders, profit, profit margin, discounts, countries, customer segments, and products. The dashboard helps stakeholders quickly understand key performance indicators, compare current year performance with the prior year, and identify profitable segments and top-selling products.

📄 **Dashboard PDF:** [View Financial Dashboard PDF](./Financial_Dashboard.pdf)

> **Note:** Add your exported Power BI PDF to the repository with the exact name `Financial_Dashboard.pdf` so the link above works correctly on GitHub.

## 🎯 Objective

The main objective of this dashboard is to provide a clear financial performance summary that supports business decision-making by answering questions such as:

- How are sales, orders, profit, profit margin, and discounts performing compared with the previous year?
- Which countries contribute the most to orders and profit margin?
- Which discount bands are used most frequently?
- Which customer segments and products are most profitable?
- Which products generate the highest sales?
- How does sales performance change over time?

## 📊 Key Performance Indicators

The dashboard highlights the following KPIs:

| KPI | Current Value | Prior Year Comparison |
|---|---:|---:|
| Sales | 92,311,095 | +249.46% |
| Orders | 861,132 | +225.36% |
| Profit | 13,015,238 | +235.58% |
| Profit Margin | 14.1% | -3.97% |
| Discount | 7,059,717 | +229.04% |

## 🧩 Dashboard Features

### KPI Cards
Shows high-level business performance for sales, orders, profit, profit margin, and discount with current year versus prior year comparison.

### Country-Level Analysis
Includes order volume and profit margin by country, covering countries such as Canada, France, United States, Mexico, and Germany.

### Discount Band Breakdown
Displays percentage share by discount band, helping understand how discounting is distributed across low, medium, and high discount categories.

### Segment and Product Profitability
Shows profit margin by customer segment and product, making it easier to identify strong and weak performing combinations.

### Sales Trend
Visualizes sales amount by year and month to identify seasonal movement and performance trends over time.

### Top Products by Sales
Highlights the top three products by sales, including Paseo, VTT, and Velo.

## 🔍 Key Insights

- Sales, orders, profit, and discount increased significantly compared with the previous year.
- Overall profit margin is positive, but it declined slightly compared with the prior year.
- Channel Partners is the most profitable segment shown in the dashboard.
- Enterprise shows negative profit margin, indicating a potential area for review.
- Paseo is the top-selling product by sales amount.
- Medium and high discount bands make up a large share of total discounts.

## 🛠️ Tools Used

- **Power BI Desktop** — dashboard design, data modeling, and visualization
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures and KPI logic
- **GitHub** — project documentation and version control

## 📁 Recommended Repository Structure

```text
Financial-Dashboard-PowerBI/
│
├── README.md
├── Financial_Dashboard.pbix
├── Financial_Dashboard.pdf
│
├── assets/
│   └── financial-dashboard-preview.png
│
└── data/
    └── financial_data.csv
```

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Open `Financial_Dashboard.pbix` in Power BI Desktop.
3. Review the data model, Power Query transformations, and DAX measures.
4. Interact with filters and visuals to explore financial performance.
5. Open `Financial_Dashboard.pdf` for a static dashboard report view.

## 📌 Suggested GitHub Upload Steps

1. Export the Power BI report as a PDF and rename it to `Financial_Dashboard.pdf`.
2. Save the dashboard screenshot as `assets/financial-dashboard-preview.png`.
3. Add the `.pbix`, `.pdf`, screenshot, and `README.md` files to your repository.
4. Commit and push the files to GitHub.

Example commands:

```bash
git add README.md Financial_Dashboard.pbix Financial_Dashboard.pdf assets/financial-dashboard-preview.png
git commit -m "Add Power BI financial dashboard project"
git push origin main
```

## 📈 Business Value

This dashboard provides a single view of financial performance and helps business users monitor growth, profitability, product performance, discount usage, and regional contribution. It can support sales planning, pricing decisions, discount strategy, and profitability improvement initiatives.

## 🔮 Future Enhancements

- Add slicers for year, country, segment, and product.
- Add drill-through pages for country and product-level details.
- Include target versus actual performance metrics.
- Add forecasting for future sales and profit.
- Improve mobile dashboard layout for easier viewing on smaller screens.

## 👤 Author

**Your Name**  
Power BI Developer / Data Analyst

## 📄 License

This project is available for learning, portfolio, and demonstration purposes. Update this section with your preferred license before publishing.
