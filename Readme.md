# 📦 Zepto Inventory SQL Project

This is a basic SQL project inspired by a Zepto-style inventory management system. It's designed to
help me learn SQL fundamentals such as data modeling, writing queries, data analysis, and 
generating insights using real-world-like datasets.

# 📚 What This Project Covers

✅ Creating and managing a MySQL database

✅ Designing a product inventory table structure

✅ Importing data from Excel/CSV into MySQL

✅ Writing SQL queries for:

         1.Filtering and selecting data

         2.Aggregations (SUM, COUNT)

         3.Grouping by category

         4.Revenue calculation

# 🛠 Tools Used
      MySQL Workbench – to create database and run queries

      Microsoft Excel – for dataset cleanup and conversion to CSV

      Kaggle Dataset – The dataset used in this project was sourced from [Kaggle - Zepto Inventory Dataset](https://www.kaggle.com/datasets/palvinder2006/zepto-inventory-dataset/data?select=zepto_v2.csv).

# 🗂️ Project Structure
This project follows a structured SQL-based data analysis pipeline:

1. 📥 **Dataset Download**  
   - Downloaded from [Kaggle - Zepto Inventory Dataset](https://www.kaggle.com/datasets/palvinder2006/zepto-inventory-dataset/data?select=zepto_v2.csv)

2. 🗃️ **Database and Table Creation**  
   - Created a MySQL database named `Zepto_SQL_Project`  
   - Designed and created a table called `zepto` with appropriate data types (`INT`, `NUMERIC`, `VARCHAR`, `BOOLEAN`)

3. 📊 **Data Import**  
   - Imported the cleaned `.csv` file (`zepto_v2.csv`) into MySQL using MySQL Workbench  
   - Resolved issues like:
     - Replacing boolean `TRUE`/`FALSE` with `1`/`0`

4. 🧹 **Data Cleaning**  
   - Converted text boolean values (`TRUE`, `FALSE`) into integers (`1`, `0`) using Excel formulas  
   - Verified and fixed column data types and row integrity  
   - Removed duplicates and handled nulls if any

5. 📈 **Data Analysis Using SQL**  
   - Calculated revenue per product and by category  
   - Categorized products by weight range (`low`, `medium`, `bulk`) using `CASE` statements  
   - Aggregated available quantity and discount insights  
   - Used `GROUP BY`, `ORDER BY`, `SUM()`, `COUNT()` and `CASE WHEN` for insights

# 💡 What I Learned
How to design and structure a SQL database

How to import real-world data into MySQL from Excel/CSV

SQL concepts like GROUP BY, SUM(), CASE WHEN, and conditional filtering

Data cleaning and resolving schema/data mismatches

Debugging import errors like duplicate column names, type mismatches, and missing keys
         



