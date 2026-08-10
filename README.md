# Supplier-Performance-Dashboard
An interactive Excel dashboard designed to evaluate supplier performance, identify operational risk, and support supplier relationship management decisions in a manufacturing environment.
## Dashboard Preview
![Supplier Relationship Management Dashboard](Supplier%20Dashboard%20Preview.png)
## Business Problem
Manufacturing organizations depend on suppliers to deliver the right material, in the right quantities, at the right time, and at the required quantity level.
When supplier performance is evaluated across separate reports, procurement teams can struggle to quickly identify which suppliers require attention and where operational risk is concentrated.
This project was developed to create a consolidated supplier performance view that allows procurement and supplier relationship management teams to monitor supplier performance, risk, spend, quality, and reliability from one interactive dashboard.
## Project Objective
The objective of this analysis was to answer several key supplier management questions:
- Which suppliers represent the greatest portion of procurement spend?
- Which suppliers are performing strongest and weakest?
- How effectively are suppliers meeting delivery and quantity requirements?
- Where is supplier-related operational risk concentrated?
- Which suppliers should be prioritized for performance improvement?
- How are delivery performance and lead times changing over time?
## Dashboard KPIs
The executive dashboard tracks:
- Total Spend
- On-Time Delivery (OTD)
- Total Suppliers
- Open Orders
- High-Risk Orders
- High-Risk Suppliers
- Fill Rate
- Expedite Orders
- Quality Pass Rate
- ASN Compliance
- PO Acknowledgement
- Partial Shipment Rate
- Perfect Order Rate
## Supplier Performance Scorecard
A supplier scorecard was developed to provide a balanced measure of supplier performance across delivery, fulfillment, and quality.
**Supplier Score = (OTD x 40%) + (Fill Rate x 30%) + (Quality Pass Rate x 30%)**
Suppliers are then classified into performance categories to help identify strong performers and suppliers requiring additional monitoring.
The scorecard also displays supplier spend to provide additional context when evaluating supplier relationships.
## Key Insights
- **Supplier risk requires attention:** 14 of 20 suppliers are associated with high-risk activity, with 533 high-risk orders across the portfolio.
- **Quality represents the largest performance gap:** Quality Pass Rate is 82%, compared to 94% Fill Rate and 89% On-Time Delivery.
- **Spend is concentrated among strategic suppliers:** The top three suppliers represent approximately 39% of total procurement spend, increasing the importance of supplier performance.
- **Operational intervention remains significant:** 604 expedited orders, 78% ASN compliance, and a 79% Perfect Order Rate indicate opportunities to strengthen supplier  planning and execution.
- **Lead-time performance requires investigation:** Average lead time increases significantly toward the end of the reporting period, indicating potential capacity, sourcing, or planning constraints.
## Interactive Analysis
The dashboard includes slicers that allow users to analyze supplier performance by:
- Supplier
- Commodity Category
- Manufacturing Plant
- Buyer
- Supplier Risk
- Production Priority
Visualizations dynamically update based on the selected filters.
## Tools & Skills Demonstrated
- Microsoft Excel
- PivotTables
- PivotCharts
- Interactive Slicers
- Excel Formulas
- Conditional Formatting
- KPI Development
- Supplier Performance Analysis
- Spend Analysis
- Supplier Scorecard Development
- Dashboard Design & Data Visualization
## Dataset
The analysis is based on approximately **6,000 manufacturing purchase order lines** covering multiple suppliers, SKUs, commodity categories, manufacturing plants, order quantities, pricing, delivery performance, quality results, payment status, and supplier risk indicators.
The Excel workbook contains the source data, supporting PivotTables, calculations, and interactive dashboard so the complete analytical workflow can be reviewed.
>**Data Disclaimer:** All supplier names, purchase orders, financial values, and operational data used in this project are synthetic and were created solely for portfolio and educational purposes. No confidential employer or supplier information is included.
## Workbook
Download 'Supplier_Performance_Dashboard.xlsx' from this repository to explore the interactive Excel dashboard.
