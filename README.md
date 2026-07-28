# healthcare-readmission-dashboard
An end-to-end healthcare analytics project using SQL and Tableau to analyze CMS Hospital Readmissions Reduction Program data for heart failure (READM_30_HF).

## Project Overview

This project explores 30-day heart failure readmission performance across 3,151 U.S. hospitals using publicly available Centers for Medicare & Medicaid Services (CMS) data. The data was queried using SQL and visualized in an interactive Tableau dashboard to identify national, state, and hospital-level trends.

## Data Preparation

- Filtered the CMS dataset to include only the Heart Failure (READM_30_HF) measure
- Removed unnecessary columns
- Standardized field names and verified missing values
- Saved the cleaned dataset for SQL analysis and Tableau visualization

## Dashboard Features

- KPI summary cards
  - Average readmission score
  - Total hospitals included
  - States and territories analyzed
- Hospital performance distribution compared to the national average
- Interactive state performance map
- Top 10 hospitals with the lowest readmission scores
- Top 10 hospitals with the highest readmission scores
- Interactive filtering by state

## Tools Used

- SQL
- Tableau Desktop
- CMS Hospital Readmissions Reduction Program Dataset

## Skills Demonstrated

- Data cleaning
- SQL querying
- Healthcare analytics
- Data visualization
- Dashboard design
- Geographic analysis
- Interactive dashboard development

## Repository Contents

| File | Description |
|------|-------------|
| Heart_Failure_Readmission_Dashboard.twbx | Tableau workbook |
| dashboard.pdf | PDF export of the dashboard |
| dashboard.png | Dashboard preview image |
| SQL_queries.sql | SQL queries used for analysis |
| Hospital_Readmissions_Data.csv | CMS dataset used in the project |

## Data Source

Centers for Medicare & Medicaid Services (CMS) Provider Data.

## Live Interactive Dashboard

View the dashboard on Tableau Public:

https://public.tableau.com/views/HospitalReadmissionsProjectFinal/HeartFailureReadmissionDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
