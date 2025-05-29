# task3-SQL-for-Data-Analysis
SQLite3 Sales Data Analysis
This Python script demonstrates how to interact with an SQLite database (olist.sqlite) using the sqlite3 module. It performs various SQL operations to analyze and summarize sales data from an e-commerce dataset.

Features:
  Connects to a local SQLite database file using Python’s sqlite3 library.
  Executes SQL queries covering:
  SELECT with filtering (WHERE), grouping (GROUP BY), ordering (ORDER BY), and aggregation (COUNT, AVG).

Joins:
  INNER JOIN between order items and sellers to combine related information.
  LEFT JOIN between customers and orders to include all customers with or without orders.
use of subqueries to filter sellers based on the number of orders.

Creation and querying of a database view (seller_sales_summary) to summarize seller performance.

Creation of an index to optimize query performance on the seller_id column.

Prints query results to the console for quick inspection.

Purpose:
  This project serves as a practical example for learning how to perform common SQL operations using Python and SQLite, including complex queries, database optimization techniques, and data summarization.
