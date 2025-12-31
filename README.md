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

**# Snowflake Schema :** is a highly normalized dimensional model where dimension tables are 
broken down into multiple, related sub dimension tables.

**# It Has a Critical Benefits:-**
 - Achieve High Normalization and Reduce Redundancy.
 - Highly scalable and can handle large volumes of data efficiently.
 - Provides high performance for data processing and query execution.
 - Supports structured and semi-structured data formats.
 - Ensures strong data security and data protection.

**# Steps:-**

 1) I determined which table would be dim or fact based on the data.
 2) The relationships between the tables were established using foreign keys.
                                                   هنا فى صورة 
     
     



## 5) Creating Measures [DAX]

The measures are designed to calculate specific metrics based on the data in the fact and dimension tables.

**# Some Of Measures:-**
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

- **YTD Selection:** It should display the Impressions YTD, Impressions YTD LY, and Change % comparison for the selected indicator.
الصوؤة 

- **Time Range Selection:** Provide options to select Last 15 days, Last 30 days, or Last 45 days (from today)
الصوؤة 

- **Manually Selected Periods [Custom]:**
الصوؤة 
  

## 7) Insights

 - **2011:** Strong performance (102% of target); stable monthly  revenue  (Apr–Nov) at 283M.
 - **The U.S** is the primary revenue driver with $4.7M in sales, followed by **China** ($1.0M) and **Canada** ($0.6M).
 - **Clicks** declined steadily from **9.39M** in **2023** to **8.03M** in **2025**—a cumulative drop of over 14%.
 - **Visual tech products** like **camcorders** ($1.34M) and **projectors** ($1.11M) lead sales.
 - **The delivered and ordered amounts** were closely aligned, indicating low cost and high operational efficiency.
   **December** had the **highest** order volume.
 - **83 % of store closures** were due to **relocation**, reflecting strategic shifts in store locations, while only **17% were actual shutdowns**.
 - Orders next 6 months are 2170, Orders next 1 month are 295, Orders next 15 days are 180 and Orders next 7 days are 81.
 
 

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

   
## Presentation

[Presentation](file:///C:/Users/Zero/Downloads/Documentation_Sales%20Analysis.pdf)

## Documentation

[Documentation](file:///C:/Users/Zero/Downloads/Documentation_Sales%20Analysis.pdf)


## Contact

##### If you want to ask me any question or you can write a feedback, reach out via  [linkedin](https://www.linkedin.com/in/dina-abdelrahman?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  or ([dinaabdalrahman7@gmail.com](mailto:dinaabdalrahman7@gmail.com))























# 📊 Sales Analysis Project

## 🧠 Overview
This project delivers a complete **end-to-end sales analytics solution** designed to support executive decision-making, operational monitoring, and marketing performance analysis.  
It covers the full analytics lifecycle — from data understanding and modeling to advanced DAX measures, interactive dashboards, insights, and strategic recommendations.

---

## 🎯 Project Objectives
- Analyze sales performance across time, geography, products, and channels  
- Track KPIs against targets and identify performance gaps  
- Support different stakeholders (Executives, Sales, Marketing) with tailored dashboards  
- Provide data-driven insights and actionable business recommendations  

---

## 🛠 Tools & Technologies
- **Data Visualization:** Power BI  
- **Data Modeling:** Snowflake Schema  
- **Analytics:** DAX (Time Intelligence, KPIs, Targets)  
- **Documentation:** GitHub, Markdown  
- **Supporting Tools:** Excel  

---

## 📁 Dataset Overview
The dataset consists of several interconnected tables:

### 🔹 Dimension Tables
- Date  
- Product  
- Channel  
- Stores  
- Geography  
- Promotion  

### 🔹 Fact Table
- **Sales**  
  - Holds measurable metrics such as Sales Amount, Total Cost, and Quantity  
  - Acts as the central table connecting all dimensions  

---

## 🔍 Project Workflow

1️⃣ Data Understanding  
2️⃣ Columns Characteristics  
3️⃣ Business Questions  
4️⃣ Data Modeling  
5️⃣ Creating Measures (DAX)  
6️⃣ Dashboard Building  
7️⃣ Insights  
8️⃣ Recommendations  

---

## 1️⃣ Data Understanding
- Identified dimension and fact tables  
- Defined relationships between tables  
- Ensured business logic consistency across the dataset  

---

## 2️⃣ Columns Characteristics
Understanding column content and data types was essential for accurate modeling and analysis.

### 📦 Products Table
- BrandName  
- ClassName  
- ProductName  
- UnitCost  

### 🧾 Sales Table
- Delivery_Date  
- SalesQuantity  
- TotalCost  
- Order_Date  

### 🏬 Stores Table
- Status  
- StoreName  
- StoryType  
- EmployeeCount  

---

## 3️⃣ Business Questions
The analysis focuses on answering key business questions such as:

- What is the monthly trend of Ordered Amount vs Delivered Amount?  
- What are the Top 5 Subcategories within the Top Category by sales?  
- How many KPIs are over target?  
- What is the Actual vs Target achievement across time?  

---

## 4️⃣ Data Modeling

### ❄️ Snowflake Schema
A **Snowflake Schema** was implemented to ensure scalability, performance, and data integrity.

#### Key Benefits:
- High normalization and reduced redundancy  
- Efficient handling of large datasets  
- Improved query performance  
- Strong data governance and security  

#### Modeling Steps:
1. Classified tables as dimension or fact  
2. Defined relationships using foreign keys  
3. Validated model performance and filter flow  

📌 *Snowflake schema diagram included in the repository*

---

## 5️⃣ Creating Measures (DAX)

Custom DAX measures were created to support KPI tracking and time-based analysis.

### 📐 Key Measures:
- Total Cost  
- Total Profit  
- Average Discount %  
- YTD Change %  

> Measures follow Power BI best practices and leverage fact–dimension relationships.

---

## 6️⃣ Dashboard Building

Three dynamic and interactive dashboards were developed to serve different business roles.

### 📊 1. C-Level Executive Dashboard
- High-level KPIs and performance overview  
- Tooltip showing current month values for the last three years  
- Row Level Security (RLS): User-based access to specific categories  

### 📊 2. Sales Team / Operational Dashboard
- Country-level performance analysis  
- Drill-through functionality for detailed insights  

### 📊 3. Marketing Analysis Dashboard
- YTD vs LY comparison with change %  
- Time range selection (Last 15 / 30 / 45 days)  
- Custom date range selection  

📷 *Dashboard screenshots are available in the assets folder*

---

## 7️⃣ Key Insights

- **2011** achieved strong performance at **102% of target**, with stable monthly revenue from April to November  
- **United States** is the primary revenue driver ($4.7M), followed by **China** ($1.0M) and **Canada** ($0.6M)  
- **Clicks** declined from **9.39M (2023)** to **8.03M (2025)**, a drop of over **14%**  
- **Camcorders** ($1.34M) and **Projectors** ($1.11M) lead product sales  
- Ordered and delivered amounts are closely aligned, indicating high operational efficiency  
- **December** recorded the highest order volume  
- **83%** of store closures were due to relocation rather than shutdown  
- Forecasted orders show stable demand across upcoming periods  

---

## 8️⃣ Recommendations

- Target new customer segments such as university students and content creators  
- Strengthen marketing investment in the U.S. market  
- Increase promotional focus on high-performing products (Camcorders & Projectors)  
- Maintain strong presence in key growth markets (U.S. and China)  
- Launch seasonal campaigns during April, June, September, and November  
- Introduce creative discount strategies within the 5%–15% range  
- Conduct a full UX audit to improve customer experience  
- Invest in short-video digital marketing campaigns  
- Enhance digital advertising and payment integration  
- Provide technical and marketing support to motivate sales channels  

---

## 📂 Repository Structure



