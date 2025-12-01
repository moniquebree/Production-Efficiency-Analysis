# 🏭 Production Efficiency Dashboard

## 📊 Project Overview
This production efficiency dashboard analyzes manufacturing data to identify key drivers of cost, time, and efficiency by department, item, and month. It provides a high-level view of operational expenditure, totaling **28.36 Million** for the year across **521,510 hours** of labor.

## 🔍 Key Findings & Insights

### 1. Cost Drivers & Expenditure
* **Top Cost Driver:** "Ceilings" are identified as the number one cost driver, accounting for the highest total production cost.
* **Monthly Trends:** December is highlighted as the most costly month of the year.
* **Total Operations:** The business spent **28.36 Million** during the period, with an average company-wide cost per hour of **54.38**.

### 2. Efficiency Metrics (Cost Per Hour)
* **Most Expensive Efficiency:** While Ceilings cost the most in total, **Curtains** are the most costly item to make *per hour*.
* **Departmental Breakdown:** The dashboard calculates cost per hour for machine assembly, painting, and veneer. (Assumption: Painting is a sub-component of the top cost driver, Ceilings).

### 3. Departmental Performance
* **Revenue Generation:** The Doughnut Chart highlights which department generated the most money for the business, independent of their cost-per-hour efficiency.

## 📸 Dashboard Visuals

### Dashboard Snapshot
*A view of the main dashboard showing Cost Drivers, Efficiency (Cost/Hr), and Monthly Trends.*
![Dashboard Snapshot](Dashboard%20Snapshot.png)

## 🛠️ Technical Stack
* **Tool:** Microsoft Power BI
* **Scripting:** Python (`analysis.py`) for data pre-processing.
* **Key Metrics:** Total Cost, Total Hours, Cost Per Hour (CPH).
