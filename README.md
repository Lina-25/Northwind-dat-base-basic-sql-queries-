# Northwind-data-base-basic-sql-queries-
# SQL Queries for Northwind Database

This repository contains a series of SQL queries designed to analyze and aggregate data from the **Northwind database**, a classic sample database that is widely used for learning SQL. The database includes data about customers, orders, products, and sales, providing valuable insights for business analysis.

The queries demonstrated in this repository cover a variety of SQL functions that allow us to explore, filter, and summarize data. By using functions such as `SELECT`, `COUNT`, `SUM`, and `AVG`, I've demonstrated how to analyze business trends, identify top-selling products, calculate totals, and filter records based on specific conditions.
## Functions and SQL Syntax Used

### 1. **SELECT * and FROM**
   - The `SELECT *` statement is used to select all columns from a specific table in the database.
   - This is important for quickly retrieving all data without specifying individual columns.

   - ![Screen Shot 2025-02-18 at 11 17 46](https://github.com/user-attachments/assets/56aba460-f45c-49cb-9778-b602b7a49bf2)


### 2. **SELECT COUNT and SELECT COUNT(DISTINCT)**
   - The `SELECT COUNT` function is used to count the number of rows in a table that match a certain condition.
   - The `SELECT COUNT(DISTINCT)` is used to count the number of distinct (unique) values in a column.
   - These functions are important for summarizing data and identifying the number of records or unique entries.
![Screen Shot 2025-02-18 at 11 18 00](https://github.com/user-attachments/assets/8af7fb55-c65a-4812-9457-642568821248)

### 3. **SELECT DISTINCT**
   - The `SELECT DISTINCT` function is used to return only distinct (unique) values from a column.
   - This function is useful for eliminating duplicate records and analyzing unique data.

### 4. **WHERE Clause with Conditions (AND, OR)**
   - The `WHERE` clause is used to filter records that meet a certain condition.
   - The `AND` operator is used to filter records that satisfy multiple conditions, while the `OR` operator allows for conditions to be met if any one of them is true.
   - These operators are critical for refining data based on multiple conditions and enabling more specific queries.
![Screen Shot 2025-02-18 at 11 19 07](https://github.com/user-attachments/assets/eb7db840-b6fd-4cfc-9d4f-5e87f2cd682d)

### 5. **ORDER BY and DESC**
   - The `ORDER BY` clause is used to sort the results by one or more columns.
   - The `DESC` keyword sorts the data in descending order.
   - Sorting is essential for presenting data in an ordered manner, whether by date, value, or another criterion.
![Screen Shot 2025-02-18 at 11 19 33](https://github.com/user-attachments/assets/13ecf1c8-19ec-4071-9b16-d0505064b2ab)

### 6. **LIMIT**
   - The `LIMIT` clause is used to restrict the number of rows returned by a query.
- This is useful for limiting large result sets, especially when analyzing data for specific samples.
  ![Screen Shot 2025-02-18 at 11 19 50](https://github.com/user-attachments/assets/6a0a17fa-10d1-4d74-b226-86c537020a09)
  
### 7. **MIN and MAX Functions**
   - The `MIN` and `MAX` functions are used to retrieve the smallest and largest values in a column, respectively.
   - These functions are particularly useful for identifying the range of data, such as the lowest and highest prices.
![Screen Shot 2025-02-18 at 11 20 48](https://github.com/user-attachments/assets/72133c57-ddf1-4a25-a7d0-51aaed5ca6fd)

### 8. **SUM and AVG Functions**
   - The `SUM` function is used to calculate the total sum of values in a column.
   - The `AVG` function calculates the average value of a column.
   - These functions are crucial for performing aggregate calculations, such as determining total sales or average prices.
![Screen Shot 2025-02-18 at 11 21 15](https://github.com/user-attachments/assets/fd791892-740c-4166-9f26-fcdac0e4d00f)

### 9. **LIKE and NOT LIKE**
   - The `LIKE` operator is used to search for a specified pattern in a column, such as matching a certain substring.
   - The `NOT LIKE` operator excludes records that match a pattern.
   - These operators are essential for text-based searches, such as finding specific product names or customer details.
![Screen Shot 2025-02-18 at 11 21 34](https://github.com/user-attachments/assets/b66e78c4-c58a-4234-826d-9eb3a6216939)

### 10. **WHERE Clause with Multiple Strings**
   - The `WHERE` clause can be used with multiple string values in a list, using the `IN` keyword.
   - This is important for filtering data based on multiple possible values for a column, such as selecting data from a set of cities or categories.
![Screen Shot 2025-02-18 at 11 22 29](https://github.com/user-attachments/assets/3267f193-245c-456f-a0fb-82af76b450f9)

### 11. **BETWEEN and NOT BETWEEN**
   - The `BETWEEN` operator is used to filter results within a specific range of values.
   - The `NOT BETWEEN` operator excludes results that fall within a specific range.
   - These operators are useful for filtering data based on numerical or date ranges.
![Screen Shot 2025-02-18 at 11 22 47](https://github.com/user-attachments/assets/d5e1a775-ea85-451d-a4c6-641263672fa0)


## Conclusion

The SQL queries and functions demonstrated in this repository are essential tools for performing basic data analysis and aggregation. Understanding how to use these functions is crucial for extracting meaningful insights from large datasets. By using SQL queries to filter, group, and aggregate data, you can gain a deeper understanding of the data's structure and trends.

This repository serves as a foundational resource for SQL beginners looking to learn essential query techniques, and it can be expanded with more complex queries and visualizations as you progress in your learning journey.
