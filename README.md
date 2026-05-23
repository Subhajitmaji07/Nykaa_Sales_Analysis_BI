# 💄 Nykaa Sales Analysis Dashboard

A multi-page **Power BI** dashboard analyzing Nykaa's beauty & personal care sales data across products, categories, cities, customer demographics, profit margins, and return trends.

---

## 📊 Dashboard Overview

The report is divided into **three interactive pages**:

| Page | Focus |
|------|-------|
| Product Analysis | Sales by product, category & monthly trends |
| Profit & Return Insights | Profitability, margins & return behavior |
| Customer & Regional Insights | City-wise sales, age groups & demographics |

---

## 🗂️ Pages at a Glance

### 1. Product Analysis

**KPIs:** Total Sales — 5M | Total Profit — 1.15M | Total Orders — 2K | Total Returns — 200

- **Top-selling products:** Lakme Lipstick leads, followed by Maybelline Mascara and Plum Serum
- **Category breakdown:** Skincare (~3M) > Makeup (~2M) > Haircare (~0.5M)
- **Monthly trend:** Sales peak around March and May, with relative stability across the year (~0.4M–0.5M/month)
- **Filters available:** Year, Category, Product

---

### 2. Profit & Return Insights

**KPIs:** Total Profit — 1.15M | Return % — 10.0% | Profit Margin — 22.3%

- **Sales vs. Profit by Category:** Skincare dominates both sales and profit; Haircare lags
- **Return by Category (Donut Chart):**
  - Skincare: 97 returns (48.5%)
  - Makeup: 88 returns (44%)
  - Haircare: 15 returns (7.5%)
- **Return Reasons:**
  - Wrong Item: ~68 (highest)
  - Damaged: ~65
  - Quality Issue: ~60
- **Profit Margin by Category:** All three categories maintain a roughly uniform ~20% margin

---

### 3. Customer & Regional Insights

**KPIs:** Total Customers — 300 | Total Orders — 2K | Total Sales — 5M

- **Top Cities by Sales:** Jaipur > Delhi > Mumbai > Surat > Lucknow
- **Sales by Age Group:** 46–55 generates the highest sales; 18–25 and 26–35 are close competitors
- **Filters:** Gender (Male / Female), Region (East / North / South / West), Membership Type (Gold / Platinum / Regular)
- **Map View:** City and region distribution across India

**Final Conclusion (from dashboard):**
> Overall sales performance is strong, with Jaipur emerging as the highest revenue-contributing city. The 46–55 age group generates the highest sale. Female customers contribute slightly higher sales, while product returns continue to impact overall profitability. Reducing return rates and strengthening focus on high-performing cities can significantly enhance profit growth.

---

## 🛠️ Tech Stack

- **Tool:** Microsoft Power BI Desktop
- **File:** `Nykaa_Sales_Analysis.pbix`
- **Data:** Simulated / sample Nykaa-style retail dataset
- **Visuals used:** Bar charts, Donut chart, Line chart, Map, KPI cards, Slicers

---

## 📁 Repository Structure

```
Nykaa-Sales-Analysis/
│
├── Nykaa_Sales_Analysis.pbix        # Power BI report file
├── README.md                        # Project documentation
│
└── screenshots/
    ├── Product_Analysis.png
    ├── Profit___Return_Insights.png
    └── Customer___Regional_Insights.png
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/nykaa-sales-analysis.git
   ```

2. **Open the report**
   - Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
   - Open `Nykaa_Sales_Analysis.pbix`

3. **Explore the dashboard**
   - Use the tab navigation at the bottom to switch between pages
   - Apply slicers (Year, Category, Gender, Region, Membership Type) for filtered insights

---

## 📌 Key Insights Summary

| Metric | Value |
|--------|-------|
| Total Sales | ₹5 Million |
| Total Profit | ₹1.15 Million |
| Profit Margin | 22.3% |
| Total Orders | 2,000 |
| Total Returns | 200 |
| Return Rate | 10.0% |
| Total Customers | 300 |
| Top City | Jaipur |
| Top Category | Skincare |
| Top Product | Lakme Lipstick |

---

## 📈 Business Recommendations

- **Reduce returns** — "Wrong Item" is the #1 return reason; improving order fulfillment accuracy can directly boost net profit
- **Double down on Jaipur & Delhi** — These cities drive the highest revenue and deserve targeted campaigns
- **Engage the 46–55 age segment** — Highest-spending cohort; loyalty programs and premium SKUs could increase LTV
- **Grow Haircare** — Significantly underperforms Skincare and Makeup; opportunity for category expansion
- **Leverage Skincare margins** — Strong sales AND healthy margins make it the core profit engine

---

## 🙌 Acknowledgements

- Dataset inspired by [Nykaa](https://www.nykaa.com/) — India's leading beauty e-commerce platform
- Built with ❤️ using Microsoft Power BI

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
