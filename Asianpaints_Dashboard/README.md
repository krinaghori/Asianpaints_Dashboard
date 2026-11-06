<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=FF6B00&center=true&vCenter=true&width=720&lines=Filter+%7C+Explore+%7C+Visualize+%7C+Decide;%E2%82%B9702+Cr+Revenue+%C2%B7+5+Dashboards+%C2%B7+1+Business+Story;Built+in+Power+BI+%F0%9F%93%8A" alt="Typing SVG" />

<br/>

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-1E5BFF?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Sales_%26_Dealer_Analytics-FF6B00?style=for-the-badge)
![Revenue](https://img.shields.io/badge/Revenue-%E2%82%B9702_Cr-22C55E?style=for-the-badge)
![Dealers](https://img.shields.io/badge/Dealers-5%2C000-0EA5E9?style=for-the-badge)
![Pages](https://img.shields.io/badge/Report_Pages-5-A855F7?style=for-the-badge)
![Visuals](https://img.shields.io/badge/Data_Visuals-62-EC4899?style=for-the-badge)
![Slicers](https://img.shields.io/badge/Slicers-6--8_per_page-E31837?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-10B981?style=for-the-badge)

<br/>

[![Watch the Presentation](https://img.shields.io/badge/%E2%96%B6_Watch_the_Presentation-EF4444?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1gJYjNji0b6CmmOdOIfxABj4vIr2mv4pW/view?usp=drive_link)
[![Dashboard Preview](https://img.shields.io/badge/%F0%9F%96%BC_Dashboard_Preview-1E5BFF?style=for-the-badge)](#-dashboard-preview)
[![Key Insights](https://img.shields.io/badge/%F0%9F%8F%86_Key_Insights-F59E0B?style=for-the-badge)](#-results--insights)
[![How to Open](https://img.shields.io/badge/%E2%96%B6_How_to_Open-10B981?style=for-the-badge)](#-how-to-open--use)

<br/>

> 🚀 A **5-page Power BI report** for **Asian Paints** that turns **revenue, profit, product, regional and dealer data (3,00,000 orders, 500 products, 5,000 dealers)** into an interactive executive dashboard — 27 KPI cards, 22 charts, 3 maps and 10 drill-down tables, with date, region, product and dealer filters — **data as on 31 Mar 2024**.

</div>

---

## 📑 Table of Contents

1. [Overview](#-overview)
2. [Problem Statement](#-problem-statement)
3. [Features](#-features)
4. [Key Features](#-key-features)
5. [Project Structure](#-project-structure)
6. [Dashboard Layout](#-dashboard-layout)
7. [Data Preparation & Modelling](#-data-preparation--modelling)
8. [Data Model & Fields](#-data-model--fields)
9. [Panel 1 — KPI Cards](#-panel-1--kpi-cards)
10. [Panel 2 — Filters](#-panel-2--filters)
11. [Panel 3 — Executive Overview](#-panel-3--executive-overview)
12. [Panel 4 — Regional Performance](#-panel-4--regional-performance)
13. [Panel 5 — Product Analytics](#-panel-5--product-analytics)
14. [Panel 6 — Dealer Performance](#-panel-6--dealer-performance)
15. [Panel 7 — Trends & Forecasting](#-panel-7--trends--forecasting)
16. [Tech Stack](#-tech-stack)
17. [Results & Insights](#-results--insights)
18. [Advantages](#-advantages)
19. [How to Open & Use](#-how-to-open--use)
20. [Project Presentation](#-project-presentation)
21. [Dashboard Preview](#-dashboard-preview)
22. [License](#-license)
23. [Author](#-author)
24. [Acknowledgements](#-acknowledgements)

---

## 🔭 Overview

**Asian Paints Executive Dashboard** is a 5-page `.pbix` report that gives business leaders one place to see **how much revenue and profit the company makes, which regions, products and dealers drive it, and where the numbers are heading** — **data as on 31 Mar 2024, all values in ₹ Crores**. A dark-navy sidebar holds the page navigation (*Overview*, *Regional Performance*, *Product Analytics*, *Dealer Performance*, *Trends & Forecasting*) and its own filter panel, **Date Range** and other dropdowns sit at the top, and a **Reset** button clears every filter.

Every visual is **live and connected** to one data model — choose a Region, Category or Dealer Type and the cards, charts and tables update together. All figures come from **DAX measures** kept in a single `Measure Table`.

<div align="center">

| 💰 **₹702 Cr** | 📈 **₹228 Cr** | 🎨 **32.50%** | 🛒 **3,00,000** | 🤝 **5,000** |
|:---:|:---:|:---:|:---:|:---:|
| Total Revenue | Total Profit | Profit Margin | Total Orders | Total Dealers |

</div>

---

## ❗ Problem Statement

Sales, product, region and dealer data usually sit in different files, so management struggles to answer questions such as:

- 💰 How much revenue and profit did we make, and how does it compare with last year and the target?
- 🗺️ Which regions, zones and states bring in the most revenue — and where is the margin highest?
- 🎨 Which product categories and individual products lead on revenue, profit and inventory turnover?
- 🤝 Who are the top dealers, how satisfied are dealers, and which dealer types perform best?
- 📈 Is revenue growing month by month, and what does the outlook look like?

**Asian Paints Executive Dashboard** answers all of these across **five interactive pages**.

---

## ✨ Features

| Feature | Visual | Description |
|---|---|---|
| 💰 **Total Revenue** | Card | Revenue in ₹ Cr with previous year and % change |
| 📈 **Total Profit** | Card | Profit in ₹ Cr with previous year and % change |
| 🎨 **Profit Margin %** | Card | Profit as a share of revenue |
| 🛒 **Total Orders** | Card | Order count with previous year |
| 🎯 **Target Achievement %** | Card | Revenue as a % of target |
| 🧱 **Total Products / Avg Inventory Turnover** | Cards | Product count and stock-turnover ratio |
| 🤝 **Total Dealers / Avg Revenue per Dealer / Satisfaction** | Cards | Dealer network KPIs |
| 📅 **YTD Revenue / YTD Profit / YoY Growth** | Cards | Year-to-date figures and growth rates |
| 🎛️ **Filters** | Slicers + Reset button | Date Range, Region, Zone, State, City, Category, Sub Category, Product, Dealer Type |
| 📉 **Revenue Trend** | Line Chart | Monthly revenue |
| 📊 **Revenue vs Target** | Column + Line Chart | Monthly revenue against target with achievement % |
| 🌳 **Revenue by Category** | Treemap | Seven paint categories |
| 🗺️ **Revenue by Region / State** | Filled Map | Revenue by state across India |
| 🏅 **Rankings** | Tables with bars | Region, state, product and dealer ranking with % contribution |
| 🔥 **Profit Margin Heatmap** | Matrix | Margin % by state and region with colour scale |
| 💎 **Top 10 Products** | Bar Charts | Revenue and profit leaders |
| 🍩 **Category Contribution** | Donut Chart | Share of revenue by category |
| 🔵 **Revenue vs Profit** | Scatter Chart | Product-level relationship |
| 👥 **Dealer Distribution & Satisfaction** | Column, Donut, Table | Revenue brackets and ratings |
| 🔮 **Revenue Forecast** | Line Chart | Month-wise outlook |
| 🚦 **Executive Scorecard** | Matrix with icons | Target achievement, profit achievement and YoY growth by month |

---

## 🌟 Key Features

| Feature | Description |
|---|---|
| 🔗 **One Connected Model** | Dimension and fact tables are linked, so filters apply consistently across all five pages |
| 🧮 **DAX Measures** | Revenue, profit, margin, target achievement, YoY growth and more live in one `Measure Table` |
| 🧭 **Drill-down Hierarchies** | Region → Zone → State → City and Category → Sub Category → Product |
| 🆚 **Previous-Year Comparison** | Almost every KPI card shows `Previous Year` with an up arrow and % change |
| 🎚️ **Hierarchy Level Slicer** | Switch the Regional and Product pages between hierarchy levels |
| 🗺️ **Map Views** | Filled maps of revenue by state and a dealer location map |
| 🚦 **Status Icons** | Scorecards use ▲ ▼ ● icons to flag months above or below target |
| 🔮 **Forecast & YoY Trend** | Current-year vs previous-year lines and a revenue forecast on the last page |
| 🎨 **Branded Design** | Asian Paints logo, navy sidebar, icon cards, paint-bucket artwork and insight call-outs |
| ♻️ **Native Visuals Only** | Card, Column, Bar, Line, Area, Donut, Treemap, Scatter, Map, Matrix and Table |

---

## 📁 Project Structure

```
📦 Asian-Paints-Dashboard/
 ┣ 📄 README.md                                ← Project documentation (you're here!)
 ┣ 📊 Asianpaints_Dashboard.pbix               ← Power BI report (5 pages)
 ┣ 🖼️ Page_1_-_Overview.png                    ← Page 1 screenshot
 ┣ 🖼️ Page_2_-_Regional_performance.png        ← Page 2 screenshot
 ┣ 🖼️ Page_3_-_Product_Analytics.png           ← Page 3 screenshot
 ┣ 🖼️ Page_4_-_Dealer_Performance.png          ← Page 4 screenshot
 ┣ 🖼️ Page_5_-_Trends___Forecasting.png        ← Page 5 screenshot
 ┗ 📁 assets/
    ┗ 🎞️ video_thumbnail.png                   ← Clickable presentation thumbnail
```

> 🎬 The **project presentation** is hosted on **Google Drive** — [watch it here](https://drive.google.com/file/d/1gJYjNji0b6CmmOdOIfxABj4vIr2mv4pW/view?usp=drive_link).

---

## 🖥️ Dashboard Layout

Every page shares one frame: **sidebar navigation and filters on the left, a title bar with dropdowns and a Reset button on top, KPI cards, then charts and tables.**

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  asianpaints     │ Executive overview                 Date Range │ Region │ Reset │
│                  │┌──────────┬──────────┬──────────┬──────────┬──────────────┐│
│ > Overview       ││ Total    │ Total    │ Profit   │ Total    │ Target       ││
│   Regional       ││ Revenue  │ Profit   │ Margin % │ Orders   │ Achievement  ││
│   Product        │└──────────┴──────────┴──────────┴──────────┴──────────────┘│
│   Dealer         │┌──────────────────────┬────────────────────────────────────┐│
│   Trends         ││ Revenue Trend        │ Revenue vs Target (Monthly)        ││
│                  ││ (line)               │ (column + achievement line)        ││
│ Filters          │└──────────────────────┴────────────────────────────────────┘│
│ Product Category │┌────────────────┬──────────────────┬───────────────────────┐│
│ Dealer Type      ││ Revenue by     │ Revenue by       │ Executive Scorecard   ││
│ State            ││ Category       │ Region           │ (vs Target)           ││
│ Zone             ││ (treemap)      │ (filled map)     │ (matrix, icons)       ││
│                  │└────────────────┴──────────────────┴───────────────────────┘│
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 1 — Executive Overview
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  asianpaints     │ Regional performance      Date Range │ Hierarchy Level │ Reset │
│                  │┌──────────┬──────────┬──────────┬──────────┬──────────────┐│
│   Overview       ││ Revenue  │ Profit   │ Target   │ Orders   │ Profit Margin││
│ > Regional       │└──────────┴──────────┴──────────┴──────────┴──────────────┘│
│   Product        │┌────────────────┬─────────────────┬────────────────────────┐│
│   Dealer         ││ Revenue by     │ Revenue by      │ Revenue by State       ││
│   Trends         ││ Region (map)   │ Region (rank)   │ (Top 10 rank)          ││
│ Filters          │├────────────────┴─────────────────┼────────────────────────┤│
│ Region · Zone    ││ Revenue vs Target by Region       │ Profit Margin %        ││
│ State · City     ││ (column + line + table)           │ Heatmap (State × Region)││
│                  │└───────────────────────────────────┴────────────────────────┘│
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 2 — Regional Performance
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  asianpaints     │ Product Analytics         Date Range │ Hierarchy Level │ Reset │
│                  │┌──────────┬──────────┬──────────┬──────────┬──────────────┐│
│   Overview       ││ Revenue  │ Profit   │ Margin % │ Total    │ Avg Inventory││
│   Regional       ││          │          │          │ Products │ Turnover     ││
│ > Product        │└──────────┴──────────┴──────────┴──────────┴──────────────┘│
│   Dealer         │┌────────────────┬────────────────┬────────────────────────┐│
│   Trends         ││ Product Revenue│ Product Profit │ Category Contribution  ││
│ Filters          ││ (Top 10 bar)   │ (Top 10 bar)   │ (donut + table)        ││
│ Category · Sub   │├────────────────┼────────────────┴──┬─────────────────────┤│
│ Category · Prod. ││ Inventory      │ Top Products by   │ Revenue vs Profit   ││
│ Product ID       ││ Turnover (col) │ Revenue (table)   │ (scatter)           ││
│                  │└────────────────┴───────────────────┴─────────────────────┘│
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 3 — Product Analytics
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  asianpaints     │ Dealer Performance     Date Range │ Region │ Dealer Type │ Reset │
│                  │┌────────┬────────┬────────┬────────┬─────────┬────────────┐│
│   Overview       ││Revenue │ Profit │ Total  │ Total  │ Avg Rev │ Avg Dealer ││
│   Regional       ││        │        │ Dealers│ Orders │ /Dealer │ Satisfaction││
│   Product        │└────────┴────────┴────────┴────────┴─────────┴────────────┘│
│ > Dealer         │┌────────────────┬──────────────────┬──────────────────────┐│
│   Trends         ││ Top 10 Dealers │ Revenue per      │ Visits & Orders      ││
│ Filters          ││ (ranked table) │ Dealer (column)  │ Booked (line)        ││
│ Dealer Type      │├────────────────┼──────────────────┼───────────┬──────────┤│
│ Region · Zone    ││ Satisfaction   │ Revenue by Dealer│ Dealer    │ Top 5    ││
│ State · City     ││ Rating (donut) │ Type (col + line)│ Location  │ Cities   ││
│                  │└────────────────┴──────────────────┴───────────┴──────────┘│
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 4 — Dealer Performance
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  asianpaints     │ Trends & Executive Summary  Date Range │ Compare With │ Reset │
│                  │┌────────┬────────┬────────┬─────────┬─────────┬───────────┐│
│   Overview       ││ YTD    │ YTD    │ Profit │ YoY Rev │ YoY     │ Total     ││
│   Regional       ││ Revenue│ Profit │ Margin │ Growth  │ Profit  │ Orders    ││
│   Product        │└────────┴────────┴────────┴─────────┴─────────┴───────────┘│
│   Dealer         │┌──────────────────┬──────────────────┬────────────────────┐│
│ > Trends         ││ Revenue Trend    │ Profit Trend     │ Executive Scorecard││
│ Filters          │├──────────────────┼──────────────────┼────────────────────┤│
│ Region · Zone    ││ YTD Revenue      │ Revenue Forecast │ YoY Growth Trend   ││
│ Category · Dealer││ (cumulative area)│ (line)           │ (line)             ││
│ Type             │└──────────────────┴──────────────────┴────────────────────┘│
│                  │ Executive Summary — four call-out cards                     │
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 5 — Trends & Executive Summary
```

---

## 🧪 Data Preparation & Modelling

The report is built on a **star-style model** of dimension and fact tables, with every calculation stored as a DAX measure.

| # | Step | What it does |
|:---:|---|---|
| 1️⃣ | **Load source tables** | Sales, product, region, dealer and date data are loaded into Power BI |
| 2️⃣ | **Build dimensions** | `DimDate`, `DimRegion`, `DimProduct` and `DimDealer` |
| 3️⃣ | **Build the fact table** | `FactSales` holds orders booked, visits and sales records |
| 4️⃣ | **Create relationships** | Dimensions are linked to the fact table so slicers filter every page |
| 5️⃣ | **Add hierarchies** | Region → Zone → State → City and Category → Sub Category → Product |
| 6️⃣ | **Create `Measure Table`** | One table that holds all DAX measures (revenue, profit, target, growth, dealers) |
| 7️⃣ | **Add prior-year logic** | PY measures power the `Previous Year` labels and YoY growth |
| 8️⃣ | **Design the pages** | Navy sidebar, filter panel, icon cards, Reset button and insight call-outs |

---

## 📋 Data Model & Fields

**📌 Dashboard at a glance**

| Metric | Value |
|---|---|
| 📄 Report pages | **5** |
| 📊 Data visuals | **62** (27 cards, 22 charts, 3 maps, 10 tables/matrices) |
| 💰 Revenue / Profit | **₹702 Cr** / **₹228 Cr** |
| 🛒 Orders | **3,00,000** |
| 🧱 Products | **500** across 7 categories |
| 🤝 Dealers | **5,000** (Distributor · Retail · Silver · Premium · Gold) |
| 🗺️ Regions | West · Central · East · North · South |
| 📆 Data as on | **31 Mar 2024** (all values in ₹ Crores) |

**📌 Tables in the model**

| Table | Role |
|---|---|
| 📅 `DimDate` | `Date`, `MonthName`, `MonthYear`, `Year` |
| 🗺️ `DimRegion` | `Region`, `Zone`, `State`, `City` |
| 🎨 `DimProduct` | `Category`, `SubCategory`, `ProductID`, `ProductName` |
| 🤝 `DimDealer` | `DealerName`, `DealerType`, `SatisfactionRating`, `Dealer Revenue Bracket`, `% Dealers` |
| 🧾 `FactSales` | Sales records, `Orders Booked`, `Visits` |
| 🧮 `Measure Table` | All DAX measures |

**📌 Measures used on the dashboard**

| Page | Measures |
|---|---|
| 🟦 Overview | `Total Revenue` · `Total Profit` · `Profit Margin %` · `Total Orders` · `Target Achievement %` · `Revenue Target` · `Profit Achievement %` · `YoY Revenue Growth %` |
| 🟧 Regional | `Region Rank` · `Region % Contribution` · `State Rank` · `State % Contribution` |
| 🟪 Product | `Total Products` · `Avg Inventory Turnover` · `Product Rank` · `Category % Contribution` |
| 🟩 Dealer | `Total Dealers` · `Avg Revenue per Dealer` · `Avg Dealer Satisfaction Display` · `Total Dealer Revenue (₹ Cr)` · `Dealer Rank` |
| 🟥 Trends | `YTD Revenue` · `YTD Profit` · `YoY Profit Growth %` · `Monthly Revenue (₹ Cr)` · `Monthly Revenue PY (₹ Cr)` · `Monthly Profit (₹ Cr)` · `Monthly Profit PY (₹ Cr)` · `Monthly Revenue Growth %` · `Monthly Profit Growth %` · `YTD Revenue Cumulative` · `YTD Revenue Cumulative PY` |

---

## 💰 Panel 1 — KPI Cards

> **Twenty-seven native Card visuals** — five or six on each page, with previous-year comparisons and % changes.

| Page | Card | Shown on dashboard | Previous year | Change |
|---|---|---|---|---|
| 🟦 Overview | 💰 Total Revenue | **₹702 Cr** | ₹689 Cr | 🟢 +18.6% |
| 🟦 Overview | 📈 Total Profit | **₹228 Cr** | ₹199 Cr | 🟢 +20.3% |
| 🟦 Overview | 🎨 Profit Margin % | **32.50%** | 31.7% | 🟢 +1.2% |
| 🟦 Overview | 🛒 Total Orders | **3,00,000** | 2,80,000 | 🟢 +15.7% |
| 🟦 Overview | 🎯 Target Achievement | **9.29%** | 8.90% | 🟢 +8.6% |
| 🟪 Product | 🧱 Total Products | **500** | 500 | — |
| 🟪 Product | 🔄 Avg Inventory Turnover | **20.74** | 19.78 | 🟢 +0.68% |
| 🟩 Dealer | 🤝 Total Dealers | **5,000** | 4,620 | 🟢 +8.2% |
| 🟩 Dealer | 💵 Avg Revenue per Dealer | **₹14.03** | 12.78 | 🟢 +9.6% |
| 🟩 Dealer | ⭐ Avg Dealer Satisfaction | **4.32 / 5** | 4.04 | 🟢 +0.28% |
| 🟩 Dealer | 🛒 Total Orders | **3,00,000** | 2,81,715 | 🟢 +15.7% |
| 🟥 Trends | 📅 YTD Revenue | **₹131.64 Cr** | ₹123.52 Cr | 🟢 +18.6% |
| 🟥 Trends | 📅 YTD Profit | **₹43 Cr** | ₹40 Cr | 🟢 +20.3% |
| 🟥 Trends | 📈 YoY Revenue Growth % | **33.53%** | 30.23% | 🟢 +2.3% |
| 🟥 Trends | 📈 YoY Profit Growth % | **33.51%** | 30.11% | 🟢 +3.2% |
| 🟥 Trends | 🛒 Total Orders | **3,00,000** | 2,88,000 | 🟢 +15.7% |

> The Regional and Product pages repeat the Revenue, Profit, Margin and Orders cards from the Overview page, and the Dealer page repeats Revenue and Profit.

> [!TIP]
> ✅ **Reading it:** revenue is up **18.6%** and profit is up **20.3%**, so profit is growing faster than sales — which is why the margin improved from **31.7% to 32.50%**.

---

## 🎛️ Panel 2 — Filters

> **Sidebar filters** and **top dropdowns** on every page, plus a **Reset** button.

| Page | Top dropdowns | Sidebar filters |
|---|---|---|
| 🟦 Overview | Date Range · Region | Product Category · Dealer Type · State · Zone |
| 🟧 Regional | Date Range · Hierarchy Level Slicer | Region · Zone · State · City |
| 🟪 Product | Date Range · Hierarchy Level Slicer | Category · Sub Category · Product · Product ID |
| 🟩 Dealer | Date Range · Region · Dealer Type | Dealer Type · Region · Zone · State · City |
| 🟥 Trends | Date Range · Compare With Dropdown | Region · Zone · Category · Dealer Type |

| Slicer Field | Table |
|---|---|
| 📅 `Date` · `Year` | `DimDate` |
| 🗺️ `Region` · `Zone` · `State` · `City` | `DimRegion` |
| 🎨 `Category` · `SubCategory` · `ProductName` · `ProductID` | `DimProduct` |
| 🤝 `DealerType` | `DimDealer` |
| 🔄 **Reset** | Button that clears every filter |

---

## 🟦 Panel 3 — Executive Overview

> **Page 1** — Line Charts, a Column Chart, a Treemap, a Filled Map and an Executive Scorecard.

| Visual | Type | Field Roles |
|---|---|---|
| 📉 Revenue Trend (Monthly) | Line Chart | Axis `MonthName` · Values `Total Revenue` |
| 📊 Revenue vs Target (Monthly) | Column + Line | Axis `MonthName` · Values `Total Revenue`, `Revenue Target`, `Target Achievement %` |
| 🌳 Revenue by Category | Treemap | Group `Category` · Values `Total Revenue` |
| 🗺️ Revenue by Region | Filled Map | Location `State` · Values `Total Revenue` |
| 🚦 Executive Scorecard (vs Target) | Matrix with icons | `Target Achievement %`, `Profit Achievement %`, `YoY Revenue Growth %`, `Profit Margin %` by `MonthName` |

**🌳 Revenue by category**

| Category | Revenue | Visual |
|---|---|---|
| 🥇 Putty | ₹115 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥈 Interior Emulsion | ₹114 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥉 Industrial Coating | ₹102 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥉 Wood Finish | ₹102 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 5️⃣ Primer | ₹99 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 6️⃣ Exterior Emulsion | ₹89 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦 |
| 7️⃣ Waterproofing | ₹80 Cr | 🟦🟦🟦🟦🟦🟦🟦 |

**🚦 Executive Scorecard (sample months)**

| Month | Target Achievement % | Profit Achievement % | YoY Revenue Growth % |
|---|---|---|---|
| April | 🟢 9.64% | 0.16 | 33.77% |
| October | 🟢 9.63% | 0.15 | 34.24% |
| December | 🟡 9.40% | 0.16 | 33.47% |
| February | 🟡 9.40% | 0.16 | 33.79% |
| July | 🔻 8.94% | 0.15 | 33.84% |
| November | 🔻 9.06% | 0.14 | 32.57% |

> [!NOTE]
> **How to read it:** the monthly achievement line sits between about **8.9% and 9.6%**, so every month lands close to the others. The footer reads *All Values in Crores | PY — Previous Year*.

> [!TIP]
> ✅ **Reading it:** **Putty** (₹115 Cr) and **Interior Emulsion** (₹114 Cr) lead the category mix, while **Waterproofing** is the smallest at ₹80 Cr.

---

## 🟧 Panel 4 — Regional Performance

> **Page 2** — a Filled Map, ranking tables, a Column + Line chart and a Profit Margin Heatmap, drilling **Region → Zone → State → City**.

| Visual | Type | Field Roles |
|---|---|---|
| 🗺️ Revenue by Region (Filled Map) | Filled Map | Location `State` · Values `Total Revenue` |
| 🥇 Revenue by Region (Ranking) | Table with bars | `Region Rank`, `Region`, `Total Revenue`, `Region % Contribution` |
| 🏙️ Revenue by State (Top 10) | Table with bars | `State Rank`, `State`, `Total Revenue`, `State % Contribution` |
| 📊 Revenue vs Target by Region | Column + Line + Table | `Region` · `Total Revenue`, `Revenue Target`, `Target Achievement %` |
| 🔥 Profit Margin % Heatmap | Matrix with colour scale | Rows `State` · Columns `Region` · Values `Profit Margin %` |

**🥇 Revenue by region**

| Rank | Region | Share of Revenue | Visual |
|:---:|---|---|---|
| 🥇 1 | West | 25% | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥈 2 | Central | 19% | 🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥉 3 | East | 19% | 🟦🟦🟦🟦🟦🟦🟦🟦 |
| 4️⃣ 4 | North | 19% | 🟦🟦🟦🟦🟦🟦🟦🟦 |
| 5️⃣ 5 | South | 18% | 🟦🟦🟦🟦🟦🟦🟦 |
| 🏁 | **Total** | **₹702 Cr (100%)** | |

**🏙️ Top states by revenue share** — 1️⃣ Mizoram **14%** · 2️⃣ Himachal Pradesh **13%** · 3️⃣ Rajasthan **11%** · 4️⃣ West Bengal **10%** · 5️⃣ Uttar Pradesh **10%** (the Top 10 table totals ₹402 Cr).

**📊 Revenue vs Target by region (table)**

| Region | Total Revenue | Revenue Target | Target Achievement % |
|---|---|---|---|
| Central | ₹136 Cr | ₹1,501.8856 | 9.05% |
| South | ₹126 Cr | ₹1,371.4727 | 9.19% |
| West | ₹172 Cr | ₹1,842.0622 | 9.34% |
| 🏁 **Total** | **₹702 Cr** | **₹7,549.6721** | **9.29%** |

**🔥 Profit margin heatmap (sample states)**

| State | Central | East | North | South | West |
|---|---|---|---|---|---|
| Andhra Pradesh | 32.56% | — | 32.51% | 32.50% | 32.57% |
| Assam | 32.39% | 32.44% | 32.46% | — | 32.33% |
| Bihar | 32.64% | 32.83% | 32.34% | — | 32.17% |
| 🏁 **Total** | **32.52%** | **32.51%** | **32.51%** | **32.45%** | **32.50%** |

> [!TIP]
> ✅ **Reading it:** **West** brings in the most revenue (25%), and margins are tightly bunched at **32.4%–32.5%** across all five regions — the heatmap colours highlight small differences, not big gaps.

---

## 🟪 Panel 5 — Product Analytics

> **Page 3** — Bar Charts, a Donut, a Column Chart, a Table and a Scatter Chart, drilling **Category → Sub Category → Product**.

| Visual | Type | Field Roles |
|---|---|---|
| 📊 Product Revenue (Top 10) | Clustered Bar | Axis `ProductName` · Values `Total Revenue` |
| 💚 Product Profit (Top 10) | Clustered Bar | Axis `ProductName` · Values `Total Profit` |
| 🍩 Category Contribution (Revenue) | Donut (centre: **₹16 Cr**) + Table | `Category` · `Total Revenue`, `Category % Contribution` |
| 🔄 Inventory Turnover by Category | Clustered Column | Axis `Category` · Values `Avg Inventory Turnover` |
| 🏆 Top Products by Revenue | Table | `Product Rank`, `ProductName`, `Category`, `Total Revenue`, `Profit Margin %` |
| 🔵 Revenue vs Profit Scatter Analysis | Scatter (colour: category) | `Total Revenue`, `Total Profit`, `Avg Inventory Turnover` |

**📊 Top 5 products by revenue**

| Rank | Product | Revenue | Profit | Visual |
|:---:|---|---|---|---|
| 🥇 | Asian Paint Product 399 | ₹1.67 Cr | ₹0.54 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥈 | Asian Paint Product 200 | ₹1.60 Cr | ₹0.53 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥉 | Asian Paint Product 222 | ₹1.58 Cr | ₹0.51 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 4️⃣ | Asian Paint Product 90 | ₹1.57 Cr | ₹0.51 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 5️⃣ | Asian Paint Product 162 | ₹1.57 Cr | ₹0.51 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦 |

**🏆 Top Products table (with category and margin)**

| Product | Category | Revenue | Profit Margin % |
|---|---|---|---|
| Product 399 | Industrial Coating | ₹1.67 Cr | 32.48% |
| Product 200 | Waterproofing | ₹1.60 Cr | 33.04% |
| Product 222 | Primer | ₹1.58 Cr | 32.35% |
| Product 90 | Industrial Coating | ₹1.57 Cr | 32.16% |
| Product 162 | Waterproofing | ₹1.57 Cr | 32.72% |
| Product 225 | Putty | ₹1.57 Cr | 33.06% |
| 🏁 **Total (table)** | | **₹15.74 Cr** | **32.52%** |

**🔄 Inventory turnover by category**

| Category | Avg Inventory Turnover | Visual |
|---|---|---|
| 🥇 Primer | 25.34 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥈 Putty | 23.04 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥉 Industrial Coating | 22.51 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 4️⃣ Waterproofing | 21.77 | 🟪🟪🟪🟪🟪🟪🟪🟪 |
| 5️⃣ Exterior Emulsion | 20.02 | 🟪🟪🟪🟪🟪🟪🟪🟪 |

**🍩 Category contribution** — Putty **0.16** · Interior Emulsion **0.16** · Industrial Coating **0.15** · Wood Finish **0.15** · Primer **0.14** · Exterior Emulsion **0.13** · Waterproofing **0.11**

> [!NOTE]
> **How to read it:** the dashboard call-out says products in the **top-right quadrant** of the scatter are high performers — focus on expanding high-margin products and improving low-margin, high-revenue ones.

> [!TIP]
> ✅ **Reading it:** the scatter forms a near-straight rising line, so **higher revenue goes hand in hand with higher profit**. **Primer** turns its inventory fastest (**25.34**).

---

## 🟩 Panel 6 — Dealer Performance

> **Page 4** — a ranked table, Column Charts, a Line Chart, a Donut, a Map and a Bar Chart.

| Visual | Type | Field Roles |
|---|---|---|
| 🏅 Top 10 Dealers By Revenue | Table with bars | `Dealer Rank`, `DealerName`, `Total Dealer Revenue (₹ Cr)` |
| 📊 Revenue Per Dealer (Distribution) | Clustered Column | Axis `Dealer Revenue Bracket` · Values `Total Dealers` |
| 📈 Visits & Orders Booked by MonthYear | Line Chart | Axis `MonthYear` · Values `Visits`, `Orders Booked` |
| 🍩 Dealer Satisfaction Rating | Donut (centre: **5000**) + Table | `SatisfactionRating` · `Total Dealers` |
| 💎 Revenue by Dealer Type | Column + Line | `DealerType` · `Total Profit`, `Total Dealers`, `Profit Margin %` |
| 🗺️ Dealer Location Map | Map | Location `State` · `Total Dealer Revenue (₹ Cr)` |
| 🏙️ Top 5 Cities by Dealer Revenue | Bar Chart | `City` · `Total Profit` |

**🏅 Top dealers by revenue (₹ Cr)**

| Rank | Dealer | Revenue | Visual |
|:---:|---|---|---|
| 🥇 1 | Dewan Inc | — | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥈 2 | Kala and Sons | ₹0.5958 | 🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥉 3 | Baral Ltd | ₹0.5453 | 🟦🟦🟦🟦🟦🟦🟦🟦 |
| 4️⃣ 4 | Dora Group | ₹0.5075 | 🟦🟦🟦🟦🟦🟦🟦🟦 |
| 5️⃣ 5 | Kala LLC | ₹0.5045 | 🟦🟦🟦🟦🟦🟦🟦🟦 |
| 6️⃣ 6 | Vaidya Inc | ₹0.4922 | 🟦🟦🟦🟦🟦🟦🟦 |
| 7️⃣ 7 | Rajan Inc | ₹0.4892 | 🟦🟦🟦🟦🟦🟦🟦 |
| 8️⃣ 8 | Sahota Inc | ₹0.4881 | 🟦🟦🟦🟦🟦🟦🟦 |

**📊 Dealers by revenue bracket** — **< 10:** 99 dealers · **10–20:** **4,881** dealers · **20–30:** 20 dealers

**💎 Dealer types**

| Dealer Type | Dealers | Profit | Margin % |
|---|---|---|---|
| 🥇 Distributor | 1,020 | ₹47 Cr | 32.53% |
| 🥈 Retail | 1,019 | ₹46 Cr | 32.52% |
| 🥉 Silver | 1,002 | ₹46 Cr | 32.49% |
| 4️⃣ Premium | 992 | ₹45 Cr | 32.49% |
| 5️⃣ Gold | 967 | ₹44 Cr | 32.47% |

**⭐ Satisfaction rating by dealer type**

| Dealer Type | Sum of Rating | % of Dealers |
|---|---|---|
| Distributor | 3,672.00 | 0.20 |
| Gold | 4,351.50 | 0.19 |
| Premium | 4,761.60 | 0.20 |
| Retail | 3,872.20 | 0.20 |
| Silver | 4,108.20 | 0.20 |
| 🏁 **Total** | **20,765.50** | **1.00** |

> [!TIP]
> ✅ **Reading it:** almost every dealer (**4,881 of 5,000**) sits in the **₹10–20** revenue bracket, and dealers are spread evenly across the five types. The map call-out says **Mumbai** leads dealer revenue, followed by **Delhi** and **Bengaluru**.

---

## 🟥 Panel 7 — Trends & Forecasting

> **Page 5** — Line Charts, an Area Chart, a Forecast and an Executive Summary strip.

| Visual | Type | Field Roles |
|---|---|---|
| 📉 Revenue Trend (Monthly) | Line Chart (vs PY) | Axis `MonthName` · `Monthly Revenue (₹ Cr)`, `Monthly Revenue PY (₹ Cr)` |
| 💚 Profit Trend (Monthly) | Line Chart (vs PY) | Axis `MonthName` · `Monthly Profit (₹ Cr)`, `Monthly Profit PY (₹ Cr)` |
| 🌊 YTD Revenue (Cumulative) | Area Chart | `YTD Revenue Cumulative`, `YTD Revenue Cumulative PY` |
| 🔮 Revenue Forecast | Line Chart | `Monthly Revenue (₹ Cr)` by month |
| 📈 YoY Growth Trend (%) | Line Chart | `Monthly Revenue Growth %`, `Monthly Profit Growth %` |
| 🚦 Executive Scorecard vs Target Achievement | Matrix | `Target Achievement %`, `Profit Achievement %`, `YoY Revenue Growth %` |

**📉 Monthly revenue and profit — current year vs previous year (₹ Cr)**

| | Highest month | Lowest month |
|---|---|---|
| 💰 **Revenue** | 60.46 (August) · PY 45.35 | 54.66 (February) · PY 40.85 |
| 📈 **Profit** | 19.63 (August) · PY 14.72 | 17.77 (February) · PY 13.27 |

**📣 Executive Summary strip on the dashboard**

| Call-out | Message |
|---|---|
| 💪 **Strong Revenue Growth** | YTD revenue of ₹131.64 Cr, up **18.6%** on the previous year |
| 💰 **Healthy Profitability** | YTD profit of ₹43 Cr with a margin of **20.35%** |
| 🎯 **On Track with Targets** | Target achievement is stated as **108.62%** across the organisation |
| 🔮 **Positive Outlook** | Forecast indicates continued revenue growth over the next 6 months |

> [!TIP]
> ✅ **Reading it:** this year's revenue and profit lines stay **well above the previous year's** in every month, and the green *Excellent Performance* banner says all key metrics are above target.

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| 📊 **Power BI Desktop** | Report authoring, data modelling and visual design |
| 🧮 **DAX** | Measures for revenue, profit, margin, target achievement, YoY growth, rankings and YTD |
| 🧱 **Power BI Data Model** | Dimension tables (Date, Region, Product, Dealer) and a sales fact table |
| 🧭 **Drill-down Hierarchies** | Region → Zone → State → City and Category → Sub Category → Product |
| 🗺️ **Map Visuals** | Filled maps of revenue by state and a dealer location map |
| 🎨 **Native Visuals** | Card, Column, Bar, Line, Area, Donut, Treemap, Scatter, Map, Matrix, Table, Slicer |
| 🖼️ **Custom Design** | Asian Paints branding, navy sidebar, icons, Reset buttons and call-out boxes |

---

## 🏆 Results & Insights

| Panel | Key Insight |
|---|---|
| 💰 **KPI Cards** | Revenue **₹702 Cr (+18.6%)**, profit **₹228 Cr (+20.3%)**, margin **32.50%**, orders **3,00,000 (+15.7%)** |
| 🌳 **Categories** | **Putty** (₹115 Cr) and **Interior Emulsion** (₹114 Cr) lead; **Waterproofing** is smallest at ₹80 Cr |
| 🗺️ **Regions** | **West** leads with **25%** of revenue; Central, East and North are level at 19%; South has 18% |
| 🔥 **Margins** | Profit margin stays within **32.4%–32.5%** across all regions |
| 🎨 **Products** | **Product 399** is the top product at **₹1.67 Cr** revenue and **₹0.54 Cr** profit; **Primer** has the best inventory turnover (**25.34**) |
| 🤝 **Dealers** | **5,000** dealers (+8.2%), satisfaction **4.32 / 5**, average revenue per dealer **₹14.03**; **Dewan Inc** is the top dealer |
| 📈 **Trends** | YTD revenue **₹131.64 Cr (+18.6%)**; YoY revenue growth **33.53%**, YoY profit growth **33.51%** |
| 🔮 **Outlook** | Forecast shows continued revenue growth over the next 6 months |

---

## 💡 Advantages

- ⚡ **Fully Interactive** — every card, chart and table responds to the filters, with no static exports
- 🧭 **Drill-down Everywhere** — go from Region to Zone, State and City, or from Category to Sub Category and Product
- 🆚 **Year-over-year Context** — most KPIs show the previous year and the % change
- 🧑‍💼 **360° Business View** — revenue, regions, products, dealers and trends in one report
- 🚦 **Quick Status Icons** — scorecards flag months above and below target at a glance
- 🔮 **Forward-looking** — a forecast and cumulative YTD view sit beside the history
- 🧮 **Centralised Measures** — all DAX lives in one `Measure Table`, easy to maintain
- 🗺️ **Map Views** — see where revenue and dealers concentrate across India
- 🎨 **Native Visuals Only** — opens cleanly in any standard Power BI Desktop install
- 🎬 **Presentation Included** — a Google Drive walkthrough explains the project end to end
- 🌱 **Room to Grow** — the model is ready for new pages such as inventory, pricing or campaigns

---

## ▶️ How to Open & Use

1. 🎬 **[Watch the project presentation on Google Drive](https://drive.google.com/file/d/1gJYjNji0b6CmmOdOIfxABj4vIr2mv4pW/view?usp=drive_link)** for a guided tour.
2. 💻 Install **Power BI Desktop** (free, Windows).
3. 📂 Open `Asianpaints_Dashboard.pbix`. The data is stored inside the file, so the visuals load immediately.
4. 🧭 Use the **sidebar buttons** to switch between the five pages.
5. 🖱️ Pick values in the **sidebar filters and top dropdowns** to filter every visual, or click a chart segment to cross-filter the page. Press **Reset** to clear everything.
6. 🔍 Use the **Hierarchy Level Slicer** and the drill arrows to move between Region → Zone → State → City or Category → Sub Category → Product.

---

## 🎬 Project Presentation

<div align="center">

<a href="https://drive.google.com/file/d/1gJYjNji0b6CmmOdOIfxABj4vIr2mv4pW/view?usp=drive_link">
  <img src="assets/video_thumbnail.png" alt="Click to watch the Project Presentation" width="760"/>
</a>

**👆 Click the thumbnail to watch the full project presentation on Google Drive**

[![Watch on Google Drive](https://img.shields.io/badge/Google_Drive-Watch_the_Presentation-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1gJYjNji0b6CmmOdOIfxABj4vIr2mv4pW/view?usp=drive_link)

</div>

| 🎞️ Detail | Info |
|---|---|
| ☁️ **Hosted on** | Google Drive |
| 🎨 **Project** | Asian Paints Executive Dashboard |
| 📄 **Pages covered** | Overview · Regional Performance · Product Analytics · Dealer Performance · Trends & Forecasting |
| 🛠️ **Built with** | Power BI Desktop and DAX |

**What the project covers**

| Step | What you will see |
|:---:|---|
| 🟦 **1** | The **Executive Overview** — headline KPIs, monthly revenue vs target, category treemap and the scorecard |
| 🟧 **2** | **Regional Performance** — rankings by region and state, revenue vs target and the profit-margin heatmap |
| 🟪 **3** | **Product Analytics** — top 10 products, category contribution, inventory turnover and the revenue-vs-profit scatter |
| 🟩 **4** | **Dealer Performance** — top dealers, revenue brackets, satisfaction ratings and dealer types |
| 🟥 **5** | **Trends & Forecasting** — YTD growth, year-over-year trends, forecast and the executive summary |
| 🎛️ **6** | **Live filtering** — every card and chart updates together |

---

## 🖼️ Dashboard Preview

<div align="center">

### 🟦 Page 1 — Executive Overview

<img src="Dashboard_Overview/Page 1 - Overview.png" alt="Asian Paints — Executive Overview" width="900"/>

*Five KPI cards, monthly revenue trend and revenue vs target, category treemap, revenue map and the executive scorecard.*

<br/>

### 🟧 Page 2 — Regional Performance

<img src="Dashboard_Overview/Page 2 - Regional performance.png" alt="Asian Paints — Regional Performance" width="900"/>

*Revenue by region and state, rankings, revenue vs target by region and the profit-margin heatmap.*

<br/>

### 🟪 Page 3 — Product Analytics

<img src="Dashboard_Overview/Page 3 - Product Analytics.png" alt="Asian Paints — Product Analytics" width="900"/>

*Top 10 products by revenue and profit, category contribution, inventory turnover and the revenue-vs-profit scatter.*

<br/>

### 🟩 Page 4 — Dealer Performance

<img src="Dashboard_Overview/Page 4 - Dealer Performance.png" alt="Asian Paints — Dealer Performance" width="900"/>

*Dealer KPIs, top 10 dealers, revenue distribution, satisfaction rating, dealer types and the dealer location map.*

<br/>

### 🟥 Page 5 — Trends & Executive Summary

<img src="Dashboard_Overview/Page 5 - Trends & Forecasting.png" alt="Asian Paints — Trends and Executive Summary" width="900"/>

*YTD KPIs, revenue and profit trends against the previous year, cumulative revenue, forecast and the executive summary.*

</div>

---

## 📄 License

```
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

---

## 👩‍💻 Author

<div align="center">

| | |
|---|---|
| 👤 **Name** | _KRINA GHORI_ |
| 📊 **Tool** | Power BI Desktop |
| 📁 **Project** | Asian Paints Executive Dashboard |
| 💡 **Purpose** | Interactive revenue, regional, product and dealer analytics dashboard |

<br/>

Made with 💙 using **Power BI**

![Power BI Love](https://img.shields.io/badge/Made%20with-%F0%9F%92%99%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

</div>

---

## 🙏 Acknowledgements

- 📊 **Microsoft Power BI Team** — for the report engine and visualization framework behind this dashboard
- 🎨 **Asian Paints** — whose branding and business domain inspired this analytics project
- 📖 **Power BI Documentation** — for reference on DAX, drill-down hierarchies, filled maps, scatter charts and native visuals
- 💻 **Open Source Community** — for README badge tools (shields.io) and typing SVG animations
- 🎓 **All learners** — who build dashboards like this to sharpen their BI fundamentals

---

<div align="center">

⭐ **Star this repo if you found it helpful!** ⭐

</div>
