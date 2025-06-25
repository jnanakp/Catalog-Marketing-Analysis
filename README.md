# 🛍️ Catalog Marketing Analysis

This project analyzes over 137,000 customer orders from a multi-category catalog retailer to identify high-value customer segments, evaluate pricing and product strategies, and recommend data-driven actions for profitability improvement. Built as part of the **MKT-567: Marketing Metrics** course at USC Marshall School of Business.

---

## 📊 Project Overview

The goal was to develop two levels of interactive dashboards in Tableau:
- **Level 1 (CXO-level)**: High-level insights into market share, profitability, and strategic performance
- **Level 2 (Manager-level)**: Functional insights on customer behavior, pricing, logistics, and operational efficiency

Our focus category was **Category P**, and the analysis benchmarked performance against competing categories to guide marketing and operations teams.

---

## 🎯 Objectives

- Build L1 and L2 dashboards tailored for executives and mid-level managers
- Use RFM segmentation and pricing analytics to uncover actionable customer and product insights
- Identify key levers to optimize product mix, margin strategy, and customer value

---

## 📁 Dataset Summary

- 📦 **Orders**: 137,047  
- 👥 **Customers**: 100,000  
- 🛒 **Products**: 6,366 items across 18 categories  
- 💵 **Revenue**: $20.79M  
- 📈 **Profit**: $11.19M  
- 🗓️ **Date Granularity**: Daily

Key columns: `Customer_ID`, `Order_ID`, `Order_Date`, `Product_Name`, `Category`, `Price`, `Cost`, `Quantity`, `Revenue`, `Profit`, `Channel`, `Ship_Date`, etc.

---

## 🧩 Level-1 Dashboard (CXO-Level)

### 🔹 Focus:
- Market share and profitability trends
- Performance comparison with competitors (e.g., Categories C & E)
- Sales and profit breakdown by year, quarter, and channel

### 📊 Key Metrics:
- YOY Revenue & Profit Growth
- Relative Market Share
- Average Profit per Order / Customer
- Sales Volume and Gross Margin by Channel
- Category-level benchmarks vs. competitors

### 🧠 Insights:
- Category P underperformed competitors in profit/customer and order volume
- Opportunity identified in improving channel mix and category prioritization

---

## 🛠️ Level-2 Dashboard (Manager-Level)

### 🔹 Focus:
- Operational and tactical breakdowns for decision-making
- Customer segmentation, pricing, and delivery patterns

### 📊 Key Metrics:
- RFM Segments and Purchase Frequency
- Cancel/Return/Backorder Rates
- Sales by Zipcode, Gender, and Time
- Cross-Sell Patterns and Top SKUs
- Delivery Lag (Ship Date - Order Date)

### 🧠 Insights:
- Loyal customers concentrated in high-margin categories and specific zip codes
- Product availability and shipping delays affected sales velocity
- Price bands revealed elasticity in underperforming categories

---

## 💡 Business Recommendations

- Streamline product mix by reducing low-margin SKUs
- Target promotions toward high RFM segments via top-performing channels
- Improve delivery systems to reduce cart abandonment and cancellations
- Re-evaluate pricing tiers for better margin capture

---

## 📈 Technologies Used

- **Tableau** – Interactive dashboards (L1 & L2)
- **Excel** – Data cleaning and profit margin calculations
- **Python** (Optional – if used for segmentation)
- **PowerPoint** – Executive-level report presentation
