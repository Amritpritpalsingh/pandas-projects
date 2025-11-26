# 📘 Project 03 — Students Marks Analysis

This project analyzes **student performance and grade distribution** using Pandas.  
The goal is to understand average marks, top performers, weak performers, and overall class trends.

---

## 🎯 Project Objectives

- Calculate **class average, median, and distribution**
- Identify **highest and lowest scoring students**
- Categorize students into **grades (A, B, C, D, F)**
- Analyze **subject-wise performance**
- Visualize marks distribution (optional)

---

## 🗂️ Dataset Information

A typical dataset contains:

| Column       | Description                       |
|--------------|-----------------------------------|
| Student_ID   | Unique ID for each student        |
| Name         | Student name                      |
| Gender       | Male / Female                     |
| Math         | Math marks                        |
| Science      | Science marks                     |
| English      | English marks                     |
| History      | History marks                     |
| Total        | Total marks (Math+Sci+Eng+Hist)   |
| Average      | Average marks                     |
| Grade        | Assigned based on Average score   |

---

## 📝 Tasks Completed

### ✅ **Task 1 — Load & Explore**
- Loaded the student dataset  
- Viewed structure and summary  
- Checked for missing values  
- Verified column types  

---

### ✅ **Task 2 — Data Cleaning**
- Filled missing marks with subject mean  
- Removed duplicate student records  
- Standardized student names  
- Ensured numeric columns are float/int  

---

### ✅ **Task 3 — New Calculated Columns**
- `Total` = Sum of all subjects  
- `Average` = Total / 4  
- `Grade` based on:  
  - **A:** 90+  
  - **B:** 80–89  
  - **C:** 70–79  
  - **D:** 60–69  
  - **F:** <60  

---

### ✅ **Task 4 — Performance Analysis**
- Class average score  
- Highest & lowest scoring students  
- Count of each grade category  
- Top 5 performers  
- Subject in which students scored best/worst  

---

### 🔍 **Key Insights**
- Overall class average  
- Percentage of students failing  
- Most commonly received grade  
- Best performing subject  
- Weakest subject  
- Performance by gender (optional)  

---


