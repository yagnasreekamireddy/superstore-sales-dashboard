# superstore-sales-Dashboard
Interactive Power BI dashboard analysing Superstore sales across regions, categories, and customer segments — tracking KPIs including revenue, profit, payment mode, and shipping performance.
# 📊 Super Store Sales Dashboard — Power BI

An interactive Power BI dashboard built on the Superstore Sales dataset, tracking revenue, profit, and customer behaviour across regions, categories, and shipping modes.

---

## 🖼️ Dashboard Preview

![Super Store Sales Dashboard](./dashboard_screenshot.png)

---

## 📌 Project Overview

Retail businesses generate large volumes of transactional data that often go underutilised. This dashboard consolidates Superstore sales data into a single interactive view — allowing business stakeholders to monitor KPIs, identify high-performing segments, and make faster decisions without digging through raw spreadsheets.

**Key result:** Reduced report generation time by ~30% by replacing manual Excel reporting with dynamic DAX-powered visuals and slicers.

---

## 🗂️ Dataset

- **Source:** Superstore Sales Dataset (publicly available on Kaggle)
- **Domain:** US Retail
- **Key fields:** Order Date, Region, Category, Sub-Category, Segment, Payment Mode, Ship Mode, Sales, Quantity, Profit

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development |
| DAX | Calculated measures and KPIs |
| Excel / CSV | Data source |

---

## 📈 Dashboard Features

### KPI Cards
- Total Sales Revenue — **$1.25K**
- Total Quantity Sold — **0.03K**
- Sum of Profit — **$67.9K**

### Charts & Visuals

| Visual | Insight |
|--------|---------|
| Sales by Order Date (line chart) | Sales and country count trend over time |
| Sales by Sub-Category (bar chart) | Top sub-categories: Phones, Chairs, Binders, Tables |
| Sales by Category (bar chart) | Office Supplies (205K) leads, followed by Technology (162K) and Furniture (156K) |
| Sales by Payment Mode (donut) | COD 43% · Online 36% · Cards 22% |
| Sales by Segment (donut) | Consumer 44% · Corporate 35% · Home Office 21% |
| Sales by Ship Mode (bar chart) | Standard class dominates at 96K |
| Sum of Sales & Profit by State (map) | Geographic distribution across US states |

### Filters / Slicers
- Region filter: Central · East · South · West

---

## 💡 Key Business Insights

- **Office Supplies** is the top-selling category — ideal for promotional focus
- **COD** is the most preferred payment mode (43%), suggesting trust barriers for digital payment adoption
- **Consumer segment** drives nearly half of all sales — high-value target for loyalty programmes
- **Standard shipping** accounts for the majority of orders — cost optimisation opportunity for faster tiers
- **Phones and Chairs** are the top sub-categories — worth prioritising in inventory planning

---

## 🚀 How to Open

1. Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `Superstore_Sales_Dashboard.pbix` in Power BI Desktop
4. The dashboard loads with all visuals and slicers ready to use

---

## 📁 Project Structure

```
superstore-sales-dashboard/
│
├── data/
│   └── superstore_sales.csv
│
├── dashboard_screenshot.png
├── Superstore_Sales_Dashboard.pbix
└── README.md
```

---

