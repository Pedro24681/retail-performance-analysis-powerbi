# retail-performance-analysis-powerbi
Greetings! This project I made analyzes retail sales performance using the Superstore dataset. My goal here was to design a professional, interactive Power BI dashboard that highlights key business performance metrics, regional trends, category profitability and sales patterns over time. I've created a 'screenshots' folder to showcase the interactive dashboard as well. Please reference that.
This case study demonstrates my ability to:
- Clean and model data
- Create DAX measures
- Build KPI visuals
- Design interactive dashboards
- Communicate insights in a business-friendly way



# Dashboard Overview

The **Retail Performance Dashboard** includes:
- **4 KPI Cards:** Total Sales, Total Profit, Profit Margin, Average Shipping Days  
- **Sales by Category** (bar chart)  
- **Sales by Region** (bar chart)  
- **Sales Over Time** (line chart with monthly trend)  
- **Interactive Slicers:** Region and Category  

This dashboard allows business users to filter and explore sales performance across different dimensions to support decision-making.



# Tools & Skills Used

**Tools**
- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query  
- Excel / CSV (data source)

**Skills**
- Data modeling  
- KPI design  
- DAX measures  
- Data visualization  
- Dashboard layout & UX  
- Business insights communication  



# DAX Measures Used

```DAX
Total Sales = SUM('Sample - Superstore'[Sales])

Total Profit = SUM('Sample - Superstore'[Profit])

Total Quantity = SUM('Sample - Superstore'[Quantity])

Average Shipping Days = AVERAGE('Sample - Superstore'[Shipping Days])

Profit Margin = DIVIDE([Total Profit], [Total Sales])
