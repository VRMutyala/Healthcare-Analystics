# Healthcare-Analystics
# Healthcare Dataset - Data Preparation & Power BI Reporting Summary

https://app.powerbi.com/reportEmbed?reportId=62862162-1b1f-429d-85e5-eafa703dcea3&autoAuth=true&ctid=f1f14c92-fde3-489f-8eeb-514d2f167be6

## Overview

This project involves detailed data preparation and Power BI reporting for a healthcare dataset containing patient information, medical conditions, and insurance provider details. As a **BI Data Analyst**, I profiled and cleaned the dataset (16 columns, 10K rows) to enable insightful and interactive visualizations.

## Data Preparation Steps

Before moving into Power BI, the dataset underwent extensive cleansing and transformation:

- Removed duplicate records to ensure data integrity.
- Handled missing/null values via imputation or exclusion.
- Standardized column names for consistency and readability.
- Corrected data types, e.g., converting date strings to `Date/Time`.
- Normalized categorical fields, such as medical conditions and insurance providers.
- Filtered irrelevant records that didn’t contribute to business insights.
- Created calculated columns and DAX measures to enable meaningful KPIs.
- Applied Power Query transformations to improve performance.
- Calendar table added and marked as the official Date table.

## Reports

### 1.Patients Overview

This report provides a high-level snapshot of patient demographics.

- **Card Visuals**:  
  - Total Headcount  
  - Female Count  
  - Male Count  
- **Slicers**:  
  - Admission Type  
  - Year  
- **Visualizations**:  
  - Infographic Designer Visual: Shows gender distribution in percentages  
  - Table Visual: Displays detailed patient data with customizable columns  
  - Decomposition Tree: Breaks down total patients by age group and test results  
  - 100% Stacked Column Chart: Gender-wise medication usage percentages

### 2. **Medical Condition Analysis**

This report uncovers trends and distribution patterns in patient health.

- **Slicers**:  
  - Year  
  - Month  
  - Age Group & Age  
  - Blood Group  
- **Visualizations**:  
  - Card Visuals: YoY growth % for each medical condition  
  - Clustered Column Chart: Male vs. female patients by admission type  
  - Matrix Table: Patients by condition, year, gender, and blood group

### 3. **Insurance Provider Insights**

This report breaks down patient billing and demographics across insurance providers.

- **Metrics Tracked**:  
  - Total Headcount  
  - Gender Split  
  - Total Bill Amount  
  - Condition-specific counts (Arthritis, Asthma, Cancer, Diabetes, Hypertension, Obesity)
- **Slicers**:  
  - Insurance Provider  
  - Gender

#### Visualizations:

- Line & Stacked Column Chart: Year-wise bill amounts by insurance provider  
  - **Conditional Formatting** for bill ranges:  
    - Min (225,000): Dust Blue  
    - Mid (325,000): Shade of Pink  
    - Max (480,000): Light Teal Green

- *Stacked Bar Chart: Top 5 hospitals with highest billing amounts  
  - **Conditional Formatting** for bill amounts by hospital:  
    - Min (320,000): Dust Blue  
    - Mid (425,000): Shade of Pink  
    - Max (480,000): Light Teal Green
<img width="1787" height="947" alt="Image" src="https://github.com/user-attachments/assets/3f12066d-1dc4-4ce0-a9d8-7ed5b6d48dc5" />
## Tools Used

- Microsoft Power BI  
- Power Query Editor  
- DAX for calculated columns and measures

##  Dataset Summary

- **Rows**: 10,000+  
- **Columns**: 16  
- **Domains**: Patient Demographics, Medical Conditions, Insurance, Billing

##  Future Enhancements

- Drill-through pages for condition-specific deep dives  
- Geo-mapping of patient distribution (if location data is available)  
- Predictive modeling on future admissions or billing amounts  

## Feedback & Contributions

Feel free to fork this repository, suggest improvements, or raise issues for enhancements.  
Let’s make healthcare data more insightful, one dashboard at a time.
