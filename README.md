# 🏥 Hospital_waiting_List Analysis  - Power BI Dashboard
This project presents a Power BI dashboard designed to analyze and visualize hospital waiting list data from 2018 to 2021. The system provides clear insights into the volume, trends, and distribution of patient wait times across various case types, specialties, age groups, and time bands on Median And Average Waiting list .

--- 
## 🔍 Objective

### Project Goals
1. Track current status of patient waiting list
2. Track monthly wait list trends across different case types (Outpatient, Day Case, Inpatient)

3. Identify backlog concentrations by patient age and time bands

4. Compare average vs. median wait lists per specialty

5. Provide detailed visibility into department-level performance

### Data Scope
2018 - 2021
### Metrics Required  

1. Average & Median Waiting List  
2. Current Total Wait List
### Views Required  

1. Summary Page
2. Detailed Page for Granular Analysis


---

## 🖼️ Dashboard Preview

![Main Dashboard](<Hospital Management 1.png>)
---
![Detailed View](<Hospital MAnagement 2.png>)

--- 

# 🧭 Project Workflow


## 1. 📊 Data Collection

- Data collected from Kaggle having two table :
  
  **1. Impatient Data**
  
  **2. Outpatient Data**
- **Inpatient :** Patients those adimitted for more than 1 day in hospital for treatment .
- **Outpatient :** Patients those get treatment without admitted in the hospital .
## 2. 🔧 Data Preperation 

- Imported Both Inpatient and Outpatient data from Kaggle .
- Both folder contains 4 tables each .
- Data is of the years 2018 to 2021 .
- Each table contains the data of a specific year in both Inpatint and Outpatient .

## 3. 📊 Data Modelling 
### Tool Used 
- Power Query Editor
  
**Steps involved in process :**
- Loaded the all data into the Power BI by using Folder Conectors .
- Transformed the data by Renamed the columns , Drops the unnecessary columns , Added the new columns so that we match the cardinality.
- Appended the table and create new table with name All_Data by matching the cardinality.

## 4. 🧹 Data Cleaning 
We performed the cleaning using Power Query Editor : 
- Trimmed the whitespaces of the data .
- Replaced the values which seems to be same .
- Removed the blank spaces .
## 5. 🌍 Visualistion / Report Design  
We created some good visual that includes 
- Cards
- Donut Charts
- Slicers
- Stagged Bar Charts
- Line Charts
- Matrix

To create visuals we created some measures , Columns and new Table using Dax functions  :
- Table to initiate Average and Median slicers
- Cards shows the yearly waiting list .
- Slicers that filters the data to find a specific insights
- Bar charts to show the waiting list by time Bands
- Line charts shows the count by Case Type 

## 6. 🖼️ Conclusion 
- A growing outpatient backlog, especially in specialties like Vascular Surgery.

- A need to prioritize long-waiting age groups (65+) and high-wait departments (e.g., A&E).

- The importance of monitoring time bands to avoid patients waiting over 52 weeks.

- Long-term trends indicate resource strain post-2019, suggesting demand for staff/resource scaling in critical specialties.
