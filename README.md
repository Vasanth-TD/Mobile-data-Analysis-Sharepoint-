# Mobile Data Analysis

### Dashboard Link : [Mobile Data Dashboard](https://app.powerbi.com/...)](https://app.powerbi.com/Redirect?action=OpenApp&appId=b51e3f07-479f-4de5-8e60-f4fc6269838e&ctid=5e81dc77-db51-4a31-8660-6858117beb25&experience=power-bi)

---

## Problem Statement

The goal of this project is to analyze mobile phone specifications, pricing, and features across multiple global brands using Power BI.  
By connecting data from a SharePoint Folder, this dashboard enables analysts and product teams to understand:

- Which companies launched the most models  
- How RAM and camera configurations differ across brands  
- How prices vary between countries and currencies  
- Which models deliver the best value for performance  

This interactive Power BI dashboard supports data-driven insights for marketing, pricing, and product strategy.

---

## Steps Followed

Step 1: Created a Microsoft 365 Trial Account and configured licenses.  

Step 2: Built a SharePoint Site and uploaded the mobile dataset.

Step 3: Connected SharePoint Folder to Power BI Desktop as a data source.  

Step 4: Used Power Query Editor for data cleaning and transformation:  
  - Removed duplicates.  
  - Cleaned and formatted PKR Price, RAM, and Launch Price columns.  
  - Standardized data types and renamed fields.  

Step 5: Used ChatGPT to generate currency conversion tables (PKR, AED, INR, CNY, USD).  

Step 6: Created calculated columns and measures using DAX:  
  - CONCATENATE, LEN, IF, LEFT, SWITCH for string operations.  
  - AVERAGE, SUMMARIZE, CALCULATE, DIVIDE for calculations.  

Step 7: Designed 4 report pages:  
  - Overview Page – Model count by company, RAM, and processor distribution.  
  - Camera Resolution Details – Front and back camera breakdowns.  
  - Price Analysis Page – Average prices in multiple currencies.  
  - Feature Analysis Page – RAM, weight, processor, and screen-size insights.  

Step 8: Added slicers for Company Name, Launch Year, RAM Range, and Price Range (USD).  

Step 9: Used bookmarks for regional analysis (India and Dubai).  

Step 10: Published the report to Power BI Service and set up scheduled refresh.

---


## Dashboard Snapshots

### Overview Page

![image alt](https://github.com/Vasanth-TD/Mobile-data-Analysis-Sharepoint-/blob/0d6da08dddf192b2641be67e02fe517d09196848/assets/Images/page%201.png)

### Camera Resolution Details

![image alt](https://github.com/Vasanth-TD/Mobile-data-Analysis-Sharepoint-/blob/2c8143a919ac565b319b4f9ac1ff837dd260bf59/assets/Images/page%202%20.png)


### Price Analysis Page

![image alt](https://github.com/Vasanth-TD/Mobile-data-Analysis-Sharepoint-/blob/2c8143a919ac565b319b4f9ac1ff837dd260bf59/assets/Images/Page%203.png)

### Feature Analysis Page

![image alt](https://github.com/Vasanth-TD/Mobile-data-Analysis-Sharepoint-/blob/0d6da08dddf192b2641be67e02fe517d09196848/assets/Images/page%204.png)

---

## Insights

### 1. Brand and Model Distribution
- Oppo, Apple, and Honor have launched the highest number of models.  
- Apple and Samsung dominate in the premium smartphone category.  
- Realme, Motorola, and Infinix focus on mid-range and budget-friendly devices.

---

### 2. Camera Specifications
- 32 MP and 16 MP are the most common front camera resolutions.  
- 50 MP and 48 MP are the most popular back camera configurations.  
- Multi-lens cameras are now a standard feature in modern smartphones.

---

### 3. RAM and Processor Insights
- Most flagship phones feature 8 GB–16 GB RAM configurations.  
- Higher RAM models correspond with premium pricing and better performance processors.  
- Budget devices are typically equipped with 4 GB–6 GB RAM.

---

### 4. Price Analysis
- Nokia, Sony, and Huawei models have the highest average launch price in USD.  
- Regional price differences (India vs Dubai) are visible due to tax and currency factors.  
- Conversion across PKR, INR, AED, CNY, and USD enables global price comparison.

---

### 5. Feature Insights
- The Feature Analysis Page offers filtering by RAM range, launch price, and model specifications.  
- Users can explore devices by screen size, processor, or camera quality.  
- Helps identify best-value smartphones across markets and regions.

---

## Final Outcome

- End-to-end BI solution using SharePoint → Power BI Desktop → Power BI Service.  
- Developed a 4-page interactive dashboard with bookmarks, filters, and drill-throughs.  
- Used Power Query and DAX for data cleaning, calculations, and performance optimization.  
- Delivered deep insights into mobile brand trends, pricing, and specifications.

---
