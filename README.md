## 🛍️ Retail Business Performance & Profitability Analysis 

# 🎯 Objective

This project analyzes transactional retail data to:
-Identify profit-draining categories and sub-categories
-Optimize inventory turnover
-Uncover seasonal product behavior
-Deliver actionable insights for improving profitability

# 📦 Dataset Overview
The dataset used for this project contains 9,994 retail transactions from a multi-category retail business, covering 5 years (2014–2018) across 4 regions (West, East, Central, South).

✅ Main Features:

Column Name  -  	Description

*Order ID	   -   Unique order identifier
*Order Date	 -   Date when the order was placed
*Ship Date	  -   Date when the order was shipped
*Ship Mode	  -   Shipping method used
*Region	     -   Geographical region (West, East, Central, South)
*Category	   -   Product category (Furniture, Office Supplies, Technology)
*Sub-Category - 	Product sub-category (e.g., Chairs, Phones, Binders)
*Product Name	 -  Name of the product sold
*Quantity	   -   Quantity of units sold
*Sales	       -   Sales amount (₹)
*Profit	      -  Profit earned (₹)
*Profit Margin	-  Profit margin percentage
*Delivery Time	-  Delivery time in days
*Season	       - Season of sale (Winter, Spring, Summer, Fall)

📊 Dataset Summary:
*Total Transactions: 9,994
*Total Sales: ₹2.3 Million
*Total Profit: ₹286,400
*Categories: Technology, Furniture, Office Supplies
*Regions Covered: West, East, Central, South
*Time Span: 2014 to 2018

✅ The dataset enables exploration of profitability, inventory turnover, delivery performance, and seasonal trends across product categories and regions.

# 🧰 Tools Used
-SQL → Data cleaning & profitability calculations
-Python (Pandas, Seaborn) → Correlation analysis
-Power BI → Interactive dashboard & visualization storytelling

# 📊 Dashboard Highlights
Summary.jpeg
 ✅ Sales Overview
-Total Sales: ₹2.30M
-Total Profit: ₹286.4K
-Average Profit Margin: 12%
-Top-Selling Category: Technology (36.4% of sales)
-Highest Region Sales: West Region (₹725K)

 ✅ Profitability Analysis
Profit.jpeg
 Profit-Draining Sub-Categories:

-Tables → Loss -₹17.7K (Profit Margin -47%)
-Bookcases → Loss -₹3.47K (Profit Margin -29%)
-Appliances → Loss -₹18.1K (Profit Margin -73%)
-Binders → Low Margin -₹30.2K (Profit Margin -304%)

 Top Profitable Sub-Categories:

-Accessories → Profit ₹41.9K (Profit Margin +169%)
-Paper → Profit ₹34K (Profit Margin +583%)
-Phones → Profit ₹44.5K (Profit Margin +106%)

 ✅ Inventory Turnover Insights
Inventory.jpeg
-Average Delivery Time: 3.96 days
-Strong negative correlation between delivery time and profit → longer delivery time reduces profitability
-Slow-moving items include Tables, Bookcases, Appliances

 ✅ Seasonal Product Behavior
Seasonal.jpeg
-Highest Sales Season: Fall (₹800K)
-Top Profitable Season: Summer → driven by Phones & Accessories
-Lowest Profit Season: Winter → driven by Furniture & Office Supplies losses

# 📝 Key Insights & Recommendations

✅ Discontinue/discount underperforming products: Tables, Bookcases, Appliances (all negative profit margins)
✅ Focus on high-profit sub-categories: Accessories, Paper, Phones → prioritize inventory & marketing
✅ Optimize delivery operations: faster shipping improves profitability
✅ Align stock levels with seasonal demand: ramp up stock for Fall, reduce Furniture stock for Winter

# 🖥️ Power BI Dashboard Pages

-Sales Overview → Key KPIs, sales by region, month, category
-Profitability Analysis → Category & sub-category margins
-Inventory & Delivery Dashboard → Delivery time vs profit analysis
-Seasonal Insights → Sales & profit by season

## 📂 Subprojects

### 🔮 Sales Forecasting using Linear Regression
📂 [Explore this subproject ➝](./Linear_Regression_Sales_Forecasting/README.md)
- Built a forecasting model for future daily sales
- Used Python, Pandas, Plotly, and Scikit-learn
- Includes prediction graphs and insights

# 📂 Repository Structure

├──Superstore Dataset.xlsx                                   #Dataset used foe the analysis
├──Retail profit and performance analysis project.pbit	      #Power BI dashboard template file
├──SQL+Python.pynb	                                          #SQL and Python scripts for cleaning & aggregation
├── Retail Busniess Performance Insights Report.pdf	          #PDF report summarizing findings 

# 📝 Summary
This project demonstrates my ability to turn raw data into actionable insights that drive profitability improvements in retail operations. I built this solution to empower decision-makers to:
✅ Focus on profitable products
✅ Eliminate loss-making items
✅ Optimize seasonal inventory
✅ Improve delivery efficiency

# 📞 Let's connect
📧 Email ID : sirishadsirishad6@gmail.com
💼 LinkedIn : https://www.linkedin.com/in/sirisha-d-064b69278/


