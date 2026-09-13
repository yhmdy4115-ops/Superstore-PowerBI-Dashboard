# 📊 US Superstore Executive & Product Performance Dashboard (Power BI)

## 📌 Project Overview
An interactive **Power BI** analytics dashboard designed to monitor high-level executive KPIs, sub-category sales, regional performance, product profitability, and geographic distribution for the **Sample Superstore** dataset (2016–2019).

The project features a sleek, dark-themed user interface across **two detailed reporting pages** aimed at helping business stakeholders make data-driven growth and logistics decisions.

---

## 🖥️ Dashboard Architecture & Pages

### 1. Executive Overview Page
- **KPI Summary Cards:** Total Sales ($2.30M), Total Profit ($286.40K), Running Total Sales ($2.30M), and Overall Profit Margin (12.47%).
- **Sub-Category Sales Breakdown:** Bar chart ranking top product categories (Phones, Chairs, Storage, Tables, etc.).
- **Customer Segment Analysis:** Sales contribution across Consumer, Corporate, and Home Office segments.
- **Regional Performance:** Regional revenue leaders (West leading with $725.45K, followed by East).
- **Time Series Dynamics:** Trend line displaying sales performance by Year and Quarter.

### 2. Product & Profitability Analysis Page
- **Profitability Categorization:** Donut chart segmenting transactions into High, Medium, Low Profit, and Loss categories.
- **Profit vs. Sales Comparison:** Dual-metric bar visual examining revenue vs. margin across Technology, Furniture, and Office Supplies.
- **Top Cities Treemap:** Visualizing geographical revenue hubs (New York City, Los Angeles, Seattle, San Francisco, Houston, Chicago).
- **Interactive Slicers & Filters:** Category, Segment, Region, and Year slider filters for deep-dive analysis.

---

## 🛠️ Data Engineering & DAX Measures
- **Data Modeling & Relationships:** Built a structured data model connecting `Orders`, `Customer Segments`, `DateTable`, `People`, and `Returns`.
- **DAX Calculations:**
  - Dynamic **Running Total** measures.
  - Calculated **Profit Margin %** metrics.
  - Custom Profitability Bucketing (High, Medium, Low, Loss).
- **Interactive Visuals & UX:** Implemented slicer synchronization, custom tooltips, reset filter options, and seamless page navigation.

---

## 📁 Repository Structure
- `Youssef_Hamdy_Mekhael_Mini_Project_2.pbix` — Complete interactive Power BI dashboard file.
- `README.md` — Technical documentation and dashboard overview.

---

## 🚀 How to View
1. Download the `.pbix` file from this repository.
2. Open using **Power BI Desktop**.
3. Interact with slicers to filter by year, category, and regional parameters.
