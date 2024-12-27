# Loan Management System Using SQL

A robust SQL-based project designed to manage, analyze, and automate loan and customer data workflows. This system integrates multiple datasets, uses advanced SQL techniques, and provides insightful analytics to streamline loan management processes.

📝 Project Overview

This project demonstrates the power of SQL in developing an efficient and scalable Loan Management System.

Key features include:

1. Dynamic customer categorization based on income.
2. Automated interest calculations using location-based rules.
3. Trigger-based automation for CIBIL score analysis and loan status updates.
4. Data cleaning and integration for seamless insights.
5. Comprehensive analytics through stored procedures and custom queries.

   
🚀 Features

Customer Income Categorization: Classifies customers into Grade A, Grade B, Middle Class, or Low Class based on income levels.

Interest Rate Calculation: Dynamically calculates monthly and annual interest amounts based on income and location.

Automated Triggers:
Updates loan status automatically for null amounts.
Classifies customers based on their CIBIL score.

Data Cleaning:
Removes invalid or irrelevant customer records (e.g., "Rejected Customers").
Ensures accurate loan amounts using data type conversions.
Data Integration: Combines data from five different datasets into a unified view using SQL joins.

Analytics:
Detects mismatched records using left joins.
Filters high CIBIL score customers and specific customer types.
Provides insights through stored procedures.

🛠️ Tech Stack
Database: SQL (MySQL)
Tools: MySQL Workbench
Programming Concepts: SQL Joins, Triggers, Stored Procedures, Case Statements


📂 Database Structure
Tables:
Customer Income Status

Contains customer income data and categorization criteria.
Loan Status

Tracks loan details, loan amounts, and CIBIL scores.
Customer Info

Stores demographic details like age, gender, and customer type.
Country State

Maps customers to their respective states and countries.
Region Info

Links states to broader regional information.

🏁 Conclusion
The Loan Management System demonstrates the potential of SQL in efficiently managing financial data.
It provides automated workflows, insightful analyses, and seamless integration of datasets, ensuring accuracy and informed decision-making.
