# Pizza Sales Dashboard

**Purpose**  
This repository contains my end-to-end Pizza Sales Dashboard project, built in Power BI and SQL, to showcase my data preparation, analysis and visualization skills in support of real-world business decision-making.

---

## Project Overview  
The interactive dashboard lets you explore and compare key pizza-sales metrics over time, by store and by product category. With this report you can:

- Track overall revenue, average order value, total pizzas sold and order counts  
- Drill into top- and bottom-performing pizzas (by revenue, quantity, order count)  
- Analyze daily and monthly sales trends  
- Compare sales distribution across categories (Classic, Supreme, Veggie, etc.) and sizes (Regular, Medium, Large)  
- Identify peak ordering days and times for staffing and inventory planning  

---

## Data Source  
- **Source:** Simulated pizza-sales dataset obtained from Kaggle  
- **Format:** CSV exports, one file per month  
- **Core fields:**  
  - `OrderDate` (YYYY-MM-DD)  
  - `OrderTime` (HH:MM)  
  - `OrderID`  
  - `PizzaName`  
  - `Category` (Classic, Supreme, Veggie, Chicken, etc.)  
  - `Size` (Regular, Medium, Large, X-Large)  
  - `Quantity`  
  - `UnitPrice`  
  - `StoreID`  

---

## Tech Stack  
- **Data storage & preparation**  
  - Raw CSV files in `data/raw/`  
  - `.gitignore` excludes intermediate and backup files  
- **Analysis & KPI calculation**  
  - SQL Server queries and results stored in `sql/queries.docx`  
- **Visualization**  
  - Power BI Desktop (`.pbix`) in `powerbi/`  
  - PDF/PNG export snapshots in `powerbi/exports/`  

---
## Key Features

- **Executive Metrics**  
  - Total revenue, average order value, total pizzas sold, total orders and average pizzas per order  
- **Top & Bottom Performers**  
  - Bar charts highlighting the top 5 and bottom 5 pizzas by revenue, quantity and order count  
- **Trend Analysis**  
  - Daily and monthly sales trend charts to reveal peak days and seasonal patterns  
- **Category & Size Breakdown**  
  - Donut charts showing percentage contribution by pizza category and by size  
- **Operational Insights**  
  - Callouts for busiest days of the week and time-of-day patterns for staffing recommendations  

## Contact & Next Steps  
I am actively seeking a co-op training opportunity where I can apply these analytical and visualization techniques to support data-driven decisions.  

- **Email:** abdulrahman.h.alzubaidi@gmial.com
- **LinkedIn:** www.linkedin.com/in/abdulrahman-hassan-5a1b99343

