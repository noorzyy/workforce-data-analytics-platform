# Initial struture 
<br>
First deployment system requirements. <br>
<br>

- This is subjected to change in the future iterations. <br>
- Just the first initial draft of the project structure. <br>
- Used for transforming raw workforce data into actionable insights that help organizations make better decisions

<br>


# Data folder: raw datasets (important for data pipelines, transformation and visualization)

1. employees.csv: contains employee demographic info (name/department/hire date/role etc) <br>

2. salaries.csv: employee salaries/pay grade or pay band over time <br>

3. performance.csv: metric performances and scores over time. <br>

4. attendance.csv: tracks absenses/worklog hours/vacation time/holidays requested 

<br>


# Scripts folder: (data engineering + analytics + +automation + file handling) 

1. data_cleaning.py: this is a python script that would be used for cleaning and merging the pre-processed raw csv data. Exception handling/missing values/format columns and consistency <br> 


2. upload_to_azure.ps1: this is a powershell script for uploading clean datasets/SQL backups to azure blob storage. <br> 


3. linux_automation.sh: bash scripts for running data backup/system maintenance tasks in linux environment 
(later iterations could include the windows/mac scripts as well.)<br>


4. anaysis_notebook.ipynb: Jupyter notebook for data analysis and statistical modelling (correlations/descriptive statistics etc.) <br> 


5. spark_processing.ipynb: Big data processing with pyspark/databricks for scalability <br>

<br> 

# SQL layer (database modeling + SQL)
<br>

1. create_tables.sql: SQL commands for defining the database (tables for employees/salaries/performance) <br>
<br>

2. queries.sql: Analytical SQL queries, for extracting top performer, salary trends, department averages <br>
views.sql: virtual tables for visualization and dashboard connections <br>

<br>

# Dashboard (presentation + output layer)
<br>

1. workforce_dashboard.pbix: PowerBI dashboard for visualizing Key performance indicators. <br>

2. Excel_dashboard.xlsx: Excel based dashboard for showing the data/summaries/charts. <br>

<br>

# README

<br>

1. Explains the project
2. How to set it up
3. Tools and technologies used
4. Things that I learned
5. Challenges that I encountered
6. Contact 

