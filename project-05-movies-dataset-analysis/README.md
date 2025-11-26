# 🎬 Project 05 — Movies Dataset Analysis

This project analyzes a **Movies Dataset** using Python and Pandas to understand movie performance, revenue, and genre trends.  
It was created as part of my data analysis practice to strengthen skills in filtering, grouping, aggregation, and creating new insights.

---

## 📁 Project Overview

The goal of this project is to explore:

- Most popular movie genres  
- Relationship between ratings and revenue  
- Top-rated and highest-grossing films  
- Director-wise and year-wise trends  
- Categorizing movies based on revenue and runtime  

This project helps in understanding **real-world entertainment data analysis**.

---

## 🗂️ Dataset Information

Dataset file: `movies.csv`

| Column           | Description |
|-----------------|-------------|
| Movie_ID         | Unique ID for each movie |
| Title            | Movie title |
| Genre            | Movie genre |
| Director         | Director name |
| Year             | Release year |
| Runtime          | Movie duration (minutes) |
| Rating           | IMDb rating |
| Revenue_Millions | Box office revenue (in millions USD) |

---

## 📝 Tasks Completed

### ✔ Task 1 — Load & Explore
- Loaded dataset from CSV  
- Displayed first & last rows  
- Checked shape, column names, and data types  
- Summary statistics and missing value counts  

### ✔ Task 2 — Data Cleaning
- Filled missing numeric values with mean  
- Filled missing categorical values with mode  
- Removed duplicates  
- Stripped whitespace from text columns  
- Converted categorical columns to `category` type  

### ✔ Task 3 — Filtering & Sorting
- Movies with Rating > 8.5  
- Movies released after 2010  
- Revenue > 500 million  
- Sorted by Revenue (descending)  
- Sorted by Rating then Revenue  

### ✔ Task 4 — New Calculated Columns
- `Profit_Category`: High / Medium / Low  
- `Runtime_Category`: Short / Medium / Long  

### ✔ Task 5 — Grouping & Aggregation
- Average revenue by Genre  
- Average rating by Director  
- Total revenue by Year  
- Count of movies per Genre  
- Top 3 highest revenue movies  

### ✔ Task 6 — Pivot Tables
- Average Rating × Genre × Director  
- Total Revenue × Year × Genre  
- Number of movies per Director × Genre  

### ✔ Task 7 — Advanced Insights
- Most popular genre by revenue  
- Highest rated movie  
- Movie with highest revenue  
- Director with highest average rating  
- Year with most movies released  

---
