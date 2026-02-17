# DB2-LUW-Retail-Banking-Analytics-System
This project demonstrates end-to-end database design and analytical querying using IBM Db2 LUW.

The system simulates a retail banking environment where customer accounts and transactions are stored, processed, audited, and analyzed for business insights.

#The primary objective of this project is to showcase:

Strong SQL expertise
Analytical thinking
Relational data modeling
SQL PL procedural programming
Performance optimization awareness
Reporting layer development

This project is designed to reflect the practical skills required for a Data Analyst working with enterprise-grade relational databases.

#Database Architecture
The database consists of the following core entities:

CUSTOMERS
Stores customer profile information.

ACCOUNTS
Stores banking account details linked to customers.

TRANSACTIONS
Stores all financial activity (deposits and withdrawals).

ACCOUNT_AUDIT
Tracks balance changes for auditing and governance.

#The schema follows proper normalization principles with:

Identity columns
Primary & foreign key constraints

Data integrity enforcement
Timestamp tracking

#Technical Features Implemented
Data Modeling
Designed normalized relational schema
Implemented referential integrity using foreign keys
Used identity columns for surrogate keys

SQL Programming
Developed SQL PL stored procedure for fund transfer
Implemented business rule validation (insufficient balance logic)
Created trigger-based audit mechanism

Analytical Queries
Aggregation queries (SUM, COUNT)
Multi-table joins
Ranking and top-N analysis
Monthly trend analysis using date functions
Inactive account detection

Reporting Layer
Created analytical views for simplified reporting
Developed reusable summary view for customer-level metrics

Performance Optimization
Created index on high-frequency filter column
Executed RUNSTATS to update optimizer statistics
Structured queries with performance awareness

#Business Questions Answered
This project answers real-world business questions such as:

Who are the top 5 high-value customers?
What is the monthly transaction trend?
Which accounts are inactive?

These queries simulate real analytical use cases found in financial reporting environments.

# Project Structure
01_Database_Setup.sql
02_Create_Tables.sql
03_Insert_Data.sql
04_Stored_Procedure.sql
05_Trigger.sql
06_Views.sql
07_Analytical_Queries.sql
08_Performance_Optimization.sql


Scripts are organized in execution order for clarity and maintainability.

Testing & Validation
The system includes:

Sample dataset insertion
Stored procedure execution testing
Validation queries to verify results
Audit trail verification
This ensures data integrity and logical correctness.

#Tools & Technologies
IBM Db2 LUW
SQL PL
Relational Database Concepts
Query Optimization Techniques

#Skills Demonstrated
Advanced SQL querying
Analytical problem solving
Database schema design
Performance tuning fundamentals
Data validation and governance
Enterprise-level database understanding

Why This Project Matters
Modern Data Analysts must understand:
How data is structured
How business logic is enforced
How queries impact performance
How to extract insights efficiently


#Author
Habiba Anjum
