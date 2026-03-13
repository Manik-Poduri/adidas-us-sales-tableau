# 👟 Adidas US Sales Analytics — Interactive Tableau Dashboard

An end-to-end **Tableau business intelligence project** analyzing **9,600+ Adidas US sales transactions** across retailers, regions, product categories, and sales channels (2020–2021). Built to uncover revenue drivers, regional performance gaps, and product profitability trends through interactive dashboards.

---

## 📊 Dataset Overview

| Field | Description |
|---|---|
| **Retailer** | Foot Locker, Walmart, Amazon, Kohl's, Sports Direct, West Gear |
| **Invoice Date** | Daily transactions (Jan 2020 – Dec 2021) |
| **Region / State / City** | Geographic breakdown across all US regions |
| **Product** | Men's/Women's Street Footwear, Athletic Footwear, Apparel |
| **Price per Unit** | Unit selling price |
| **Units Sold** | Transaction-level quantity |
| **Total Sales** | Gross revenue per transaction |
| **Operating Profit** | Profit after operating costs |
| **Operating Margin** | Profit margin % per transaction |
| **Sales Method** | In-store, Outlet, Online |

**Records:** 9,648 transactions · **Columns:** 13 · **Period:** 2020–2021

---

## 🔍 Analysis Performed

### Sales Performance
- Total revenue and operating profit trends over time (monthly/quarterly)
- Year-over-year comparison: 2020 vs 2021 sales growth
- Best and worst performing months identified

### Regional Analysis
- Sales breakdown across Northeast, Southeast, South, West, Midwest regions
- State-level and city-level revenue mapping
- Regional operating margin comparison

### Retailer Analysis
- Revenue contribution by retailer (Foot Locker, Walmart, Amazon, etc.)
- Retailer profitability — operating profit vs total sales
- Sales channel mix per retailer (In-store vs Outlet vs Online)

### Product Analysis
- Top-performing product categories by revenue and units sold
- Men's Street Footwear vs Women's Athletic Footwear margin comparison
- Price per unit vs operating margin relationship by product

### Sales Channel Analysis
- In-store vs Outlet vs Online revenue split
- Channel profitability — operating margin by sales method
- Channel growth trends 2020 → 2021

---

## 🧰 Tools Used

```
Tableau Desktop · Excel · Tableau Prep (data cleaning)
```

**Techniques:** Interactive Filters · Calculated Fields · Dual-Axis Charts · Map Visualizations · Bar/Line Charts · KPI Cards · Dashboard Actions

---

## 📁 Repository Structure

```
├── Project_tableau.twbx          # Tableau workbook (open in Tableau Desktop/Public)
├── Adidas_US_Sales_Datasets.xlsx # Raw sales data (9,648 records)
├── Cleaned.xlsx                  # Cleaned & preprocessed dataset
├── Output.hyper                  # Tableau Hyper extract for fast querying
└── README.md
```

---

## 💡 Key Insights

- **Total US sales of $900M** with $332M operating profit across 2020–2021
- **Amazon** was the top retailer by revenue at $503M, followed by Foot Locker at $243M
- **Men's Street Footwear** had the highest operating margin at ~50%
- **Sales peaked in 2021**, showing strong recovery and growth post-2020
- Dynamic filters allow instant drill-down by product, retailer, state, and date range

---

## 🌐 Live Dashboard

👉 **[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/sri.krishna.datta.manikyalarao.poduri/viz/Projecttableau_17734428887030/PerformanceDashboard)**

No installation needed — interact with all filters directly in your browser.

---

## ▶️ How to Open Locally

1. Download **[Tableau Public](https://public.tableau.com/en-us/s/download)** (free)
2. Clone or download this repo
3. Open `Project_tableau.twbx` in Tableau Desktop or Tableau Public
4. Interact with filters — Region, Product, Retailer, Sales Method, Date Range

---

## 📈 Dashboard Highlights

### KPI Summary
| Metric | Value |
|---|---|
| **Total Sales** | $900M |
| **Operating Profit** | $332M |
| **Profit Margin** | ~37% |

### Dashboard 1 — Sales Performance (Full View)
- **KPI Cards:** Operating Profit · Total Sales · Profit Margin
- **Sales by Retailer (Donut Chart):** Amazon $503M · Foot Locker $243M · Sports Direct $182M · Kohl's $78M · Walmart $75M · Others $102M
- **Sales Trend Over Time:** Monthly revenue trend 2020–2022 with multi-product overlay
- **Sales by State (Choropleth Map):** Geographic revenue distribution across all US states
- **Interactive Filters:** Product · Invoice Date · Retailer · State

### Dashboard 2 — Filtered View
- Same layout with dynamic filters applied — isolates specific retailers, products, date ranges, and states in real time
- Demonstrates drill-down capability for executive-level reporting

---

## 👤 Author

**Sri Krishna Datta Poduri**
MS Data Science @ Worcester Polytechnic Institute
[LinkedIn](https://www.linkedin.com/in/manikyalaraopoduri) · [GitHub](https://github.com/srikrishna-poduri)
