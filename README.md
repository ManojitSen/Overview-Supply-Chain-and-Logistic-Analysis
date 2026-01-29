# Overview Supply Chain and Logistics (Using Microsoft PowerBi)
## Project Overview
This project uses a comprehensive dataset that models an end-to-end supply chain, production, and sales ecosystem for a global consumer electronics company.
The data integrates master data and transactional data to enable deep analysis of business performance, operational efficiency, and profitability across regions, facilities, products, and customers.
The dataset is well-suited for Excel dashboards, Power BI reports, SQL analysis, and data analytics projects.

## Dataset Used
Your dataset represents an end-to-end supply chain and sales ecosystem, combining master data (customers, products, suppliers, facilities, and dates) with transactional data (inventory, procurement, production, sales, and shipments). It enables detailed analysis of operations, costs, quality, logistics, and profitability across the entire business lifecycle.
The structure supports time-based trend analysis and performance comparisons across regions, facilities, and sales channels. Supplier and procurement data help evaluate lead times, quality, and sourcing efficiency. Inventory and production tables enable demand planning, stock optimization, and defect analysis. Sales data links revenue and profit to customers and products, while shipment data tracks delivery performance and logistics costs.
- <a href="https://github.com/ManojitSen/Overview-Supply-Chain-and-Logistic-Analysis/blob/main/DATA.zip">Dataset</a>

## Business Questions (KPIs)
-  What is the total revenue generated across products, customers, and time periods?
- How much profit is being generated, and which products or customers contribute the most?
- What is the overall profit margin (%), and how does it vary by product category or sales channel?
- Are higher sales quantities translating into better profitability?
- What is the total sales quantity, and how does demand trend over time?
- Which products or regions have the highest and lowest sales volumes?
- How much quantity is successfully delivered vs delayed?
- What is the total order quantity placed with suppliers?
- What is the total sales cost, and how does it impact overall profit?
- Are procurement costs aligned with sales revenue?
- What is the current safety stock level, and is it sufficient to meet demand?
- Are there products with excess or insufficient safety stock?
- How many total shipments were made in a given period?
- What percentage of shipments are delayed?
- How much quantity is delayed, and how does it impact customer deliveries?
- Which carriers or routes contribute most to shipment delays?
- What is the delivery fulfillment rate (delivered quantity vs total sales quantity)?
- How do shipment delays affect revenue, profit, and customer satisfaction?
- Dashboard Interaction <a href="https://github.com/ManojitSen/Overview-Supply-Chain-and-Logistic-Analysis/blob/main/Dashboard_Screenshot.jpg">View Dashboard</a>

## Process
-  Collected and reviewed raw supply chain, sales, inventory, procurement, and shipment data to understand the overall business flow and key operational dependencies.
- Performed data validation and cleaning to handle missing values, duplicates, and inconsistencies, ensuring high data accuracy and reliability.
- Standardized data types, formats, and categorical fields across all fact and dimension tables to enable seamless modeling and analysis.
- Built a structured data model by establishing relationships between sales, procurement, inventory, shipment, supplier, product, customer, and date tables.
- Created business-driven DAX measures and KPIs, including total revenue, profit, profit margin, order quantity, safety stock, shipment volume, delivery quantity, and delay metrics.
- Analyzed procurement costs, inventory levels, and shipment performance to identify inefficiencies, delays, and cost drivers in the supply chain.
- Designed interactive visuals and KPI cards to track sales performance, profitability, inventory health, and logistics efficiency.
- Integrated all insights into a single interactive dashboard with filters and slicers for time, product, supplier, facility, and customer-level analysis.

## Dashboard
![Dashboard_Screenshot](https://github.com/user-attachments/assets/2bec2cb5-e091-4e00-a25b-58c6f04d4b89)

## Project Insights
-  The business maintains strong financial performance with a 27.44% profit margin, reflecting efficient cost and pricing strategies.
- Inventory levels are well-aligned with demand, as 160K inventory quantity supports 129K order quantity, reducing stock-out risks.
- High logistics volume is evident with 3M shipment quantity across 7,500 shipments, indicating large-scale supply chain operations.
- Only 75% of orders are perfectly delivered, highlighting improvement opportunities in delivery accuracy and fulfillment reliability.
- Maersk Line, DHL Express, and DB Schenker account for the highest shipment delays, making them key focus areas for logistics optimization.
- High-value products such as Galaxy S24 Ultra and Galaxy Buds2 Pro dominate inventory value, requiring tighter inventory control to optimize working capital.
- Top customers including Amazon, Flipkart, and Best Buy contribute the majority of revenue, emphasizing the importance of strategic customer partnerships.

## Conclusion
This project delivers a comprehensive view of Samsung’s supply chain and logistics performance by integrating sales, inventory, procurement, and shipment data into a single analytical dashboard. The analysis highlights strong profitability and scalable operations while also revealing key improvement areas such as shipment delays and order fulfillment efficiency. By identifying high-value products, critical suppliers, and top customers, the dashboard enables data-driven decision-making to optimize inventory levels, reduce logistics bottlenecks, and strengthen overall supply chain performance.
