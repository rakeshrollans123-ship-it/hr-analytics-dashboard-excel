# HR Analytics Dashboard (Excel)

An interactive Excel dashboard analysing **9,964 employee records** across 10 departments. It uses PivotTables, charts, slicers and formula-driven KPI cards to show headcount, attrition, salary, tenure and training.

## Dataset
`HR_Data` sheet: 9,964 rows × 18 columns (Employee_ID, Full_Name, Gender, Age, Age Bucket, Department, Employment_Type, Job_Title, Hire_Date, Exit_Date, Years_of_Service, Tenure Bucket, Annual_Salary, Bonus_Percentage, Performance_Rating, Reports_To_Manager_ID, Training_Hours_Last_Year, Location).

## Dashboard
- **KPI cards:** Total Employees, Active, Leavers, Average Salary, Average Tenure, Average Age, Average Training
- **Charts:** Headcount by Department, Gender Distribution, Average Salary by Department, Headcount by Location, Salary by Location, Headcount by Hire Date
- **Slicers:** Gender, Age Bucket, Department, Location

## How It Works
- Raw data is stored as an Excel Table (`Table1`).
- The `calc engine` sheet calculates KPIs with structured references, e.g. `=COUNTA(Table1[Employee_ID])`, `=AVERAGE(Table1[Annual_Salary])`.
- Six PivotTables feed the charts, and the `Dashboard` sheet brings everything together.

## Key Findings
- 9,964 employees: **8,674 active** and **1,290 leavers** (about 12.9% attrition)
- Average salary ≈ 81,364 · average tenure 4.8 years · average age 43 · average training 49 hours
- Highest average salary by department: Legal (≈110,043), Strategy (≈104,611), Product (≈97,466); lowest: Support (≈54,723)

## Skills
Excel Tables · PivotTables & PivotCharts · Slicers · Structured references · Dashboard design · HR analytics
