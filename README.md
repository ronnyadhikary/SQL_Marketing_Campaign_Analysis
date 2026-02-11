# 📊 Marketing Campaign Analysis Using SQL

## 📌 Project Overview

This project analyzes marketing campaign performance using SQL.  
The raw marketing dataset was structured into relational tables and analyzed to identify customer behavior, spending patterns, and campaign effectiveness.

---

## 🗂 Database Structure

The original dataset was separated into three logical tables for better relational analysis:

### 1️⃣ Customers  
Contains demographic information:
- customer_id  
- Year_Birth  
- Education  
- Marital_status  
- Income  
- Kidhome  
- Teenhome  
- Dt_Customer  
- Country  

### 2️⃣ Purchase  
Contains spending behavior:
- MntWines  
- MntFruits  
- MntMeatProducts  
- MntFishProducts  
- MntSweetProducts  
- MntGoldProducts  
- NumDealsPurchases  
- NumWebPurchases  
- NumCatalogPurchases  
- NumStorePurchases  
- NumWebVisitsMonth  

### 3️⃣ Campaigns  
Contains marketing response data:
- AcceptedCmp1  
- AcceptedCmp2  
- AcceptedCmp3  
- AcceptedCmp4  
- AcceptedCmp5  
- Response  
- Complain  

---

## 🛠 SQL Concepts Used

- CREATE TABLE using SELECT  
- INNER JOIN  
- GROUP BY  
- SUM() aggregation  
- UNION  
- ORDER BY  
- LIMIT  

---

## 📊 Business Questions Answered

- Which campaign performed the best?
- Which birth year segment responded the most?
- Does higher spending correlate with campaign acceptance?
- Which education level shows the highest engagement?
- Which country shows the strongest campaign response?

---

## 📈 Key Insights

- One campaign outperformed others in total acceptances.
- Certain education segments showed stronger engagement.
- High spenders did not always accept more campaigns.
- Campaign response varies significantly across demographic groups.

---

## 💡 Business Value

This analysis helps marketing teams:
- Improve customer targeting strategies  
- Optimize marketing budget allocation  
- Identify high-value but low-engagement customers  
- Increase overall campaign ROI  

---

## 📁 Files Included

- marketing_campaign_analysis.sql — Contains all SQL queries used in the analysis  
