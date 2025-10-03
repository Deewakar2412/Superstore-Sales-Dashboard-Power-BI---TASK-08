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

_Include an image of your final dashboard here for the best effect._
`[Image of the final Superstore Sales Dashboard]`

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
