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
- **Presentation:** GitHub  

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
Understanding column content and data types was essential for accurate modeling and analysis,such as :-

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

### 📐 Key Measures Such as:-
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



