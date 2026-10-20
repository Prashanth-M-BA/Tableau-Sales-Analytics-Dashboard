# 📊 Global Sales & Logistics Performance Dashboard (Tableau)

## 📌 Executive Summary
This project analyzes cross-border sales and shipment operations across **6 key international markets**. Using **Tableau Public**, the dashboard synthesizes high-level revenue KPIs, geographical performance, and top sales representative achievements to enable executive decision-making.

---

## 📸 Dashboard Overview
![Business Summary Dashboard](./Tableau%20Visual%20Report.png)

> **Live Interactive Dashboard:** [View on Tableau Public](https://public.tableau.com/views/YOUR_WORKBOOK_LINK)

---

## 📈 Key Business Metrics
* **Total Sales Revenue:** ₹6,183,625
* **Total Volume Shipped:** 177,007 Boxes
* **Total Shipments Handled:** 1,094 Shipments

---

## 🔍 Visualizations & Business Insights

### 1. Sales by Country (Geographic Revenue Distribution)
* **Markets Analyzed:** Australia, Canada, India, New Zealand, UK, and USA.
* **Key Insight:** Revenue is evenly distributed across international territories, with each country consistently generating around **1,000K (1M)** in total sales amount, demonstrating robust market diversification.

### 2. Sales by Top 10 Persons (Sales Representative Performance)
* **Top Performers Identified:** Highlights top 10 sales executives including *Ches Bonnell*, *Madelene Upcott*, *Kelci Walkden*, *Brien Boise*, and *Oby Sorrel*.
* **Key Insight:** Top sales reps consistently generate between **250K and 320K** in revenue individually, showing strong sales force efficiency across regions.

---

## 🛠️ Tableau Basics & Technical Concepts Applied

### 🔹 1. Data Connection & Preparation Basics
* **Data Ingestion:** Connected raw Excel/CSV data source into Tableau Data Source workspace.
* **Data Types & Roles:** Configured dimensions (e.g., `Country`, `Sales Person`) and measures (e.g., `Amount`, `Boxes Shipped`, `Shipment Count`).

### 🔹 2. Fundamental Chart Types & Formatting
* **KPI Summary Cards:** Configured aggregated text mark cards (`SUM(Amount)`, `SUM(Boxes Shipped)`, `COUNT(Shipments)`) for executive-level summaries.
* **Vertical Bar Chart:** Built for discrete geographical comparison (`Country` vs. `Amount`).
* **Horizontal Bar Chart:** Utilized for categorical ranking and clear label readability (`Sales Person` vs. `Amount`).
* **Number & Currency Formatting:** Applied custom currency prefixes (`₹`) and abbreviated display units (`K` for thousands).

### 🔹 3. Dashboard Layout & Design Fundamentals
* **Worksheet Composition & Layout:** Combined multiple individual sheets (`Sheet 1`, `Sheet 2`, `Sheet 3`) into a single, cohesive **Business Summary Dashboard**.
* **Container Management:** Used tiled object containers, padding adjustments, and clean typographic hierarchy to ensure professional presentation.

---

## 📁 Repository Structure
* `/images`: Contains dashboard preview screenshots.
* `/data`: Dataset file (`.xlsx` / `.csv`).
* `Business_Summary_Dashboard.twb`: Raw Tableau workbook file.
