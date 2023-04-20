# Sales-Analysis-by-Customer-Segment-and-Product-Category
This repository contains a Power BI dashboard showcasing sales data for a fictional superstore derived from Kaggle https://www.kaggle.com/datasets/vivek468/superstore-dataset-final. The dashboard provides insights into sales performance by customer segment, product category, and region, and includes visualizations such as charts, tables, and cards.


Dataset:

Column Header from Original Dataset:
  Order ID
  Order Date
  Ship Date
  Ship Mode
  Customer ID
  Customer Name
  Segment
  Country
  City
  State
  Postal Code
  Region
  Product ID
  Category
  Sub-Category
  Product Name
  Sales 
  Quantity
  Discount
  Profit
  
After cleaning the data,  new columns were inserted to provide additional performance indicators:
  Order Date Hierarchy
  Order to Ship Days (Order Date/Ship Date)
  Profit Margin (Profit/Sales)
  Segment Hierarchy
  Ship Date Hierarchy


Dashboard:

PBIX Location: https://github.com/Ejayvicta008/Sales-Analysis-by-Customer-Segment-and-Product-Category/blob/main/Portfolio%20Project.pbix

These Dashboard was derived from combination of descriptive and diagnostic analysis.

Overview of the dashboards:

  Sales and Profit
    This dashboard provides an overview of sales and profitability. It includes Total Sales, Total Profit, and Average Profit Margin across all product types and regions for comparative. There's also a map showing Sales and Profit by State, a section on Sales and Profit by Product Category, and a time series chart showing Sales and Profit by year to identify Sales and Profit movement per year. 
    
  Product and Shipping
    This dashboard gives a summary of product quantity and shipping. It displays Total Product Quantity, Average Product Quantity per Year, and Average Days to Deliver to showcase the order Quantity per order, Total Orders and Average Delivery Timeframe per Month. The dashboard also displays the Total Orders by Product Sub Category to identify which Product and Subproduct is often ordered. Also, there is a bar chart which displays which regions have the highest Products distributed. 
    
  Customer and Product
    Lastly, this dashboard contains correlated data visualization of Customer Segments and Products. It contains a chart which displays Total Population per Region and per States. This dashboard also shows high level view of segmentation of Customer Types based of Profit Margin and Product Category which provides an understanding of which type of customers and products have the highest and lowest profitability. This dashboard also drills down on which products has the highest and lowest profitability via Profit Margin per Product view.    
    
    
Overall, this dashboard provides a clear and straightforward view of the company's sales and profitability metrics, allowing audiences to quickly identify areas of strength and weakness through various variables.
