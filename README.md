# Business-Insights-360

**PROJECT OVERVIEW:**

AltiQ Hardware, a fast-growing company expanding globally, specializes in selling computers and accessories through three main channels: retailers, direct sales, and distributors.

Despite its growth, the company faced unexpected losses after opening a store in America. These setbacks were identified through surveys, intuition, and basic Excel analysis. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities to thrive in the industry.

To surpass competitors and enable data-driven decision-making, the company has decided to implement Power BI for analytics. This project aims to provide stakeholders with insights into finance, sales, marketing, and supply chain, ensuring informed decisions at all levels.

----------------------------------------------------------------------------------------------

**DATASETS:**

**gdb041**:

•	dim_customer      
•	dim_market    
•	dim_product     
•	fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes   
•	fact_sales_monthly—This table is similar to the fact_forecast_monthly table, but the last column has the sold quantity instead of the forecast value.

**gdb056:**

•	freight_cost   
•	gross_price   
•	manufacturing_cost   
•	Pre_invoice_dedutions   
•	Post_invoice_deductions

----------------------------------------------------------------------------------------------

**IMPORTING DATA AND DATA MODELING:**

Data was imported from MySQL into Power BI, and a data model was created after cleaning and transforming the data.

✅ Data Extract ---> ✅ Data Cleaning---> ✅ Data Modelling ---> ✅ Data Analysis

In this project, we have followed the Snowflake schema data modeling method.

![Data Model](https://github.com/user-attachments/assets/60824abd-32c4-436e-b9f2-81aa13e956c1)

----------------------------------------------------------------------------------------------


**POWER BI DASHBOARD OVERVIEW:**

**Home Page**:  _A landing page with buttons to navigate to different pages._

![HomePage](https://github.com/user-attachments/assets/4849ea31-d3ae-4ace-99c8-bf30b874aee6)

----------------------------------------------------------------------------------------------

**Finance Page**: _Focuses on improving financial planning, budgeting processes, and cost control. Includes Profit and Loss statements, Top and Bottom Products and Customers by Net Sales, and more._

![Finance page](https://github.com/user-attachments/assets/1302447a-cea4-4df7-b389-92084fa1ce25)

----------------------------------------------------------------------------------------------

**Sales Page:** _Aims to increase sales revenue and market share. Features Customer performance by Net Sales, Gross Margin, Gross Margin %, and more._

![Sales Page](https://github.com/user-attachments/assets/41ddf51d-c558-43fe-a985-e0e9278a25fd)

----------------------------------------------------------------------------------------------

**Marketing Page:** _Aims to increase brand visibility and customer engagement. Provides Segment Performance by Gross Margin% and Net Profit%, and more._

![Marketing Page](https://github.com/user-attachments/assets/2e815b77-bed8-41d9-af5f-07ebb87032d0)

----------------------------------------------------------------------------------------------

**Supply Chain Page:** _Aims to optimize inventory management and enhance supplier relationships for cost savings. Includes details about Forecast Accuracy, Net error, and more._

![Supply Chain Page](https://github.com/user-attachments/assets/7a5d2f74-d891-4bb7-960f-60cb6cba2d7c)

----------------------------------------------------------------------------------------------

**Executive Page:** _Provides an overview of the organization's performance for top management. Includes Net Sales, Gross Margin%, Net Profit%, Revenue Contribution by channel, Top 5 Customer and Product, Sub Region performance, and more.


![Executive Page](https://github.com/user-attachments/assets/a757377d-c43b-4238-9af9-0008ef10e0a2)

----------------------------------------------------------------------------------------------

**SKILLS LEARNED:**

Power BI fundamentals, Calculated columns and DAX measures, Data Modeling, Data Cleaning, Bookmarks, Conditional formatting, Custom Tooltip usage, Dynamic Title Creation, and more.

**TOOLS USED:**

SQL, Power BI Desktop, DAX language, DAX studio (to reduce file size), Project Charter file.

**BUSINESS TERMS LEARNED:**

Gross Margin, Gross Margin %, Gross Sales, Gross Sales %, Pre-invoice deductions, Post-invoice deductions, Net sales, Net Invoice Sales, Net Profit, Net Profit %, COGS (cost of goods sold), YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.

**CONCLUSION:**

This report empowers decision-making based on data, addressing numerous "why" questions across various scenarios. It serves as a tool to extract insights and guide actions, ultimately aiming to enhance AltiQ's profitability through data-driven decisions.

----------------------------------------------------------------------------------------------











