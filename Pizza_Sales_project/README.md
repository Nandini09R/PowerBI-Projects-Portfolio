🍕 **Pizza Sales Analysis — Power BI Project**

An end-to-end BI project analyzing pizza restaurant sales to uncover customer behavior, peak sales periods, and product performance using Power BI, DAX, and a star-schema model.

📁 **Project Files**

Pizza_Sales_Report.pbix — Interactive Power BI report

Pizza_Sales_Report.pdf — Exported report

Data Model Screenshot

Pizza_Sales_Dataset.xlsx — Raw dataset (Kaggle)

⭐ **Key Business Questions**

Which days and time slots are the busiest?

How many pizzas are made during peak periods?

Which pizzas sell the most and least?

What is the average order value (AOV)?

📊 **Report Visuals**

**Card Visuals**

Total Revenue

Total Orders Placed

Average Order Value

Best-Selling Pizza

Worst-Selling Pizza

Peak Time Slot

**Other Visuals**

**Funnel Chart:** Average Orders by Weekday

**Donut Charts:** Revenue by Category, Revenue by Size, Orders by Size

**Slicers:** Pizza Category, Time Slot (Breakfast/Lunch/Dinner), Order Date

🏗️ **Data Model (Star Schema)**
**Fact Table**

order_details_id, order_id, pizza_id

quantity, unit_price, total_price

order date, time index

**Dimension Tables**

**Dim_Pizza**
pizza_id, pizza_name, pizza_category, pizza_size, ingredients

**Dim_Date**
date, day, month, month name, quarter, weekday, weekend flag, year

**Dim_Time**
time, hour, minute, time slot, AM/PM, 24-hour format

📈 **Key DAX Measures**

Total Revenue

Total Pizzas Sold

Total Orders

Average Order Value (AOV)

Sales by Weekday

Sales by Hour

Best & Worst Selling Pizza

🧠 **Insights Generated**

Peak periods: Friday dinner, Thursday lunch, Wednesday breakfast

Best-selling pizza: Classic Deluxe Pizza

Worst-selling pizza: Brie Carre Pizza

Most popular size: L

Least popular size: XXL

Classic pizzas outperform Veggie and Chicken categories

Dinner hours generate higher revenue due to larger orders

AOV is highest on Fridays, showing premium end-of-week spending

Demand patterns align with office worker and family meal times

🛠️ **Tools Used**

Power BI Desktop — data modeling & visualization

Power Query — data cleaning & transformation

DAX — custom measures

GitHub — portfolio documentation

Kaggle — dataset source

