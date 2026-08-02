# NutriBite-Foods-Sales-Performance-Dashboard
Transforming Sales Data into Business Insights: A Comprehensive Excel Power Pivot Dashboard for Revenue and Profit Optimization

**Sales Performance Analysis and KPI Dashboard Using Power Pivot in Excel**

**Project Overview**

This project provides a comprehensive sales analysis dashboard using Power Pivot in Excel, designed to help businesses monitor key performance indicators (KPIs) and drive strategic decisions. The dataset Sales Inventory includes financial, product, product category, region, state, and sales channel data structured into star schema model.

**Key Objectives:**

- Build an interactive Power Pivot model to analyze sales trends.
- Create dynamic KPIs (e.g., total quantity, total revenue, average revenue, minimum and maximum revenue)
- Use Excel cube functions and SL Functions to enhance dashboard interactivity.
- Provide business recommendations to optimize sales, revenue and profitability.

**Data Model (Star Schema Design)**

The data model follows a start schema with a fact table (sales_inventory) and multiple dimension tables:

1. **Sales_Inventory**: Sales transactions with cost, revenue, and quality details.
2. **Product_Category**: Product  classifications.
3. **Products**: Product details.
4. **Region**: Different region chanels.
5. **State**: Sales performance by state.
6. **Date**: Derived time-based table for dynamic reporting.

**Calculated Columns (DAX in Power Pivot)**

To enrich the dataset, the following calculated columns were created:
- **Profit Margin** = (Profit / Revenue) * 100
- **Revenue** = Quantity Sold * Price
- **Expenses** = Quantity Sold * Cost of Sales
- **Profit** = Revenue - Expenses
- **Profit Category**: High or Low, based on comparison with the average profit.

**Business Questions Answered**

- Top and bottom performing products by revenue and demand.
- Total quantity and revenue Sales across Regions and States
- Monthly Sales trends

**KPIs Monitored**

- Total Quantity
- Total Revenue
- Average Revenue
- Minimum Revenue
- Maximum Revenue

Tools & Technologies Used

- **Microsoft Excel** (Power Pivot, Pivot Tables, Cube & SL Functions)
- **DAX** (Data Analysis Expressions) for calculated columns and measures.
- **Data Modelling** (Star Schema Design)
- **Data Visualization in Excel Dashboards**
 
**Recommendations to Improve Sales & Revenue**

- Replicate June 2022 and November 2023 strategies to maintain peak sales momentum.
- Focus marketing on top-performing products to maximize revenue.
- Use of feedback mechanism to get customer response and view on the bottom performing products in order to understand and rectify the low sales, thereby eventually improving sales.
- Expand operations in profitable states and regions to optimize sales channels.
- Introduce seasonal promotions and loyalty programs to increase customer retention.
- Monitor KPIs in real time using the dashboard for data-driven decision making.
- Implement predictive modelling as sales growth to forecast future sales and proactively adjust inventory marketing and pricing strategies.

**Conclusion**

This project demonstrates how Power Pivot in Excel can be used for advanced business intelligence, enabling companies to analyze sales performance efficiently. By leveraging DAX calculations, Pivot Tables, and KPI tracking, businesses can gain actionable insights and drive revenue growth.
