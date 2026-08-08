# Cafe Sales Executive Dashboard (Looker Studio)

## Executive Overview
This interactive dashboard translates cleaned sales transaction data into executive-level business intelligence using Looker Studio. Designed for cafe operational leads and decision-makers, it provides real-time visibility into overall revenue performance, product demand, payment channel preferences, and core sales metrics across the 2023 financial year.

---

## Live Dashboard & Screenshot
🔗 **[https://github.com/Omotayo1460/Cafe_Sales_SQL_EDA](#)**

---

## Executive Key Performance Indicators (KPIs)
Based on full-year transactional data analyzed in the dashboard:
- **Total Revenue**: **$88,952.00** generated across all locations and products.
- **Total Orders**: **10,000** completed transactions.
- **Total Quantity Sold**: **30,141** individual items.
- **Average Order Value (AOV)**: **$8.90** per transaction.
- **Top Fulfilling Channel**: **In-Store** dining generated the highest overall volume compared to takeaway orders.

---

## Key Dashboard Sections & Business Findings

### 1. Monthly Revenue Performance Over Time
- **Trend Analysis**: Revenue displays strong stability throughout 2023, averaging approximately **$7,000 to $7,500 monthly**.
- **Peak Months**: Modest sales surges occurred in **June 2023** and **October 2023**, while **February 2023** and **July 2023** saw minor dips.

### 2. Top Products by Revenue
- **Primary Revenue Driver**: **Salad** generated the highest overall revenue, nearing **$19,000** (more than double any individual drink item).
- **Food vs. Beverage Insights**: High-value food items (**Salad**, **Sandwich**, **Smoothie**) led overall revenue contribution, while core beverages (**Coffee**, **Tea**, **Juice**) contributed high transaction frequency at lower individual price points.
- **Product Ranking**: 
  1. Salad
  2. Sandwich
  3. Smoothie
  4. Juice
  5. Cake
  6. Coffee
  7. Tea
  8. Unknown Items
  9. Cookie

### 3. Customer Payment Preferences
- **Others**: **31.2%** (Includes secondary and alternative payment methods)
- **Credit Card**: **23.0%**
- **Digital Wallet**: **22.9%**
- **Cash**: **22.9%**
- **Takeaway**: Modern payment channels (Credit Card, Digital Wallet, Cash) share an almost equal 23% slice of customer preferences, highlighting the need to support multi-channel POS checkouts.

---

## Project Structure
```text
cafe-sales-lookerstudio-dashboard/
├── dashboard/
│   └── dashboard_screenshot.png    # High-resolution executive dashboard export
├── data/
│   └── cleaned_cafe_sales.csv      # Cleaned backend dataset
└── README.md                       # Comprehensive documentation & analytical findings

