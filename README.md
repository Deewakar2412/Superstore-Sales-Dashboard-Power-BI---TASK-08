# Superstore Sales Analysis Dashboard

## Project Overview

This project presents a comprehensive sales and profitability analysis for a global superstore. Using data from thousands of international orders, this interactive dashboard provides key insights into sales trends, product performance, market distribution, and the impact of returns and discounts. The primary goal is to identify key business drivers, pinpoint areas of unprofitability, and provide actionable data to inform strategic decisions.

This repository includes the raw data, the final dashboard design, and custom theme files for easy replication and further analysis in BI tools like Power BI or Tableau.

---

## 📊 Data Sources

The analysis is based on three primary CSV files:

* `Orders.csv`: Contains detailed records of each customer order, including order dates, product information, sales figures, profit, and customer details.
* `Returns.csv`: Contains a list of all returned orders and the corresponding market.
* `People.csv`: Maps regional managers to their respective regions.

---

## 🚀 Dashboard Overview

The final dashboard is split into two main pages for a clear, story-driven analysis:

1.  **Executive Summary:** A high-level overview of the business's health, focusing on key performance indicators (KPIs) and global sales trends.
2.  **Profitability Deep Dive:** A detailed analysis page designed to uncover the root causes of profitability issues, focusing on product categories, discounts, and returns.

**Here is the main dashboard view:**
http://googleusercontent.com/image_generation_content/2



---

## 🛠️ Installation and Usage

To use this dashboard and its custom themes, follow these steps:

1.  **Load Data:** Import the `Orders.csv`, `Returns.csv`, and `People.csv` files into your preferred BI tool (e.g., Power BI, Tableau).
2.  **Establish Relationships:** Create a relationship between the `Orders` table and the `Returns` table using `Order ID` as the key.
3.  **Build Visuals:** Recreate the charts and KPIs as shown in the dashboard images. The necessary formulas (Measures/Calculated Fields) are provided in the analysis.
4.  **Apply Theme (Optional):** To apply the custom theme, follow the instructions in the "Dashboard Themes" section below.

---

## 🎨 Dashboard Themes

This project includes custom JSON theme files to ensure a consistent and professional design. The recommended theme is the **High-Contrast Dark Mode**, which is modern, sleek, and easy on the eyes.

### How to Use the Theme File:

1.  **Download:** Download the `dark_theme.json` file from this repository.
2.  **Import into Power BI:**
    * Go to the **View** tab in the Power BI ribbon.
    * Click the dropdown arrow in the **Themes** section.
    * Select **Browse for themes**.
    * Open the downloaded `dark_theme.json` file.
3.  The theme will be automatically applied to your entire report.

---

## 📈 Key Metrics (KPIs)

The main dashboard page highlights five critical KPIs for a quick business health check:

* **Total Sales:** The total revenue generated from all sales.
* **Total Profit:** The absolute profit after all costs and discounts.
* **Profit Ratio:** The percentage of sales that is converted into profit.
* **Average Discount:** The average discount rate applied to all orders.
* **Return Rate %:** The percentage of total orders that were returned by customers.

---

## 🔎 Visualizations and Insights

### Page 1: Executive Summary

* **Monthly Sales & Profit Trend:** A line chart that tracks performance over time, helping to identify seasonal trends and the overall growth trajectory.
* **Sales by Global Market (Map):** A world map that visualizes the geographic distribution of sales, highlighting key international markets.

### Page 2: Profitability Deep Dive

* **Profit by Sub-Category:** A horizontal bar chart that clearly identifies the most and least profitable product categories. Unprofitable categories are highlighted in a different color for immediate attention.
* **Returns by Sub-Category:** Complements the profit chart by showing which products are most frequently returned, helping to diagnose if losses are due to quality issues or pricing strategy.
* **Profit vs. Discount (Scatter Plot):** A powerful scatter plot that visualizes the relationship between discounts and profitability for each sub-category, answering the question: "At what point do discounts make our products unprofitable?"

---

## 🤝 How to Contribute

Contributions are welcome! If you have suggestions for improving the dashboard, adding new analyses, or refining the data model, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeatureName`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some amazing feature'`).
5.  Push to the branch (`git push origin feature/YourFeatureName`).
6.  Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
