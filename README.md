# Krishi-Seva
**Overview**

Krishi Seva is a comprehensive Database Management System (DBMS) project developed to streamline the management of agricultural resources. Built using PostgreSQL, the system efficiently organizes and manages data related to farmers, workers, traders, banks, government schemes, and crops. The database schema comprises 11 relational tables, including Crops, Banks, GovernmentSchemes, Workers, Traders, Farmers, Dependents, WorkerJobs, FarmingLand, WorkingLogs, and Occupations, all normalized to BCNF to ensure optimal data integrity and eliminate redundancy.

**Key Insights**

The project includes various functional modules to cater to different stakeholders. Farmers can check their eligibility for government schemes, view credit scores, calculate profits, and project future loan amounts. Workers can track their total earnings and find job opportunities in their area. Traders can locate farmers harvesting specific crops and assess trading opportunities, while government officials can evaluate the performance of government aid, identify top-performing farms, and analyze regional trader activities. Banks can retrieve farmers' personal and financial details to assess CIBIL scores and loan eligibility.

**SQL Operations and Data Integrity**

The system includes SQL queries for performing operations such as data retrieval, CRUD operations, profit analysis, loan projections, and worker wage calculations. These queries leverage complex SQL features like joins, subqueries, constraints, and aggregate functions to provide meaningful insights and ensure accurate results. The database also incorporates various constraints such as FOREIGN KEY, CHECK, and UNIQUE to enforce data validity and integrity, along with loan eligibility and CIBIL score checks.
