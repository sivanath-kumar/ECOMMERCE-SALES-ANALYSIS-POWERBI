# ECOMMERCE-SALES-ANALYSIS-POWERBI
End-to-end Ecommerce Sales Analysis Dashboard built using Power BI, SQL Server, and DAX to analyze sales performance, profit trends, customer segments, product performance, and regional insights.
This project focuses on building an interactive **Ecommerce Sales Analytics Dashboard using Microsoft Power BI**.

The objective of this dashboard is to analyze sales performance, customer behavior, profitability, product trends, and regional performance to support data-driven business decisions.

The dashboard provides insights into revenue growth, profit analysis, customer categories, product performance, shipping methods, and geographical sales distribution.

---

# 🎯 Business Problem Statement

An ecommerce company wants to create a Sales Dashboard to monitor business performance and generate insights for the following scenarios:

- Track overall sales and profit performance
- Analyze Year-To-Date (YTD) sales growth
- Compare current year vs previous year performance
- Identify top and bottom-performing products
- Understand customer category contribution
- Analyze state-wise and regional sales performance
- Evaluate shipping type performance

---

# 📊 KPI Requirements

The dashboard includes the following KPIs:

## 1. YTD Sales
- Displays current year-to-date sales performance.

## 2. YTD Profit
- Tracks total profit generated during the selected period.

## 3. YTD Quantity Sold
- Shows total products sold.

## 4. YTD Profit Margin
- Calculates profit percentage compared with sales.

**Formula:**

Profit Margin = (Profit / Sales) × 100


## 5. Year-over-Year (YoY) Growth Analysis

- Compares current year performance with previous year.
- Displays growth percentage trends.

---

# 📈 Dashboard Visualizations

## 1. KPI Banner

Includes:

- YTD Sales
- YTD Profit
- YTD Quantity
- YTD Profit Margin
- YoY Growth

Purpose:
Monitor overall business performance quickly.


---

## 2. Customer Category Analysis

Visualizes:

- YTD Sales
- Previous Year Sales
- YoY Growth

Categories:

- Consumer
- Corporate
- Home Office


Purpose:
Identify high-value customer segments.


---

## 3. State-wise Sales Performance

Chart Type:
Map / Bar Chart

Purpose:
Analyze sales contribution across different states.


---

## 4. Top 5 Products Analysis

Metrics:

- Sales
- Quantity
- Profit

Purpose:
Identify best-performing products.


---

## 5. Bottom 5 Products Analysis

Metrics:

- Sales
- Quantity
- Profit

Purpose:
Identify low-performing products and improve product strategy.


---

## 6. Regional Sales Analysis

Analyzes:

- YTD Sales by Region
- Best and worst performing regions

Regions:

- East
- West
- Central
- South


---

## 7. Shipping Type Analysis

Purpose:

Analyze sales distribution based on shipping methods.

Examples:

- Standard Class
- Second Class
- First Class
- Same Day


---

# 🛠 Project Steps

## 1. Problem Statement

Understanding business requirements and defining KPIs.

## 2. Data Import

Imported data from:

- MS SQL Server
- Flat Files / Excel

## 3. Data Cleaning

Performed using Power Query:

- Removed duplicates
- Handled missing values
- Changed data types
- Prepared clean datasets

## 4. Data Modeling

Created relationships between tables.

Implemented:

- Fact Table
- Dimension Tables
- Star Schema Model


## 5. Date Table Creation

Created a calendar table for:

- Year analysis
- Month analysis
- Time intelligence calculations


## 6. DAX Calculations

Created measures using:

- CALCULATE()
- SUM()
- SUMX()
- FILTER()
- VALUES()
- SELECTEDVALUE()
- DIVIDE()


Implemented:

- YTD calculations
- PYTD calculations
- YoY Growth
- Profit Margin


## 7. Dashboard Development

Created interactive visuals:

- Cards
- Charts
- Maps
- Tables
- Slicers


## 8. Insight Generation

Generated business insights from:

- Sales trends
- Customer behavior
- Product performance
- Regional analysis


---

# 🧰 Tools & Technologies Used

- Microsoft Power BI
- SQL Server
- Power Query
- DAX
- Data Modeling
- Excel


---

# 💡 Skills Demonstrated

✔ Data Cleaning  
✔ Data Transformation  
✔ SQL Data Extraction  
✔ Data Modeling  
✔ DAX Measures  
✔ Time Intelligence  
✔ KPI Development  
✔ Dashboard Design  
✔ Business Analysis  


---

# 📌 Project Outcome

This dashboard helps ecommerce stakeholders:

- Monitor sales performance
- Identify growth opportunities
- Improve product strategies
- Understand customer behavior
- Make data-driven decisions

