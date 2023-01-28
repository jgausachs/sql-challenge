# SQL-challenge
Submission for Challenge 9 - SQL

## Data Modelling
Submission of the Entity Relationship Diagram can be found under folder 'sql-challenge/EmployeeSQL/':  
- File 'ERD_clip_v3.png':  
  contains a clip of the logic diagram as generated with QuickDBD
- File 'ERD_code_v3.txtERD_code_v3.txt':  
  contains the code used to generate the diagram  
  
Note: we assumed serial keys for tables 'dept_emp' and 'dept_manager' in the ERD model; whereas for the final implmentation we created composite keys for those tables instead.

## Data Engineering
Submission can be found under folder 'sql-challenge/EmployeeSQL/':  
- File 'employees_schema.sql':  
  contains the table schema and code used to create the tables per the ERD (using PostgreSQL); code is included to create the primary composite keys for the tables 'dept_emp' and 'dept_manager'  
  
Note: the data was uploaded from the .csv files contained in the '/data' folder using the import function of pgAdmin4.
  
## Data Analysis
Submission can be found under folder 'sql-challenge/EmployeeSQL/':  
- File 'employees_queries.sql': 
  contains the code to run each query (using PostgreSQL) as outlined ib the data analysis section of the challenge (duly labelled).
