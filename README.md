# Blink-it-sales-dashboard

To analyze Blinkit's historical sales data and build an interactive dashboard that highlights:

- Revenue trends over time  
- Top-performing products and categories  
- Region-wise sales breakdown  
- Customer behavior and purchase patterns  
- Key sales KPIs (Revenue, Orders, Units Sold, AOV, etc.)


├── data/ # Raw and cleaned datasets (CSV/Excel)
│ ├── blinkit_sales_raw.csv
│ └── blinkit_sales_cleaned.xlsx
│
├── powerbi_dashboard/ # .pbix Power BI dashboard file
│ └── Blinkit_Sales_Dashboard.pbix
│
├── visuals/ # Dashboard screenshots (for preview)
│ └── dashboard_overview.png
│
├── analysis/ # Jupyter notebooks / Excel analysis
│ └── sales_insights.ipynb
│
├── README.md


Cleaning steps:

- Removed duplicates and missing values  
- Standardized category names  
- Calculated `Revenue = Price × Quantity`  
- Added time dimensions (Month, Quarter, Year)  
- Generated lookup tables for regions and products


