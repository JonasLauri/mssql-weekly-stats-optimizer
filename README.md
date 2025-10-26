Project Overview

This project focuses on optimizing recurring SQL queries that were slow and required multiple servers to fetch data. The goal was to reduce execution time, consolidate data retrieval, and improve overall query efficiency in Microsoft SQL Server.

The optimization process involved parameterizing queries, using temporary tables, and creating a centralized query structure to pull weekly statistics from a single server instance.

Tools & Technologies

T-SQL (Transact-SQL)

Microsoft SQL Server Management Studio (SSMS)

Key Improvements

Reduced data retrieval time by consolidating multiple queries into one parameterized structure.

Used temporary tables for faster joins and aggregations.

Simplified maintenance by centralizing scripts into a single optimized process.

Results & Outcome

Query runtime reduced from minutes to seconds.

Data is now retrieved from a single SQL instance.

Improved maintainability and performance for future updates.
