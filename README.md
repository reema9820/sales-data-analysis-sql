# sales-data-analysis-sql

**SQL Sales Data Repository**

This repository contains an SQL script creating and manipulating a sales_data table. The table captures sales information such as product details, quantity, sale date, amount, customer details, region, and sales representative ID. Additionally, various SQL queries are included to showcase data retrieval and analysis.

**Table Structure**
sales_data table fields:
SaleID (Primary Key),
ProductName,
Quantity,
SaleDate,
SaleAmount,
ClientName (formerly CustomerName),
Region,
SalesRepID

The script demonstrates the following key SQL concepts:

**1. Table Creation:**
Defines a table (sales_data) with appropriate data types and constraints.
Utilizes primary keys for unique identification.

**2. Data Manipulation:**
Inserts sample data into the sales_data table, demonstrating the INSERT statement for adding records.

**3. Data Retrieval:**
Utilizes the SELECT statement to retrieve data from the sales_data table.
Demonstrates simple queries to retrieve all records and more complex queries to filter data based on specific criteria.

**4. Data Filtering and Analysis:**
Uses the WHERE clause to filter records based on product names, sale dates, sale amounts, regions, and more.
Demonstrates the use of logical operators (AND, OR, NOT) for complex conditions.
Utilizes the BETWEEN operator for date range queries.

**5. Aggregation:**
Showcases the use of aggregate functions (SUM, AVG, MAX) for analyzing sales data.
Utilizes the GROUP BY clause to group records based on certain criteria.

**6. Data Modification:**
Demonstrates the UPDATE statement to modify records, updating SalesRepID values where they are NULL.
Uses the ALTER TABLE statement to add and drop a column (DiscountPercent).

**7. String Manipulation:**
Includes examples of string manipulation using functions like CONCAT, UPPER, LOWER, LEFT, RIGHT, and REPLACE.

**8. Handling NULL Values:**
Demonstrates handling NULL values using the IFNULL function and updating NULL values.

**9. Default Values:**
Uses the DEFAULT keyword to set a default value for a column (DiscountPercent).

**10. Column Renaming and Table Alteration:**
Uses the ALTER TABLE statement to rename a column (CustomerName to ClientName).
Illustrates how to add and drop a column.

**11. Advanced Queries:**
Implements more advanced queries, such as finding top-selling products, identifying high-performing sales representatives, and calculating average sales amounts per region.

**12. Sorting and Limiting:**
Uses the ORDER BY clause to sort results.
Implements the LIMIT clause to restrict the number of returned rows.

**13. Pattern Matching:**
Demonstrates pattern matching using the LIKE operator for customer name filtering.

**14. Handling Duplicates:**
Uses the DISTINCT keyword to retrieve unique records.

**15. Error Handling:**
Addresses potential issues like renaming a column that does not exist (commented out for safety).

**16. Comments:**
Includes comments throughout the script to provide clarity and explanations.
