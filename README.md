# HR Employee Report (SQL & Power BI)

## Project Overview

This project focuses on analyzing Human Resources data to gain insights into employee demographics, turnover rates, tenure, and department distributions. SQL is used for querying the HR database, and Power BI is utilized for visualizing key findings through interactive dashboards.

## Project Structure

The project is organized into the following main directories:
```plaintext

HR-Employee-Report-SQL_PowerBI/
│
├── data/
│   ├── CSV_Files/
│   │   ├── raw/
│   │   │   └── Human Resources.csv
│   │   ├── processed/
│   │   │   ├── age_group.csv
│   │   │   ├── age_group_gender.csv
│   │   │   ├── avg_lenght_employment.csv
│   │   │   ├── avg_tenure.csv
│   │   │   ├── employee_change.csv
│   │   │   ├── gender.csv
│   │   │   ├── gender_department.csv
│   │   │   ├── Human Resources.csv
│   │   │   ├── jobtitle.csv
│   │   │   ├── location.csv
│   │   │   ├── race.csv
│   │   │   └── turnover_rate.csv
│   └── SQL_Files/
│       ├── Project_HR.sql
│       └── HR DATA QUESTIONS.sql
│
├── Dashboard/
│   └── HR_Employee_Report.pdf
│
└── PowerBI/
    └── HR_Employee_Report.pbix
```

## Project Files

- **data/CSV_Files/raw/**  
  Contains the raw dataset:  
  - `Human Resources.csv`

- **data/CSV_Files/processed/**  
  Contains processed datasets:  
  - `age_group.csv`
  - `age_group_gender.csv`
  - `avg_length_employment.csv`
  - `avg_tenure.csv`
  - `employee_change.csv`
  - `gender.csv`
  - `gender_department.csv`
  - `jobtitle.csv`
  - `location.csv`
  - `race.csv`
  - `state.csv`
  - `turnover_rate.csv`

- **data/SQL_Files/**  
  Contains SQL queries and scripts:  
  - `Project_HR.sql`  
    SQL commands for creating and modifying the `hr` table, date formatting, and age calculations.
  - `HR DATA QUESTIONS.sql`  
    SQL queries answering key HR-related questions such as employee distribution by gender, department turnover rates, and tenure.

- **Dashboard/**  
  Contains the Power BI dashboard:  
  - `HR_Employee_Report.pdf`  
    PDF version of the dashboard for easy viewing.

- **PowerBI/**  
  Contains the Power BI file:  
  - `HR_Employee_Report.pbix`

## SQL Queries Breakdown

### Key SQL Queries in `Project_HR.sql`:
- Data cleaning and transformation of birth dates, hire dates, and term dates.
- Calculation of employee ages based on birthdate.
- Modifications to the `hr` table for improved data handling.

### Key SQL Queries in `HR DATA QUESTIONS.sql`:
- Gender and race/ethnicity breakdown of employees.
- Age group distribution and breakdown by gender.
- Location-based employee counts.
- Department-wise turnover rates.
- Job title distribution across the company.
- Tenure distribution per department.
- Employee count changes over time.

## Dashboard Overview

The Power BI dashboard includes the following visualizations:
- **Gender Distribution**
- **Turnover Rate by Department**
- **Age Group and Gender Breakdown**
- **Employee Distribution by Location**
- **Tenure and Average Length of Employment**
  
These insights provide a clear overview of the HR data, helping the company make informed workforce management decisions.

## Tools Used
- **SQL**: Data querying and transformation.
- **Power BI**: Data visualization and dashboard creation.

## How to Use

1. **SQL Queries**: 
   - Use the SQL files in `data/SQL_Files/` to query the HR database.
   - The queries provide key HR insights and metrics.

2. **Power BI Dashboard**: 
   - Open the Power BI file `HR_Employee_Report.pbix` in Power BI to explore the interactive dashboard.
   - Alternatively, view the dashboard in PDF format in `Dashboard/HR_Employee_Report.pdf`.

## Author

Elkoudy