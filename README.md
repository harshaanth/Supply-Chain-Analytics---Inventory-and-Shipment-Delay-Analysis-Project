# Inventory and Shipment Delay Analysis Project

## Project Overview
This project analyzes inventory levels and shipment delays using Tableau to optimize supply chain performance and inventory management. The objective is to identify key areas for improvement in shipment speed, stock management, and overall operational efficiency.

## Context
Efficient supply chain management is essential for operational success. By monitoring inventory levels and analyzing shipment delays, companies can make data-driven decisions to optimize stock levels, improve customer satisfaction, and reduce logistical bottlenecks. This analysis identifies shipment delay trends over time and pinpoints product categories that frequently experience understock or overstock issues.

---

## Data Sources
The project integrates data from three main sources, connected to create a unified data model in Tableau:

   - **orders_and_shipments**: Contains monthly order data.
   - **inventory**: Contains inventory costs, and warehouse details.
   - **fulfillment**: Includes information on warehouse order fulfillment times, allowing for the evaluation of supply chain efficiency.

## Tools and Technologies
- **Tableau**: Used for data visualization and building interactive dashboards.
- **Data Sources**: Integrated from multiple Microsoft Excel files to create a unified data model in Tableau.
- **Git**: Version control and management for project files and assets.

---

## Dashboards
### 1. Shipment Delays Dashboard
![Shipment Dashboard](https://github.com/user-attachments/assets/01f2c621-188b-4400-a89f-729dd16d756a)
   - **Purpose**: Analyzes shipment delays over time, showing patterns and identifying periods with high or low delivery times.
   - **Features**: Trend line of average shipment delay, breakdown by month, and filter options for regional analysis.
   - **Insights**: Reveals significant shipment delays before mid-2016, with a marked improvement afterward, potentially indicating changes in supply chain processes or logistics.
     
### 2. Inventory Levels Dashboard
![Inventory Dashboard](https://github.com/user-attachments/assets/f0f0e297-96b6-444b-a35f-279cacc72b7f)
   - **Purpose**: Monitors inventory across product categories, identifying understocked and overstocked items.
   - **Features**: Visual representation of stock levels by category to understand supply-demand alignment.
   - **Insights**: Highlights persistently understocked categories, suggesting a need for refined forecasting or adjustments in stock ordering cycles. Frequent fluctuations, particularly in Women’s Apparel, indicate areas requiring attention.

---

## Story Points and Key Insights
![Findings - 1](https://github.com/user-attachments/assets/8061319e-3d23-4bd7-9dee-eddbf12baf50)
![Findings - 2](https://github.com/user-attachments/assets/a74a6aa1-fd84-4d38-86d7-234da66332d1)

## A Story Point Summarizes Major Findings for Stakeholder Review:

1. **Highest Monthly Order Quantity:**  
   - **October 2016**, with **2.3K orders**.

2. **Month with Most Delays:**  
   - **January 2015**: **17.03% delayed over 5 days**, and 37.45% delayed up to 5 days.

3. **Last Notable Delay Spike:**  
   - **May 2016** saw **average delays exceeding 0.5 days**, indicating a significant spike.

4. **Overstocking and Understocking Patterns:**  
   - **Top Overstock Category:** Toys, ranked **2nd** in monthly overstock frequency.
   - **Highest Supply Exceeding Demand:** Cleats.
   - **Supply-Demand Imbalance:** Indoor/Outdoor Games category shows a recurring mismatch, deviating from the supply = demand line.

5. **Country-Specific Delays:**  
   - **Overall (ALL):** 61% of orders delayed, with an average delay time of 0.5 days.
   - **Puerto Rico:** Slightly lower percentage of delayed orders at **60.1%**, but a **higher average delay time of 1.4 days**, highlighting logistical challenges that extend delivery times.
   - **USA:** Higher delayed order percentage at **61.5%**, yet a **lower average delay time of -0.1 days** (indicating minor lead-time gains).

## Conclusion:
This Tableau analysis highlights critical areas for improvement:

- **Reduction in shipment delays post-May 2016** suggests effective logistical adjustments, though regional delay patterns in Puerto Rico and the U.S. warrant further review.
- **Persistent under- and overstocking** in categories like Women’s Apparel and Toys calls for enhanced demand forecasting and inventory planning.
- **U.S. warehouse delays** show minor improvements in delay time despite a higher frequency of delays, while Puerto Rico’s prolonged delays indicate a need for regional focus.

These insights offer a foundation for improved inventory management and logistics, aiming for increased customer satisfaction and operational efficiency.

---

## Best Practices for Analytical Work in Tableau
1. **Data Integration**: Connect all data sources and build a unified data model.
2. **Data Preparation**: Set correct data types, dimensions/measures designation, and hide unnecessary fields.
3. **Iterative Exploration**: Explore data with worksheets and create calculated fields and parameters as needed.
4. **Dashboard Design**: Identify themes for dashboard creation, combining worksheets into cohesive insights.
5. **Interactivity**: Add and test interactive elements (filters, dashboard actions) to improve user experience.
6. **Data Storytelling**: Assemble dashboards and visualizations into a story point to guide stakeholders through key findings.

## Files in Repository

- **HarshaanthKumar_ThiyagarajaKumar_DataCampSC.twbx**: 
  - Tableau workbook file containing all data connections, dashboards, and story points for the analysis.
  - This workbook is self-contained, with multiple data sources integrated to analyze inventory levels and shipment delays.
  - Open this file in Tableau Desktop or Tableau Online to interact with the data visualizations and explore insights.
