# Sales Analysis Project 
## Sales Analysis Dataset Overview
This Sales Analysis Dataset consists of several interconnected tables. Dimension tables such as Date, Product, Channel, Stores, Geography, and Promotion contain descriptive information about sales. At the center is the Sales fact table, which links all these dimensions and holds key measurable figures like SalesAmount and TotalCost.

## # Steps 
        

          1) Data Understanding
          2) Columns Characteristic
          3) Business Questions
          4) Data Modelling
          5) Creating Measures [DAX]
          6) Dashboard Building
          7) Insights
          8) Recommendations

## 1) Data Understanding

 - Specify which column is dim and which is fact (Dimension tables such as Date, Product, Channel, Stores, Geography and the Sales is a fact table).

## 2) Columns Characteristic

 - Understanding The Content of Columns and Data Types, like: -
  **Products Table** =>(BrandName,ClassName,ProductName,UnitCost).
 **Sales Table** =>(Delivery_Date,SalesQuantity,TotalCost,Order_Date).
 **Stores Table** =>(Status,StoreName,StoryType,EmployeeCount).

## 3) Business Questions

I set some questions that will help me analyze the data.
Such As:-
 - What is the monthly trend of Ordered Amount vs. Delivered Amount?
 - What is the Top 5 Subcategories from Top Category by sales?
 - How many KPIs are over target?
 - What is the Actual vs Target achievement?

## 4) Data Modelling

After completing the previous steps, I built Snowflake Schema. 

**# Snowflake Schema :** is a highly normalized dimensional model where dimension tables are broken down into multiple, related sub dimension tables.
**# It Has a Critical Benefits:-**
 - Achieve High Normalization and Reduce Redundancy.
 - Highly scalable and can handle large volumes of data efficiently.
- Provides high performance for data processing and query execution.
 - Supports structured and semi-structured data formats.
 - Ensures strong data security and data protection.

**# Steps:-**
     1) I determined which table would be dim or fact based on the data.
     2) The relationships between the tables were established using foreign keys.
                                                  
![Home](https://github.com/user-attachments/assets/a9187863-d99b-4562-8c88-b041500ceb1f
)


     

## 5) Creating Measures [DAX]

The measures are designed to calculate specific metrics based on the data in the fact and dimension tables.
**Some Of Measures:-**
 - Total Cost 
فى صور هنا 
 - Total Profit
 - Avg Discount %
 - YTD Change %



## 6) Dashboard Building
I Built **3** Dynamic Interactive Dashboards

 - C-Level Executive
 - SalesTeam/Operational
 - Marketing Analysis

**1. C-Level Executive:-**
الصوؤة 

 - **A tooltip** on hover that displays this month's values for the last
   three years of the selected year.
   pic

 - **RLS** For User B: Can access specific category in TV and Video.
pic

**2. SalesTeam /Operational: -**
الصوؤة 

 - **Drill through** for Countries by sales.
الصوؤة 

**3. SalesTeam /Operational: -**
الصوؤة 
**YTD Selection:** It should display the Impressions YTD, Impressions YTD LY, and Change % comparison for the selected indicator.
الصوؤة 
**Time Range Selection:** Provide options to select Last 15 days, Last 30 days, or Last 45 days (from today)
الصوؤة 
**Manually Selected Periods [Custom]:**
الصوؤة 
  

## 7) Insights

 - **2011:** Strong performance (102% of target); stable monthly  revenue  (Apr–Nov) at 283M.
 - **The U.S** is the primary revenue driver with $4.7M in sales, followed by **China** ($1.0M) and **Canada** ($0.6M).
 - **Clicks** declined steadily from **9.39M** in **2023** to **8.03M** in **2025**—a cumulative drop of over 14%.
 - **Visual tech products** like **camcorders** ($1.34M) and **projectors** ($1.11M) lead sales.
 - **The delivered and ordered amounts** were closely aligned, indicating low cost and high operational efficiency. **December** had the **highest** order volume.
 - **83 % of store closures** were due to **relocation**, reflecting strategic shifts in store locations, while only **17% were actual shutdowns**.
 - Orders next 6 months are 2170, Orders next 1 month are 295, Orders next 15 days are 180 and Orders next 7 days are 81.
 - 

## 8) Recommendations

 - There’s an opportunity to **target new customer** segments like
   university students and content creators.
 - **Strengthen** your investment **in the U.S**. market by maintaining strong
   marketing campaigns.
 - **Camcorders** and **Projectors** are leading the market. I suggest
   **increasing marketing efforts** around them.
 - **Strengthen high-performing** markets: **The United States** and **China** are the primary growth drivers. I suggest maintaining strong marketing campaigns and continuously reviewing the customer experience to ensure long-term success.
 - **Launch seasonal offers** during key months such as **April** (Ramadan), **June** (summer), **November** (Black Friday), and **September** (back-to-school).
 - **Add creativity to offers** within the 5%–15% discount range. For example, “Buy 2 and get 15% off” or “5% off your first order” can make these promotions more appealing.
 - **Conduct a full UX audit** to assess user experience, and implement improvements in design and browsing speed.
 - Launch fresh **marketing campaigns** using **short videos** and engaging content to re-attract and activate users.
 - I suggest investing in user experience improvements, **digital advertising** **campaigns**, and **seamless payment integration**.
 - **Offering technical** and **marketing support** and reviewing distribution terms to better motivate sales.

   

## Contact

##### If you want to ask me any question or you can write a feedback, reach out via  [linkedin](https://www.linkedin.com/in/dina-abdelrahman?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  or ([dinaabdalrahman7@gmail.com](mailto:dinaabdalrahman7@gmail.com))

