# 📱Mobiles-Sales-Dashboard
📌 Project Overview

This project is an interactive Mobile Sales Dashboard developed using Microsoft Power BI. The dashboard provides insights into mobile phone sales performance, customer ratings, transaction trends, payment methods, brand-wise sales, and geographical distribution of sales.

The dashboard helps business users analyze sales data and make data-driven decisions through interactive visualizations and KPIs.

---

- 🎯 Objectives
  
•Analyze total mobile sales and quantity sold.<br>
•Track transaction performance.<br>
•Compare sales across different mobile brands.<br>
•Monitor customer ratings.<br>
•Identify popular payment methods.<br>
•Analyze sales trends by month and day.<br>
•Visualize sales distribution across cities.<br>

---

🛠 Tools & Technologies Used

•Microsoft Power BI<br>
•Power Query Editor<br>
•DAX (Data Analysis Expressions)<br>
•Data Modeling<br>
•Interactive Visualizations<br>

---

- 📊 Dashboard Features
  
•KPI Cards<br>
•Total Sales<br>
•Total Quantity Sold<br>
•Total Transactions<br>
•Average Sales Value<br>
•Visualizations<br>
•Customer Ratings Analysis<br>
•Total Sales by Mobile Model<br>
•Transactions by Payment Method (Pie Chart)<br>
•Total Sales by Day Name (Line Chart)<br>
•Total Sales by City (Map Visual)<br>
•Total Quantity by Month and Day<br>
•Brand-wise Sales and Quantity Table<br>
•Interactive Filters<br>
•Brand Filter<br>
•Month Filter<br>
•Mobile Brand Logo Selection<br>


<h2>Total Transactions</h2>
<br>
Transactions = COUNTROWS(Sales_Data)
<h2>Total Sales</h2>
<br>
Total Sales = SUMX(Sales_Data,Sales_Data[Units Sold]*Sales_Data[Price Per Unit])




- 🔄 Data Transformation Using Power Query<br>

The following transformations were performed:<br>
•Data Cleaning<br>
•Removed duplicate records<br>
•Handled missing/null values<br>
•Corrected data types<br>
•Renamed columns for readability<br>
•Date Transformations<br>
•Extracted Month Name<br>
•Extracted Day Name<br>
•Created Date Hierarchy<br>
•Data Preparation<br>
•Standardized brand names<br>
•Formatted sales values<br>
•Created calculated columns for analysis<br>
•Data Modeling<br>
•Established relationships between tables<br>
•Optimized data model for performance<br>

---

🎨 Dashboard Design & Styling<br>
•Theme<br>
•Clean and modern business dashboard<br>
•Light background with purple accents<br>
•Rounded corners for visual appeal<br>
•Design Elements<br>
•Custom KPI Cards<br>
•Mobile Brand Logos<br>
•Interactive Slicers<br>
•Consistent Typography<br>
•Professional Layout Structure<br>
•User Experience<br>
•Easy navigation<br>
•Interactive filtering<br>
•Responsive visual arrangement<br>
•Business-focused KPIs<br>

---

## Dashboard Preview<br>
![Mobile Sales Dashboard](dashboard_image.png)


