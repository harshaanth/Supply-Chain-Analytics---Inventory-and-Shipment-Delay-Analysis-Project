# Inventory and Shipment Delay Analysis Project

## Project Overview
This project analyzes inventory levels and shipment delays using Tableau to optimize supply chain performance and inventory management. The objective is to identify key areas for improvement in shipment speed, stock management, and overall operational efficiency.

## Context
Efficient supply chain management is essential for operational success. By monitoring inventory levels and analyzing shipment delays, companies can make data-driven decisions to optimize stock levels, improve customer satisfaction, and reduce logistical bottlenecks. This analysis identifies shipment delay trends over time and pinpoints product categories that frequently experience understock or overstock issues.

---

## Data Sources, Connections, and Fields
The project integrates data from three main sources, connected to create a unified data model in Tableau:

1. **Data Sources**
   - **orders_and_shipments**: Contains monthly order data and shipment details, providing insights on order trends, shipment delays, and fulfillment metrics.
   - **inventory**: Tracks stock levels across various product categories, helping assess the health and balance of inventory.
   - **fulfillment**: Includes information on warehouse order fulfillment times, allowing for the evaluation of supply chain efficiency.

2. **Data Connections**
   The data sources are connected in Tableau as follows:
   - `orders_and_shipments` is joined with `inventory` on the `Product ID` field to align orders with their corresponding inventory levels.
   - `inventory` is joined with `fulfillment` on the `Warehouse ID` field, linking inventory data to fulfillment times by warehouse.
   - 
---

## Tools and Technologies
- **Tableau**: Used for data visualization and building interactive dashboards.
- **Data Sources**: Integrated from multiple Microsoft Excel files to create a unified data model in Tableau.
- **Git**: Version control and management for project files and assets.

---

## Dashboards
### 1. Inventory Levels Dashboard
   - **Purpose**: Monitors inventory across product categories, identifying understocked and overstocked items.
   - **Features**: Visual representation of stock levels by category to understand supply-demand alignment.
   - **Insights**: Highlights persistently understocked categories, suggesting a need for refined forecasting or adjustments in stock ordering cycles. Frequent fluctuations, particularly in Women’s Apparel, indicate areas requiring attention.

### 2. Shipment Delays Dashboard
   - **Purpose**: Analyzes shipment delays over time, showing patterns and identifying periods with high or low delivery times.
   - **Features**: Trend line of average shipment delay, breakdown by month, and filter options for regional analysis.
   - **Insights**: Reveals significant shipment delays before mid-2016, with a marked improvement afterward, potentially indicating changes in supply chain processes or logistics.

---

## Story Points and Key Insights
A **Story Point** summarizes major findings for stakeholder review:
1. **Highest Monthly Order Quantity**: October 2016, with 2.3K orders.
2. **Month with Most Delays**: January 2015, with 61% of orders delayed over 5 days.
3. **Last Notable Delay Spike**: May 2016 had average delays above 0.5 days.
4. **Overstocking and Understocking Patterns**:
   - Top overstock category: **Toys** (2nd in monthly overstock).
   - Category with the highest supply exceeding demand: **Cleats**.
5. **Country-Specific Delays**: U.S. warehouse noted for having average shipment delays exceeding the global benchmark (0.5 days).
6. **Supply-Demand Imbalance**: **Indoor/Outdoor Games** category deviates from the supply = demand line.

---

## Conclusion
This Tableau analysis highlights critical areas of improvement:
1. **Reduction in shipment delays post-May 2016**, indicating effective improvements in logistics.
2. **Persistent under- and overstock issues** in categories like Women’s Apparel and Toys suggest a need for better demand forecasting and inventory planning.
3. **U.S. warehouse delays** exceed the global average, warranting further regional adjustments.

These insights can support better decision-making in inventory management and logistics, aiming for higher customer satisfaction and operational efficiency.

---

## Best Practices for Analytical Work in Tableau
1. **Data Integration**: Connect all data sources and build a unified data model.
2. **Data Preparation**: Set correct data types, dimensions/measures designation, and hide unnecessary fields.
3. **Iterative Exploration**: Explore data with worksheets and create calculated fields and parameters as needed.
4. **Dashboard Design**: Identify themes for dashboard creation, combining worksheets into cohesive insights.
5. **Interactivity**: Add and test interactive elements (filters, dashboard actions) to improve user experience.
6. **Data Storytelling**: Assemble dashboards and visualizations into a story point to guide stakeholders through key findings.
