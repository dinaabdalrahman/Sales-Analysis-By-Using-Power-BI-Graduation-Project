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

---

## 📁 Dataset Overview
The dataset consists of several interconnected tables:

### 🔹 Dimension Tables such as :-
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
Understanding column content and data types was essential for accurate modeling and analysis, such as :-

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


![**Snowflake schema diagram**](https://github.com/user-attachments/assets/a70b0171-0fa7-479b-9048-71b300bf875b)


---

## 5️⃣ Creating Measures (DAX)

Custom DAX measures were created to support KPI tracking and time-based analysis.

### 📐 Key Measures Such as:-
- Total Cost

 ![**Total Cost**](https://github.com/user-attachments/assets/77ab7ce3-46f3-4861-b472-e33070074440)


- Total Profit

![**Total Profit**](https://github.com/user-attachments/assets/8e3e247b-e2bd-4bc9-9bf4-c8a55810c502)

- Average Discount %

![**Average Discount %**](https://github.com/user-attachments/assets/7c3a2c5c-eef4-45b4-9d3a-4bce67102ec7)

- YTD Change %

![**YTD Change %**](https://github.com/user-attachments/assets/40e9dd84-422b-4637-a828-dc24fbf6d3d8)


---

## 6️⃣ Dashboard Building

**Three** dynamic and interactive dashboards were developed to serve different business roles.

### 📊 1. C-Level Executive Dashboard
![C-Level Executive Dashboard](https://github.com/user-attachments/assets/164b6d4e-bd59-43b7-8eed-d941d50e04da)

- High-level KPIs and performance overview  
- Tooltip showing current month values for the last three years

![ToolTip](https://github.com/user-attachments/assets/2f2be321-b333-483c-9bee-ed3ad08ec555)

- Row Level Security (RLS): User-based access to specific categories ==>
[User B: Can access specific category in TV and Video.]

![RLS for user B](https://github.com/user-attachments/assets/044dc42c-fd09-4abf-986e-c9959f4b40c8)


### 📊 2. Sales Team / Operational Dashboard
![Sales Team / Operational Dashboard](https://github.com/user-attachments/assets/715f7754-674b-4d13-8023-d0f0a17ac257)

- Country-level performance analysis  
- Drill-through functionality for detailed insights


![Drill Through](https://github.com/user-attachments/assets/a4be6c8c-9008-46ac-b882-3de079584dc4)

![drill2](https://github.com/user-attachments/assets/bc181cc7-52e0-4d3c-94bf-533c2e0e2f9b)



### 📊 3. Marketing Analysis Dashboard
![Marketing Analysis Dashboard](https://github.com/user-attachments/assets/9d6a34b5-6fff-4fa4-b839-edb342159676)

- YTD vs LY comparison with change %


![YTD ](https://github.com/user-attachments/assets/b9292155-88fc-44ab-943f-ee2633888341)

- Time range selection (Last 15 / 30 / 45 days)

![Time range selection](https://github.com/user-attachments/assets/0786f94c-9afc-4dc1-8c86-670b64f3bb9f)

- Custom date range selection


![Custom date range selection](https://github.com/user-attachments/assets/08b575c0-9f82-432f-abc4-2dbbfae2ebc7)



---

## 🧠 Skills Demonstrated

- Data Modeling (Snowflake Schema)
- DAX Measures & Time Intelligence
- KPI Tracking & Target Analysis
- Business Insights & Storytelling
- Dashboard Design for Stakeholders
- Row Level Security (RLS)

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

## 📑 Presentation & Documentation
- You can find the project presentation and detailed documentation below:

📑 [Presentation_Sales Analysis.pdf](https://drive.google.com/file/d/1trYoW8FquyHRgfM3MRDNbRa_28lAGEBh/view?usp=sharing)

📄 [Documentation_Sales Analysis.pdf](https://github.com/dinaabdalrahman/Sales-Analysis-By-Using-Power-BI-Graduation-Project/blob/main/Documentation_Sales%20Analysis.pdf)


---


## 📬 Contact
🔗 **LinkedIn:**  
https://www.linkedin.com/in/dina-abdelrahman  

📧 **Email:**  
dinaabdalrahman7@gmail.com  

---

⭐ *If you find this project valuable, feel free to star the repository.*



