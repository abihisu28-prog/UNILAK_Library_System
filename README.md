UNILAK LIBRARY MANAGEMENT SYSTEM
Author: Abiel Hisabu Tesfay
Student ID: 32135
Project Overview: This repository contains the complete database implementation for the UNILAK Library Management System, including setup scripts, CTE-based analytical queries, and Window Function applications for data reporting.
Table of Contents
1. Project Overview
2. Database Implementation
3. Analytical Queries
4. Analysis and Findings
Database Implementation
The foundation of this system includes three core tables: ⁠Books⁠, ⁠Students⁠, and ⁠Borrows⁠. The ⁠setup.sql⁠ file creates these tables and establishes necessary constraints, such as primary and foreign keys, to maintain data integrity.
Analytical Queries
Part A: Common Table Expressions (CTEs)
 Simple CTE: Filters high-value rentals and aggregates results.
 Multiple CTEs: Combines customer spending patterns and total volume of orders.
 Recursive CTE: Generates a 5-day booking timeline for system scheduling.
 CTE with Join: Connects inventory details with rental transaction history.
Analysis and Findings
 Descriptive Analysis: The system is built to manage book borrowing, student records, and inventory data at UNILAK, demonstrating robust data handling and relational design.
 Diagnostic Analysis: Analysis of loan data shows peak usage for critical Computer Science texts, identifying high-demand areas within the library's collection.
 Prescriptive Analysis: We recommend a targeted budget increase for computer science and technical textbooks to meet growing demand, and an update to key database volumes to accommodate higher transaction logs.
