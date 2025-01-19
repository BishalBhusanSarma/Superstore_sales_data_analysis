# Superstore Sales Dashboard

## Overview
This Tableau project provides a comprehensive analysis of sales performance for a Superstore, leveraging visualizations to uncover insights into key business metrics like sales, profit, quantity, and average days required for shipping. The dashboard includes various charts and KPIs to provide a clear and actionable overview of the store’s performance across multiple dimensions.

## Dataset Used
**Dataset Name**: SuperStore Sales Dataset

### Key Fields in the Dataset:
- **Order Date**: Date when the order was placed.
- **Ship Date**: Date when the order was shipped.
- **Sales**: Revenue generated from sales.
- **Profit**: Profit earned from sales.
- **Quantity**: Number of items sold.
- **Region**: Geographical region where sales occurred.
- **Segment**: Customer segment (e.g., Consumer, Corporate, Home Office).
- **Ship Mode**: Shipping method (e.g., First Class, Standard Class).
- **Category**: Product category (e.g., Furniture, Office Supplies, Technology).
- **Sub-Category**: Product sub-category (e.g., Phones, Chairs, Binders).

---

## Dashboard Features

### 1. KPIs
- **Quantity**: Total number of items sold.
- **Total Sales**: Total revenue generated from sales.
- **Profit**: Total profit earned.
- **Average Days Required**: Average time taken for orders to be shipped.

### 2. Sales by Payment Method
- A donut chart showcasing the percentage share of sales by payment methods such as Online, Cards, and COD.

### 3. Sales by Region
- A donut chart illustrating the percentage share of sales across different regions: West, Central, East, and South.

### 4. Sales by Segment
- A donut chart showing sales contribution from various customer segments: Consumer, Corporate, and Home Office.

### 5. Profit and Sales by State
- A map visualization indicating profit and sales values by state, with circle sizes representing total sales.

### 6. Sales by Ship Mode
- A horizontal bar chart showing sales distribution by different shipping modes (e.g., Standard Class, Second Class, First Class).

### 7. Sales by Category
- A horizontal bar chart comparing sales across the primary product categories: Office Supplies, Technology, and Furniture.

### 8. Sales by Sub-Category
- A horizontal bar chart detailing sales for individual product sub-categories, such as Phones, Chairs, and Binders.

### 9. Sales and Profit by Month
- Two line charts:
  - **Sales by Month**: Monthly sales trends for 2019 and 2020.
  - **Profit by Month**: Monthly profit trends for 2019 and 2020.

---

## How the Dashboard Works
- **Region Filter**: Select regions (Central, East, South, West) to filter the data across the entire dashboard.
- **Reset Button**: Resets all filters to display the full dataset.
- **Dynamic Insights**:
  - Visualizations update automatically based on selected regions or filters.
  - KPIs adjust dynamically to reflect the filtered data.

---

## Key Insights
- **Regional Performance**:
  - The West region contributes the most to sales, followed by East.
- **Customer Segment Insights**:
  - The Consumer segment accounts for nearly half of total sales.
- **Shipping Method Preference**:
  - Standard Class is the most used shipping mode.
- **Top-Selling Sub-Categories**:
  - Phones, Chairs, and Binders generate the highest sales.

---

## Tools and Skills Used
- **Tableau**: Data visualization and dashboard creation.
- **Data Analysis**: Extracting actionable insights from sales data.
- **Calculated Fields**:
  - Example: Calculating "Average Days Required" using `DATEDIFF('day', [Order Date], [Ship Date])`.
  - Filtering top-performing regions and products.
- **Formatting and Styling**:
  - Customizing colors, labels, and chart types for readability and clarity.

---

## File Structure
- **SuperStore Sales DataSet.xlsx**: Contains raw data used to build the dashboard.
- **Dashboard**: Tableau file where the visualizations and KPIs are implemented.
- **Screenshot**: Provides a preview of the dashboard.

---

## Future Improvements
- Add trendlines to visualize long-term sales and profit trends.
- Implement drill-down capabilities for deeper analysis of sub-categories and states.
- Incorporate predictive analytics to forecast sales and profits.


---

## Author
**Name**: Bishal Bhusan Sarma
**Email**: bishalbhusansarma87787@gmail.com

