# 🛒 Project 2 — Supermarket Sales Analysis (Tasks)

# -----------------------------------------
# ✅ Task 1: Load & Explore the Data
# -----------------------------------------
1. Load dataset using pd.read_csv()
2. Show first 10 rows
3. Check shape (rows, cols)
4. Print column names
5. Check data types (dtypes)
6. Summary statistics (describe())
7. Check missing values (isnull().sum())

# -----------------------------------------
# ✅ Task 2: Data Cleaning
# -----------------------------------------
1. Replace missing numeric values → mean/median
2. Replace missing categorical values → mode
3. Remove duplicate rows
4. Strip whitespace from text columns
5. Convert date column → datetime
6. Convert category columns → category type
7. Rename inconsistent column names

# -----------------------------------------
# ✅ Task 3: Filtering & Sorting
# -----------------------------------------
1. Filter rows where Unit price > 50
2. Filter rows where Payment == "Cash"
3. Quantity between 5 and 10
4. Female customers only
5. Sort by Total (descending)
6. Sort by Date (ascending)
7. Sort by Product line then Unit price

# -----------------------------------------
# ✅ Task 4: New Calculated Columns
# -----------------------------------------
1. Total = Quantity * Unit price
2. VAT = Total * 0.05
3. Grand_Total = Total + VAT
4. Category:
   - High (Total > 200)
   - Medium (100–200)
   - Low (<100)

# -----------------------------------------
# ✅ Task 5: Grouping & Aggregation
# -----------------------------------------
1. Total revenue per product line
2. Average unit price per product line
3. Total quantity sold per city
4. Avg Grand_Total per gender
5. Most used payment method
6. Top 3 product lines by revenue

# -----------------------------------------
# ✅ Task 6: Pivot Tables
# -----------------------------------------
1. Revenue by City × Product Line
2. Quantity by Gender × Product Line
3. Average Total by Payment method
4. Monthly sales count
5. Revenue trend by Day

# -----------------------------------------
# ✅ Task 7: Highest & Lowest
# -----------------------------------------
1. Row with highest Total
2. Row with lowest Total
3. Highest & lowest revenue product line
4. City with most orders
5. Day with highest revenue


