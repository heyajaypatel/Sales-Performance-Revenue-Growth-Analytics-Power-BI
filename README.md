# Sales Performance & Revenue Growth Dashboard | Power BI

## 🎯 Project Objective
The objective of this project is to provide sales managers and executive leadership with a real-time view of commercial performance. By analyzing sales velocity, regional contributions, and revenue growth percentages, this dashboard identifies top-performing products and underperforming regions, allowing for strategic adjustments in sales tactics and resource allocation.

## 📊 Key Sales Metrics (KPIs)
* **Total Revenue:** Gross income generated from all sales transactions.
* **Growth %:** Month-over-month (MoM) or Year-over-year (YoY) revenue comparison to measure business momentum.
* **Units Sold:** Total volume of products moved.
* **Average Selling Price (ASP):** The average price at which products are being sold.
* **Sales Executive Performance:** Ranking of team members based on revenue generation and target achievement.

---

## 🛠️ Technical Workflow

### 1. Data Cleaning & Transformation (Power Query)
* **ETL Process:** Standardized regional naming conventions, handled missing transaction values, and validated currency formatting.
* **Advanced Logic:** Created custom columns for "Revenue per Unit" and "Discount Impact" to understand pricing elasticity.

### 2. Data Modeling (Star Schema)
* **Optimized Model:** Established relationships between Sales Fact tables and Dimension tables (Geography, Product, and Sales Team).
* **Time Intelligence:** Created a robust `DateTable` to support dynamic growth calculations and seasonal trend analysis.

### 3. DAX Analysis & Visualizations
* **Growth Calculation:** Used `PARALLELPERIOD` and `DIVIDE` to calculate accurate revenue growth percentages.
* **Dynamic Ranking:** Developed measures to rank Sales Executives and Product Categories dynamically based on filtered timeframes.

---

## 💡 Key Business Insights
* **Top Revenue Drivers:** Identified specific product categories that contribute to over 50% of the total revenue.
* **Regional Variance:** Discovered high-performing states where sales volume is high despite lower marketing spend.
* **Seasonality:** Pinpointed peak sales months, enabling better inventory planning and sales target setting.

## 📸 Dashboard Preview
> **Note to Recruiter:** This dashboard focuses on clarity and actionable data, utilizing high-contrast visuals for quick decision-making.
<img width="1920" height="1080" alt="Screenshot 2026-04-18 163522" src="https://github.com/user-attachments/assets/851cb370-16a0-446f-bb2c-62957fb4b509" />


## 🚀 How to Use
1. Clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Link the `Sales_Data.csv` from the `Dataset/` folder.
4. Interact with **Slicers** (Region, Sales Executive, Category) to drill down into specific performance data.

---
**Target Job Roles:** Sales Analyst | Business Analyst | Revenue Manager | Commercial Controller | Operations Analyst.
