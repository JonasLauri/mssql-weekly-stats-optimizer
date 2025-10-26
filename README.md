# MSSQL Weekly Statistics Optimizer

## Overview

This project focuses on optimizing recurring SQL queries that were previously slow and dependent on multiple servers. The goal was to **reduce execution time**, **consolidate data retrieval**, and **improve query performance** within Microsoft SQL Server.

The optimization process included:

* Parameterizing repetitive queries
* Using temporary tables for intermediate data storage
* Designing a centralized query structure for weekly statistics

---

## Tools & Technologies

* **T-SQL (Transact-SQL)**
* **Microsoft SQL Server Management Studio (SSMS)**

---

## Key Improvements

* Reduced data retrieval time by merging multiple queries into one parameterized structure
* Improved performance using temporary tables for joins and aggregations
* Simplified maintenance by centralizing scripts into a single optimized process

---

## Results & Impact

* Query runtime reduced from *minutes to seconds*
* All data now retrieved from a *single SQL instance*
* Easier maintenance, faster reporting, and improved scalability
