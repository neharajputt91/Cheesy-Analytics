# Cheesy-Analytics
"Analysis of pizza sales data from 2015, including KPIs, trends, and insights."

## Project Overview
This repository contains the dataset and analysis of pizza sales from a pizzeria in 2015. The data includes detailed transaction logs, KPIs, trends, and breakdowns by category/size. The goal is to provide insights into sales performance, popular items, and operational trends.

### Dataset
- **File**: [pizza sales excel file.xlsx](pizza%20sales%20excel%20file.xlsx)
- **Source**: Provided as an Excel file with 6 sheets (KPI, Trends, Category, Best/Worst Sellers, Pizza Sales, Dashboard).
- **Key Stats**:
  - Total Revenue: $817,860
  - Total Orders: 21,350
  - Total Pizzas Sold: 49,574
  - Average Order Value: $38.31
  - Average Pizzas per Order: 2.32

### Analysis Summary
#### KPIs
- Revenue and volume metrics highlight a healthy business with room for optimization.

#### Trends
- **Daily**: Saturday dominates (14,032 orders), weekdays even (~1,200 each).
- **Hourly**: Peaks at 12-13 and 17-18 hours.

#### Categories
- Classic leads (27% revenue, 14,888 units).
- Large size drives 46% revenue.

#### Best/Worst Sellers
- **Top**: Classic Deluxe (2,453), BBQ Chicken (2,432), etc.
- **Bottom**: Brie Carre (490), Mediterranean (934), etc.

For full details, see the analysis in the [main document](#) or run the provided code.

### How to Use
1. Download the Excel file.
2. Open in Excel/Google Sheets for exploration.
3. For advanced analysis, use Python (e.g., pandas):
   ```python
   import pandas as pd
   df = pd.read_excel('pizza sales excel file.xlsx', sheet_name='pizza_sales')
   print(df.describe())  # Summary stats
