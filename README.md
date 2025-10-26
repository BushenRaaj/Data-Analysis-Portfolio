# 📊 Data Analysis Portfolio – Python & Power BI

This repository contains two complete data analytics projects combining **Python (Pandas, NumPy)** for data processing and **Power BI** for visualization.

---


## 🚀 Projects Overview

### 🧾 [Project 1 – HR Attrition Data Analysis](./Project_1_HR_Attrition_Analysis)
Analyze employee attrition patterns using HR data to identify key factors influencing turnover.

## 🧮 Datasets
| File Name | Description |
|------------|-------------|
| `WA_Fn-UseC_-HR-Employee-Attrition.csv` | Raw dataset containing HR-Attrition details |
| `Cleaned_HR_Attrition.xlsx` | Cleaned dataset after preprocessing in Python |
| `Cleaning_Dataset.ipynb` | Jupyter Notebook used for data cleaning and transformation |
| `HR_Attrition_Data_Sheet.pbix` | Power BI dashboard file |
---

## 🧱 Steps Involved in Building the Project

### 1. Data Collection
- Imported the raw dataset (`WA_Fn-UseC_-HR-Employee-Attrition.csv`) for analysis.

### 2. Data Cleaning (Python - Jupyter Notebook)
- Handled missing values, standardized column names, and converted categorical data into dummy variables.  
- Exported the cleaned data to Excel as `Cleaned_HR_Attrition.xlsx`.

### 3. Data Transformation (Power BI)
- Dropped redundant columns including `OverTime_Yes`, `Department_Research & Development`, `JobRole_Manager`, etc.  
- Added calculated columns such as:  
  - **Age Group**, **Salary Band**, **Employee Tenure**, **Risk Score**, and **Risk Category**.  
- Created **DAX measures** for key metrics like:  
  - `Total Employees`, `Avg Monthly Income`, `Attrition Rate`, `Avg Job Satisfaction`, etc.

### 4. Visualization (Power BI Dashboard)
- Designed interactive visuals showing attrition distribution, income vs. tenure, satisfaction vs. performance, etc.  
- Highlighted high-risk groups and key trends using custom KPIs.

---

## 📊 Key Insights
- Younger employees and those with lower monthly incomes had higher attrition rates.  
- Employees with poor job satisfaction or limited career growth showed higher attrition risk.  
- The Risk Score model effectively categorized employees into **Low**, **Medium**, and **High** attrition risk levels.  

---
## 📊 Final Dashboard Preview

<img width="1281" height="721" alt="Screenshot 2025-10-26 150017" src="https://github.com/user-attachments/assets/1cc7743a-9eaa-4ca2-8b28-52f639119ab5" />

---

<img width="1287" height="721" alt="Screenshot 2025-10-26 150030" src="https://github.com/user-attachments/assets/0307ed04-f76b-46b0-98ac-68a435620b86" />

---

<img width="1280" height="723" alt="Screenshot 2025-10-26 150044" src="https://github.com/user-attachments/assets/79aac68f-bae1-4eb6-a141-c1380dccb307" />

---

<img width="1285" height="717" alt="Screenshot 2025-10-26 150057" src="https://github.com/user-attachments/assets/76d6ff61-8ad7-4c71-8f9c-91481fbcffda" />

---

<img width="1285" height="722" alt="Screenshot 2025-10-26 150111" src="https://github.com/user-attachments/assets/b5dadfc1-4965-42f3-8258-d74517734f83" />

---

## 📂 Repository Structure

- [**WA_Fn-UseC_-HR-Employee-Attrition.csv**](WA_Fn-UseC_-HR-Employee-Attrition.csv) | Raw dataset containing employee demographic, job, and satisfaction details. 
- [**Cleaned_HR_Attrition.xlsx**](Cleaned_HR_Attrition.xlsx) | Cleaned and processed dataset generated using Python. 
- [**Cleaning_Dataset.ipynb**](Cleaning_Dataset.ipynb) | Jupyter Notebook used for data cleaning and preprocessing. 
- [**HR_Attrition_Data_Sheet.pbix**](HR_Attrition_Data_Sheet.pbix) | Power BI dashboard file for visual analytics.  

---

### 📦 [Project 2 – E-Commerce Delivery Performance Analysis](./Project_2_ECommerce_Delivery_Performance)
Evaluate delivery efficiency and customer satisfaction through e-commerce data analytics.

## 🧮 Datasets
| File Name | Description |
|------------|-------------|
| `Train.csv` | Raw dataset containing e-commerce order details |
| `Cleaned_Train_File.xls` | Cleaned dataset after preprocessing in Python |
| `E-commerce.ipynb` | Jupyter Notebook used for data cleaning and transformation |
| `ecomus sheet.xlsx` | Transformed dataset post Power Query |
| `E-Commerce Delivery Performance.pbix` | Power BI dashboard file |

---

## 🧱 Steps Involved in Building the Project

### 1. Data Collection
Imported the raw dataset (`Train.csv`) containing e-commerce order details, shipment modes, warehouses, product costs, discounts, and customer ratings.

### 2. Data Cleaning (Python – Jupyter Notebook)
- Handled missing and inconsistent values.  
- Removed duplicates and standardized categorical fields.  
- Created new columns such as:
  - `Discount_Percent`
  - `Gender_Label`
  - `Weight_Bin`
- Exported the cleaned dataset as **Cleaned_Train_File.xls**.

### 3. Data Transformation (Power BI)
- Imported the cleaned dataset and refined data using **Power Query (M Code)**.  
- Created calculated columns:
  - `Weight_Bin` – Categorized products by weight range.  
  - `Discount_Percent` – Computed discount as a percentage of product cost.  
  - `Gender_Label` – Converted gender codes (M/F) to descriptive labels.  

- Created **DAX measures**:
  - `Total Orders`  
  - `On-Time Deliveries`  
  - `On-Time %`  
  - `Average Discount %`  
  - `Average Rating`  
  - `Average Cost`  
  - `Total Discount Amount`

### 4. Visualization (Power BI Dashboard)
Designed 2–3 interactive dashboards focusing on:
- **Delivery Performance** (Shipment mode, warehouse, and trends)  
- **Customer Insights** (Ratings vs. Discounts, Product Importance)  
- **Operational Overview** (On-Time %, Average Discount, Cost KPIs)  

Added **slicers for filters**: Shipment Mode, Warehouse, Product Importance, and Gender.  
Used **KPI cards** and **trend lines** for easy performance tracking.

---

## 📊 Key Insights
- Shipments by **Air** had the highest on-time delivery percentage.  
- **Medium-weight products** experienced the most balanced delivery rates and costs.  
- Customers offered **moderate discounts** tended to give higher ratings.  
- Some **warehouses consistently underperformed**, indicating optimization potential.

---

## 📊 Final Dashboard Preview

<img width="1133" height="636" alt="Screenshot " src="https://github.com/user-attachments/assets/f25faccb-335b-414c-a0d7-820520032db9" />

---

<img width="1133" height="637" alt="Screenshot " src="https://github.com/user-attachments/assets/2face64d-1652-43b0-adc2-72bf7e546662" />

---
## 📂 Repository Structure

- [**Train.csv**](Train.csv) | Raw dataset containing e-commerce delivery details including shipment mode, warehouse block, product cost, discount, and customer ratings.  
- [**Cleaned_Train_File.xls**](Cleaned_Train_File.xls) | Cleaned and processed dataset generated using Python (Jupyter Notebook).  
- [**E-commerce.ipynb**](E-commerce.ipynb) | Jupyter Notebook used for data cleaning, preprocessing, and feature engineering.  
- [**E-Commerce Delivery Performance.pbix**](E-Commerce%20Delivery%20Performance.pbix) | Power BI dashboard file for interactive visual analytics.

---

## 🧰 Tools & Technologies Used
- **Python (Jupyter Notebook)** – Data cleaning, preprocessing, and transformation.  
- **Pandas, NumPy** – Data manipulation and feature engineering.  
- **Power BI** – Data modeling, DAX calculations, and dashboard creation.  
- **Power Query (M Code)** – Transformation logic for calculated columns.  
- **Excel** – Cleaned dataset export and validation.

---

## 🧠 About
This repository showcases end-to-end data analytics workflows — from raw data to business insights — integrating **data cleaning, visualization, and storytelling**.

---
