# Supply-Chain-Performance-and-Logistics-Analysis
An end-to-end data analytics project using SQL and Power BI to evaluate sales performance, inventory indicators, supplier operations, product quality, and shipping efficiency. The project transforms supply chain data into actionable business insights through SQL-based analysis and an interactive, three-page Power BI dashboard.

# 📦 Supply Chain Performance & Logistics Analytics

An end-to-end data analytics project using **SQL and Power BI** to evaluate sales performance, inventory indicators, supplier operations, product quality, and shipping efficiency. The project transforms supply chain data into actionable business insights through SQL-based analysis and an interactive, three-page Power BI dashboard.

---

## 📌 Project Overview

Supply chain operations involve balancing sales performance, inventory availability, manufacturing efficiency, product quality, and logistics costs. Analysing these areas together can help businesses identify operational bottlenecks, understand cost patterns, and make more informed decisions.

This project analyses a supply chain dataset containing **100 SKUs** across product categories, suppliers, manufacturing operations, and logistics activities.

The analysis is organised into two dashboard pages:

1. **Sales Analysis** – Understand revenue contribution, sales volume, and product performance.
2. **Shipping Analysis** – Compare shipping durations and costs across routes, carriers, transportation modes, and product categories.

## 🎯 Business Objectives

* Identify the product categories and SKUs contributing most to revenue and sales volume.
* Examine inventory levels relative to recorded product sales to flag items for further review.
* Compare supplier lead times, manufacturing costs, and quality indicators.
* Identify routes, carriers, transportation modes, and product categories associated with longer shipping durations.
* Translate analytical findings into potential areas for operational investigation and improvement.

## 🛠️ Tools & Technologies

| Tool            | Purpose                                                             |
| --------------- | ------------------------------------------------------------------- |
| **MySQL**       | Data exploration, aggregation, segmentation, and logistics analysis |
| **Power BI**    | Interactive dashboard development and data visualisation            |
| **DAX**         | KPI calculations and analytical measures                            |
| **Power Query** | Data preparation and transformation                                 |

## 📊 Dataset

The dataset includes supply chain information across the following areas:

| Area                 | Key Fields                                                                      |
| -------------------- | ------------------------------------------------------------------------------- |
| Sales                | Product type, SKU, Price, Number of products sold, Revenue generated            |
| Inventory            | Availability, Stock levels, Order quantities                                    |
| Suppliers            | Supplier name, Location, Lead time                                              |
| Manufacturing        | Production volumes, Manufacturing lead time, Manufacturing costs                |
| Quality              | Inspection results, Defect rates                                                |
| Shipping & Logistics | Shipping times, Shipping carriers, Shipping costs, Transportation modes, Routes |

**Dataset size:** 100 records / SKUs as analysed in the project.

## 📈 Dashboard

### 1. Sales Analysis

**Objective:** Understand product-level and category-level sales performance.

Key analyses:

* Revenue contribution by product category.
* Units sold by product category.
* Top-performing SKUs by revenue.
* Revenue versus units sold to compare product performance.
* Category and SKU-level performance using a drill-down matrix.

**Business value:** Helps identify revenue-contributing categories and products that may warrant further commercial analysis.

### 2. Operational Analysis

**Objective:** Investigate inventory, supplier, manufacturing, and quality performance.

Key analyses:

* Stock levels compared with recorded units sold.
* Average supplier lead time.
* Manufacturing cost by supplier.
* Inspection results distribution.
* Average defect rate by product category.
* Supplier and SKU-level manufacturing comparisons.

**Business value:** Helps flag inventory, supplier, and quality patterns for further investigation.

### 3. Shipping Analysis

**Objective:** Evaluate shipping duration and cost patterns across logistics dimensions.

Key analyses:

* Average shipping time by route.
* Shipping cost by transportation mode.
* Average shipping time by carrier.
* Shipping time by route and product category.
* Shipping cost by location.
* Detailed logistics comparisons by SKU, carrier, mode, and route.

**Business value:** Helps identify longer-duration shipping segments and areas where logistics costs or carrier allocation may need review.

## 🔍 Key Insights

* **Skincare was the largest contributor to sales volume**, generating approximately 0.24M in revenue and 21K units sold, accounting for around 45% of total units sold.
* **Cosmetics recorded the highest average shipping time**, at approximately 6.58 days.
* A drill-down of the Cosmetics segment identified **Carrier A, Rail transportation, and Route B** as a combination with a recorded average shipping time of approximately 9.50 days, flagging it for further logistics investigation.

## 💡 Potential Business Recommendations

* Review shipping arrangements for category-route combinations with longer average durations.
* Compare carriers within the same transportation mode and route before considering changes to carrier allocation.
* Investigate SKUs with relatively high sales volume and low recorded stock levels.
* Review suppliers with higher lead times or defect rates to understand whether process or quality improvements are needed.
* Monitor shipping costs alongside shipping duration to assess trade-offs between cost and transit performance.

These are investigation opportunities based on the available data, not measured savings or confirmed root causes.

## ⚠️ Data Limitations

* The dataset does not include order dates, so monthly trends, seasonality, and time-based consistency cannot be assessed.
* Promised delivery dates or an agreed delivery SLA are unavailable; therefore, genuine on-time and late-delivery rates cannot be calculated.
* Stock levels compared with units sold are indicative comparisons, not direct measures of stockout frequency or inventory turnover.
* Supplier and carrier comparisons reveal patterns and associations, not proof of causation.
* Cost definitions and units should be validated before interpreting results as profit, margin, or fully loaded logistics cost.

## 🚀 Project Workflow

1. Explored the dataset and reviewed available fields.
2. Used SQL to aggregate and compare sales, operational, and logistics metrics.
3. Developed KPIs and measures using DAX.
4. Built a three-page interactive Power BI dashboard.
5. Investigated category, supplier, carrier, transportation-mode, and route-level patterns.
6. Developed evidence-based observations and recommendations while documenting data limitations.


## 📌 Conclusion

This project demonstrates how SQL and Power BI can be used to turn supply chain data into structured business analysis. By connecting sales, operations, and logistics perspectives, the dashboard supports product performance evaluation, operational monitoring, and targeted investigation of shipping duration and cost patterns.

---

**Skills demonstrated:** SQL · MySQL · Power BI · DAX · Data Visualisation · KPI Development · Root Cause Analysis · Business Insights

