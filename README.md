# 📊 Retail Sales Dashboard (Power BI)

## 📝 Project Overview
This project analyzes **retail sales transactions** using an **interactive Power BI dashboard**.  
The dataset includes **transaction details, store types, payment methods, customer segments, and promotions**,  
allowing for an in-depth analysis of **sales trends and business performance**.




## 🔗 **How to View the Dashboard**
1️⃣ Download **Retail_Sales_Dashboard.pbix** -  **https://drive.google.com/file/d/1U-U3JRlaizpf_bIjG40yt62Ie9KZhzxQ/view?usp=drive_link**
2️⃣ Open in **Power BI Desktop**  
3️⃣ Interact with filters, slicers, and drill-through features


---

## 📂 Dataset Overview
- **Dataset Name:** Retail Transactions Dataset
- **Number of Records:** [Number of rows in dataset]
- **Key Features:**
  - `Transaction_ID` - Unique transaction identifier  
  - `Date` - Date and time of transaction  
  - `Customer_Name` - Customer who made the purchase  
  - `Product` - Items purchased in the transaction  
  - `Total_Items` - Quantity of items purchased  
  - `Total_Cost` - Total cost of the transaction  
  - `Payment_Method` - Payment method used (Cash, Credit Card, Mobile Payment, etc.)  
  - `City` - City where the transaction occurred  
  - `Store_Type` - Type of store where the purchase was made  
  - `Discount_Applied` - Whether a discount was applied  
  - `Customer_Category` - Customer type (Young Adult, Professional, Homemaker, etc.)  
  - `Season` - Season during which the transaction occurred  
  - `Promotion` - Type of promotion applied (e.g., Buy One Get One, Discount on Selected Items)  

---

## 🔄 **Steps Applied**
### 1️⃣ **Data Cleaning & Preparation**
✔ Checked and removed **duplicate transactions**  
✔ Handled **missing values** in payment methods and promotions  
✔ Converted **date format** for accurate time-series analysis  
✔ Created **new calculated columns**:
   - **Profit Margin %** = `(Profit / Total Cost) * 100`
   - **Discount Impact Analysis**  
   - **Sales by Month & Year Extracted**  

---

### 2️⃣ **Key Metrics (KPIs) Tracked**
✔ **Total Sales** → `SUM(Total_Cost)`  
✔ **Total Transactions** → `COUNT(Transaction_ID)`  
✔ **Average Transaction Value (ATV)** → `Total Sales / Total Transactions`  
✔ **Top-Selling Products**  
✔ **Revenue Contribution by Store Type & City**  
✔ **Impact of Discounts on Sales**  
✔ **Customer Segmentation (Professionals, Young Adults, Homemakers, etc.)**  
✔ **Seasonal Sales Trends**  

---

### 3️⃣ **Dashboard Visualizations**
📊 **Sales Performance Overview** → Line Chart (Sales trends over time)  
📊 **Sales by Store Type** → Column Chart (Store contribution to revenue)  
📊 **Customer Segmentation** → Donut Chart (Top customer categories)  
📊 **Best-Selling Products** → Bar Chart (Most purchased products)  
📊 **Payment Method Preferences** → Treemap (Distribution of payment methods)  
📊 **Discount Impact on Sales** → Stacked Column Chart (Sales with vs. without discount)  
📊 **Sales by City** → Map Visualization (Regional sales distribution)  
📊 **Seasonal Sales Trends** → Line Chart (Sales during different seasons)

**Sneak Peak**
![image](https://github.com/user-attachments/assets/0a5c1cf4-00b6-493d-8d44-6ebe616c8047)





