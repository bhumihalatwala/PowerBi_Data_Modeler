# 🌟 Power BI – Star Schema Project

## 📌 Project Overview
This project showcases a **Power BI Data Model** built using the **Star Schema** approach.  
It focuses on efficient reporting and analysis by connecting a **Fact Table (Sales)** with supporting **Dimension Tables**.

### ✨ Key Features
- Fact Table: **Sales**
- Dimension Tables: **Products**, **Customers**, **Regions**, **Dates**
- Reporting Examples:
  - Revenue by Customer Segment
  - Sales by Product Category and Region
  - Returns by Fiscal Year

---

## 🌟 Schema Type: Star Schema
- **Fact table** in the center (Sales).  
- **Dimension tables** directly connected.  
- No intermediate joins → clean & fast reporting.

✅ **Why Star Schema?**
- Simplified model design  
- Easy filter flow from dimensions → fact table  
- Faster queries, optimized for dashboards  

---

## 🔗 Relationships & Filter Flow
- **One-to-Many (1:*)** relationship from dimensions → fact table  
- Filters flow downwards from **Product / Region / Date** → **Sales**  

---

## ⚠️ Issues Faced
- **Problem:** Different file locations on different systems caused query errors.  
- **Fix:** Used **Manage Parameters** → **File Path Parameter** to make the dataset location dynamic.  
  - Now, users only need to update the parameter to point to their local dataset folder.

---

## 📷 Model View 
<img width="1653" height="849" alt="image" src="https://github.com/user-attachments/assets/edc611c3-97a0-4b3a-8c50-6c55c7627913" />

