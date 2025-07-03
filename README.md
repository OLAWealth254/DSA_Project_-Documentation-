# DSA_Project_Documentation
This is where I started my portfolio building while taking my  Data Analysis class with Incubator Hub

 I have learnt quite a number of things ranging from Microsoft Excel, SQL, to Power BI and now to My Portfolio Building

 ## Project Overview 
  This Data Analysis Project aim to analyze business insight questions in order to generate insights that guide sales in terms of product category, Region, how to increase revenue.To check if shipping mode & shipping cost is based on order priority and how does it the business .We seek to gather enough insight to make reasonable decisions,which enable us to tell compelling stories around our data from the insight gotten and to know the best performance from our data.

  ## Data Sources 
   The primary source of data used here is KMS sql Case Study.csv & Order_status.csv, this is an open source data that can be freely downloaded from an online open source such as Kaggle, FRED or any other data repository site.

### Project Topic: KMS Business_ Insights( SQL)
This repository contains SQL queries used to analyze the sales data of KMS Mega Stores from 2009 to 2012.

### Case Study( datasets)
* KMS sql Case Study(KMS_Order)
* Order_Status

### Structure 
* SQL/Case_Scenario_1.sql, give answers to business sales and shipping cost questions using SQL.
* SQL/Case_Scenario_2.sql, contains customers analysis, profit insights and shipping mode.


  ### Tools Used
* Microsoft SQL Server
* SQL (T- SQL Syntax)

  ### Columns in Dataset
Row_Id, Order_Id, Order_Date,Order_Quantity,Order_Priority,Sales, Profit, Product_Category, Region, Status e.t.c

### Instructions 
* Clean your dataset(KMS sql Case Study) in Microsoft Excel.
* Save your cleaned data into document/Sql server.
* Create a database in your SQL
* Load your datasets into the created database using task/ import flat file.
* Edit the data( especially KMS sql Case Study,cause the data type size)
* Click finish
  Note: Microsoft SQL will automatically create the table and columns for you.
* Run the SQL

### Business Insights Questions 
The following are the business insights questions asked 


#### Highest Sales by Product Category:
The product_category with the highest sales was (Technology), generating a total sales of (5,984,248) in revenue.
  

#### Regional Sales Ranking:
  * Top 3 Sales per Region : Are West, Ontario,Prane with their respectively total sales of (3,597,549),(3,063,212) & (2,837,305).

  * Bottom 3 Sales per Region: Are Nunavut, Northwest Territories, Yukon with their respective total sales of (116,376), (800,847), (975,867).
     

####  Total Appliance Sales in Ontario: 
The total sales of appliances in Ontario amounted to 202,346.8


#### How To Increase Revenue From Bottom 10 Customers:
   The following strategies can be used :
  * Customer Feedback: The Management are advise to conduct survey to understand their needs or dissatisfaction.
  * Customer Engagement: Management are advise to initiate loyalty program or offer discounts to the bottom 10 customers.
  * Product Bundles: Management are advise to create attractive product/service bundles to encourage large purchases.


#### Most Shipping Cost Method: 
The highest shipping cost was incurred using, Ship_Mode and Total_Shipping_Cost respectively,( Delivery truck 51,972 ), (Regular Air 48,008 ), ( Express Air 7,851 )
   

#### Most Valuable Customers and their Purchase: 
The most valuable customers based on total revenue generated were:
 (Emily Phan, technology, 110,482)
(Deborah Brumfield,  technology,76,796) e t.c
According to their customer_name, product_category and category_sales.

#### Top Small Business Customer: 
The small business customer with the highest sale was 'Dennis Kane' with total purchase amounting to 75,968.


#### Corporate Customers with Most Orders (2009-2012):
   Between 2009 and 2012, 'Adam Hart' placed the most number of orders, totally 18 orders.


#### Most Profitable Consumer Customer: 
The most profitable consumer customer was 'Emily Phan' with a profit to contribution of 34,005.


#### Customer Returns and Segments :
419 customers returned item into various customer_segments.


#### Shipping Cost Evaluation Based on Order Priority:
##### Summary 
* Delivery Truck incurs the highest shipping cost across all order priorities.
* Express Air, while is the fastest,has the lowest shipping cost,but is underused for critical orders.
* Critical Orders heavily use delivery truck,which is expensive and slow.

##### Conclusion 
* Shipping cost were not optimally spent, relative to order priority.
* Critical orders should prioritize Express Air to improve delivery speed.
* Delivery truck should be reserved for lower priority orders to save costs.
* Management should negotiate costs and implement a priority-based shipping policy.


##### Recommendation 
* Increase Express Air usuage for critical/ high priority orders.
* Optimize Delivery Truck usuage and negotiate better shipping rates.
* Monitor Shipping costs and adjust allocation as needed.

  
