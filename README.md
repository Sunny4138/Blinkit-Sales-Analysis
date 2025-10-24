# 🛒 Blinkit  Sales Analysis 

<img width="1449" height="813" alt="image" src="https://github.com/user-attachments/assets/bcde6719-8e1c-455b-af61-c9a78ecc3501" />






### (1). **Problem Statement**
   • This dashboard delivers in-depth analysis of Blinkit’s sales performance, customer satisfaction, and inventory distribution across outlets and item categories.  
   • Business users and data analysts can quickly identify high-performing products, trends in customer ratings, and opportunities for optimization.  
   • The solution helps guide strategic decisions in sales, procurement, and inventory management to maximize growth and efficiency.

### (2). **Steps Followed**

(1).  Loaded BlinkIT Grocery Data Excel file into Power BI Desktop.  

(2). Cleansed and validated data using Power Query (checked for missing 
values, inconsistent entries, and column distribution).  

(3). Explored key fields including outlet type, outlet size, item types, fat content, total sales, ratings, and locations. 

(4). Created calculated columns and measures for KPIs: Total Sales, Average Sales, Number of Items, Average Rating. 

(5). Built visuals—donut charts, bar charts, KPIs, and line graphs—to highlight top metrics like item sales by fat content, item type performance, and outlet establishment trends.  

(6). Developed filter panel for interactivity (filtering by outlet type, item type, outlet size, and location). 

(7). Added cards to display headline metrics: total sales, average sales, number of items, and average rating.  

(8). Used advanced Power BI visuals to display distribution and visibility of items by outlet and item category.  

(9). Used segmentation to analyze performance by outlet tier (Tier 1, 2, 3) and size (Medium, Small, High).  

(10). Final dashboard published for sharing and business presentations.

## (4). **Key Insights**
   • **Total Sales:** $1.20M with 8,523 unique items.  
   • **Top Performers:** Highest sales from regular fat content products and popular item types, especially fruits, snacks, and household products.  
   • **Ratings:** Average customer rating ~3.9, indicating moderate satisfaction and areas for improvement.  
   • **Outlet Trends:** Tier 3 outlets and ‘High’ outlet size contributed most to total sales.  
   • **Geographic Distribution:** Outlet sales vary across locations and establishment years, with notable peaks in some years/regions.  
   • **Visibility:** Item visibility scores show which product-outlet combinations need better stock or promotion.  
   • **Actionable Finding:** Outlets with regular fat products and strategic item assortments generate higher sales; focusing promotions and inventory here can boost revenue.

## (5). **Dataset Details**
   • **Source:** BlinkIT Grocery Data (Excel)  
   • **Columns:** Outlet ID, Location, Type, Size, Establishment Year, Item Type, Fat Content, Total Sales, Number of Items, Ratings, etc.  
   • **Period:** Data captures multiple years and geographies of Blinkit retail operations.

## (6). **Example KPI Calculation – Total Sales**
   
   SELECT SUM(total_sales) AS TotalSales
   FROM blinkit_grocery_data;


 ## (7). Conclusion
 
(1). The Blinkit Analysis Dashboard delivers a comprehensive, data-driven overview of sales, customer satisfaction, and inventory performance.

(2). It transforms raw transactional data into meaningful business insights, enabling organizations to monitor KPIs, identify trends, and make informed decisions.

#### (3).Through this project, businesses can:
 • Optimize marketing and promotions based on seasonal and         category-wise demand.

• Identify top-performing products and address underperforming items.

• Enhance inventory management using insights from sales patterns.

• Boost profitability and efficiency through continuous performance monitoring.

(4). In summary, this dashboard acts as a powerful business intelligence tool, empowering stakeholders to make strategic, data-backed decisions and drive sustainable business growth.
