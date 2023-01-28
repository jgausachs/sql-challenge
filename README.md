# SQL-challenge
Submission for Challenge 9 - SQL

## Data Modelling
Submission of the Entity Relationship Diagram is stored in folder 'sql-challenge/EmployeeSQL/':  
- File 'ERD_clip_v3.png':  
  contains a clip of the logic diagram as generated with QuickDBD
- File 'ERD_code_v3.txtERD_code_v3.txt':  
  contains the code used to generate the diagram  
  
Note: we model serial keys for tables 'dept_emp' and 'dept_manager' in the ERD; whereas the final implmentation was instead done with composite keys for those tables.

## Data Engineering
Submission is stored in folder 'sql-challenge/EmployeeSQL/':  
- File 'employees_schema.sql':  
  contains the table schema and code used to create the tables per the ERD (using PostgreSQL); code is included to create the primary composite keys for the tables 'dept_emp' and 'dept_manager'  
  
Note: the data was uploaded from the .csv files contained in the '/data' folder using the import function in pgAdmin4.
  
## Data Analysis
Submission is stored in folder 'sql-challenge/EmployeeSQL/':  
- File 'employees_queries.sql':  
  contains the code to run each query (using PostgreSQL) as outlined in the data analysis section of the challenge (duly labelled).
