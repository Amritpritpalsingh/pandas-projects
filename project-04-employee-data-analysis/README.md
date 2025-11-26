# 🧾 Project 04 — Employee Data Analysis (HR Analytics)

This project performs **HR Data Analysis** using Python and Pandas.  
The goal is to explore employee performance metrics such as salary distribution, experience levels, and department-wise workforce insights.

---

## 📁 Project Overview

In this project, I analyzed a dataset of employees to understand:

- Salary distribution across the company  
- Age and experience trends  
- Department-wise workforce and salary budget  
- Youngest & oldest employees  
- Seniority and promotion eligibility  

This project strengthened my skills in **data cleaning, transformation, grouping, and business insights using Pandas**.

---

## 🗂️ Dataset Information

Dataset file used: `employees.csv`

| Column | Description |
|--------|-------------|
| Emp_ID | Unique employee ID |
| Name | Employee name |
| Age | Employee age |
| Gender | Male/Female |
| Department | Working department |
| Salary | Monthly salary (in ₹) |
| Experience_Years | Work experience in years |

---

## 📝 Tasks Completed

### ✔ **Task 1 — Load & Explore**
- Loaded dataset from CSV
- Displayed first & last 5 rows
- Checked shape, column names, and data types
- Summary statistics and missing value count

### ✔ **Task 2 — Data Cleaning**
- Filled missing numeric values with mean
- Filled missing categorical values with mode
- Removed duplicate rows
- Stripped whitespace from Name & Department
- Converted categorical columns to `category` type

### ✔ **Task 3 — Filtering & Sorting**
- Filtered highly paid employees (Salary > 100,000)
- Employees with Age < 30
- Experience > 5 years
- Female employees in Finance
- Sorted by Salary (descending)
- Sorted by Department → Salary

### ✔ **Task 4 — Derived Columns**
- `Salary_per_Year_Exp` created using Salary / Experience
- `Seniority` based on experience:
  - Junior | Mid | Senior
- Promotion eligibility condition applied

### ✔ **Task 5 — Grouping & Aggregation**
- Average salary per department
- Highest salary per gender
- Total salary budget per department
- Department-wise average age
- Gender count

### ✔ **Task 6 — Advanced Insights**
- Highest paid employee (full row)
- Lowest paid employee
- Youngest & oldest employees
- Department with highest salary expenditure
- Top 3 highest paid employees

---

