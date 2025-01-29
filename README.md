# Power BI Pizza Sales Dashboard

## Overview
A Power BI dashboard to analyze pizza sales with insights on total sales, revenue trends, best-selling pizzas, and customer patterns.

## Process
1. **Data Preparation**: Clean and preprocess data using Power Query.
2. **Data Modeling**: Establish relationships between tables and optimize performance.
3. **Visualizations**: Use bar charts, pie charts, line graphs, and slicers.
4. **DAX Measures**:
   ```DAX
   Total Revenue = sum(pizza_sales[total_price])
   Total orders = DISTINCTCOUNT(pizza_sales[order_id]) 
   Avg order value = [Total Revenue]/[Total orders]
   Total pizza sold = SUM(pizza_sales[quantity])
   Avg pizza per order = [Total pizza sold]/[Total orders] 
   ```
5. **Interactivity**: Add filters, drill-through, and tooltips.
6. **Styling**: Apply themes, format numbers, and improve readability.
7. **Publishing**: Publish to Power BI Service and set up data refresh.
8. **Optimization**: Remove unnecessary columns, optimize DAX, and use aggregations.

## Tools Used
- **Power BI** – Visualization
- **SQL/Excel** – Data storage
- **DAX & Power Query** – Data processing

## Conclusion
This dashboard provides actionable insights into pizza sales. Future improvements can include predictive analytics and real-time data integration.

## Author
Sital Kumar Jagri
jagrisital01@gmail
+916360182657

