# 📊 Project 01 — Restaurant Bill Analysis (Tips Dataset)

This project analyzes the **Tips Dataset** using Python and Pandas.
It was created as part of my daily data analysis practice and is my first real project in Pandas.

------------------------------------------------------------

## 📁 Project Overview

The goal of this project is to understand:

- Customer tipping behavior
- Total bill patterns
- How gender, time, day, and smoking habits affect tips
- How to filter, group, and summarize data
- How to create new calculated columns

This project helped me build confidence in Pandas basics.

------------------------------------------------------------

## 🗂️ Dataset Information

The dataset is loaded from **Seaborn**:

import seaborn as sns
df = sns.load_dataset("tips")

Columns in the dataset:

total_bill     -> Total bill paid  
tip            -> Tip amount  
sex            -> Male or Female  
smoker         -> Customer is a smoker (Yes/No)  
day            -> Day of the week  
time           -> Lunch or Dinner  
size           -> Number of people at the table  

------------------------------------------------------------

## 📝 Tasks Completed

### Task 1: Basic Exploration
- Displayed first & last rows
- Checked columns & data types
- Viewed dataset structure
- Generated summary statistics

### Task 2: Filtering Operations
- Filtered tips above 5
- Selected Dinner customers
- Selected total bills between 20 and 40
- Filtered Female smokers

### Task 3: Grouping & Aggregation
- Average tip
- Average total bill
- Average tip by gender
- Total revenue per day
- Average tip by Lunch vs Dinner
- Average bill per table size

### Task 4: Highest & Lowest Values
- Highest tip
- Largest total bill
- Smallest tip
- Day with highest total revenue

### Task 5: Feature Engineering
- Created new column: tip percentage
- Added "Good" or "Normal" tip labels
- Calculated bill per person

------------------------------------------------------------

## 🛠️ Libraries Used

- Pandas
- NumPy
- Seaborn

------------------------------------------------------------

## 🚀 How to Run This Project

# Install dependencies
pip install pandas seaborn numpy

# Run the notebook
jupyter notebook tips_analysis.ipynb

------------------------------------------------------------

## 🎯 What I Learned

- Exploring a dataset
- Filtering data with conditions
- Aggregations using groupby()
- Creating new calculated columns
- Finding max/min values
- Working with categorical data

------------------------------------------------------------

## 🧑‍💻 Author

Amritpritpal Singh 
Learning Pandas & Data Analysis ✨

