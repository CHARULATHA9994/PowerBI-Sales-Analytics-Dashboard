# 📊 Sales Analytics Dashboard — Awesome Chocolates

> **Power BI · DAX · Data Modelling · Business Intelligence · Time Intelligence**

An interactive, end-to-end sales analytics dashboard built in Microsoft Power BI, using the Awesome Chocolates dataset. The dashboard enables dynamic exploration of sales performance, profitability, shipment analysis, and product-level KPIs across multiple countries and time periods.

---

## 🖼️ Dashboard Preview

![Sales Analytics Dashboard](Sales_Analytics_dashboard_powerbi_project_.png)

---

## 📌 Project Overview

| Detail | Description |
|---|---|
| **Project Type** | Self-directed learning project |
| **Tool** | Microsoft Power BI Desktop |
| **Dataset** | Awesome Chocolates Sales Data |
| **Scope** | Sales, Profit, Cost, Shipment, and Product KPI Analysis |
| **Time Period** | March 2023 — January 2024 |
| **Countries Covered** | Australia, Canada, India, New Zealand, UK, USA |

---

## 📂 Repository Contents

```
PowerBI-Sales-Dashboard/
│
├── Sales_Analytics_Dashboard.pbix          # Power BI project file (interactive)
├── Awesome_Chocolates_Dataset.csv          # Source dataset
├── Sales_Analytics_dashboard_powerbi_project_.png   # Dashboard screenshot
└── README.md                               # Project documentation
```

---

## 🎯 Dashboard Features

### KPI Summary Cards
| Metric | Value |
|---|---|
| Total Sales | $34M |
| Total Boxes | 2M |
| Total Costs | $13.52M |
| Total Profit | $20.52M |
| Total Shipments | 6K |
| Overall Profit Margin | 60.3% |
| Month-on-Month Change | -10.8% |

### Visual Components
- **Profit % Gauge** — Semi-circular gauge showing real-time profit margin (60.3%)
- **Dynamic Trend Chart** — Single chart switching between Sales, Boxes, Shipments, Costs, Profit, and Profit% using field parameters
- **Monthly Profit Line Chart** — Time intelligence trend from March 2023 to January 2024
- **Shipment Histogram** — Distribution analysis with zoom slider for drill-down
- **Product Performance Table** — 14 products with Sales, Profit, Profit% bars (conditional formatting), and LBS% indicator
- **Category Slicer** — Filter by Bars, Bites, Other
- **Country Slicer** — Filter by Australia, Canada, India, New Zealand, UK, USA

---

## 💡 Technical Skills Demonstrated

### Data Modelling
- Star schema design with fact and dimension tables
- Relationship management across tables in Power BI model view

### DAX Measures
- Custom measures: Total Sales, Total Profit, Total Cost, Profit%, LBS% (Low Box Shipment Percentage)
- Dedicated measure table for organised DAX management
- Month-on-Month (MoM%) time intelligence calculations using `DATEADD` and `CALCULATE`

### Power BI Features Applied
- Field parameters for dynamic metric switching on a single chart visual
- Group feature to create histogram bins from raw shipment data
- Zoom slider for histogram drill-down
- New Card visual with reference labels and trend indicators
- Conditional formatting — in-cell profit% bar chart within table visual
- Bookmarks for interactive navigation between dashboard views
- Icon-based performance flags (✓ = above threshold, ⊗ = below threshold)

---

## 📈 Key Business Insights

| Insight | Detail |
|---|---|
| 🏆 Highest profit margin | Peanut Butter Cubes — **87.1%** ($2.03M sales) |
| 📈 Peak month | November 2023 — ~$2.95M profit |
| ⚠️ Declining trend | MoM% = **-10.8%** — requires attention |
| ⊗ Underperforming products | Mint Chip Choco (51.9%), Eclairs (44.3%), Drinking Coco (26.7%) |
| ✓ Consistent top performers | Smooth Silky Salty (84.4%), Orange Choco (79.5%), Manuka Honey Choco (78.9%) |

---

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development, data modelling, visualisation |
| DAX (Data Analysis Expressions) | Measure creation, time intelligence, KPI calculations |
| Power Query (M language) | Data transformation and loading |

---

## 📚 Learning Background

This project was built by independently following a structured Power BI tutorial, implementing each feature hands-on. The workshop **"Foundational Principles of Business Intelligence and their Practical Application using Microsoft Power BI"** was completed at Sathyabama Institute of Science and Technology (September 2025), providing the foundational Power BI knowledge that supported this project.

**Topics covered during the build:**
- Dashboard design and professional layout
- Data modelling with star schema
- KPI identification and DAX measure setup
- Time intelligence calculations (MoM%)
- New card visuals with reference labels
- Field parameters for dynamic trend charts
- Histogram creation using the Group feature
- Zoom slider and bar chart formatting
- Table design with conditional formatting
- Bookmark implementation for navigation

---

## 🔗 Related Projects

- 🔬 [Respiratory Disease Biomarker Discovery](https://github.com/CHARULATHA0994/Respiratory-Disease-Biomarker-Discovery) — MSc Research Project: Pan-transcriptomic and multi-omics analysis using R and Python

---

## 👤 Author

**M. Charulatha**
MSc Bioinformatics and Data Science
Sathyabama Institute of Science and Technology, Chennai

