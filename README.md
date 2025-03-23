# Projects
Overview of the projects completed for BUSI 653: Cloud Computing Technologies. 
---
## Project 1: Exploratory Data Analysis (EDA)
### Project Title: Implementation of DAP to support the requirement of the City of Vancouver
### Objective:
Exploratory Data Analysis for Vancouver City aim to analyse employee remuneration and expenses for HR Department employees according to different titles. 
### Dataset:
Extracted from the [City of Vancouver Open Data Portal](https://opendata.vancouver.ca), this dataset contains historical records of employee remuneration and expenses from 2016 to 2023 with details such as:
- Year : 2016 to 2023
- Name : Name of the employees in various Titles
- Department: Human Resource
- Title: All the different Titiles under HR Depeartment
- Remuneration: Yearly remuneration for each employee
- Expense: Yearly expense of each employee
###  Methodology:
- Data Ingestion: uploading 
- Profiling and summarizing the dataset
- Analysis using **SQL in Athena** for identifying average expenses, minimum remuneration, and yearly trends
- Visualization with **QuickSight** and **Excel**

###  Tools & Technologies:
1. Amazon S3 as a data lake for storage of raw, curated, and transformed buckets
2. AWS EC2 to access remote PC to injest files in S3 bucket using PowerShell
3. AWS Glude DataBrew for cataloging, cleaning, profiling, and transformation. 
4. AWS Athena to perform SQL queries for Business Questions.

###  Deliverables:
- Cleaned dataset in S3
- SQL queries for key business questions
- Summary graphs and interpretation of results

---

##  Project 2: Descriptive Analysis

###  Project Title:
**Descriptive Analysis of City Remuneration Data**

### 🔹 Objective:
To provide summarized statistics (mean, minimum, trends) and compare those with visual outputs to verify the accuracy of ETL processes.

### 🔹 Dataset:
Employee remuneration and expenses dataset from the City of Vancouver (same dataset as EDA, used for deeper summarization).

### 🔹 Methodology:
- ETL pipeline built using **AWS Glue Studio**
- Aggregations performed on yearly expenses and remuneration
- Output stored in **CSV** and **Parquet** format in S3
- Visualizations developed for reporting purposes
- Matched output to summary graphs for data validation

### 🔹 Tools & Technologies:
`AWS Glue`, `S3`, `Athena`, `CloudWatch`, `Python`

### 🔹 Deliverables:
- ETL pipeline in Glue
- Transformed dataset in metrics folder
- Summary graphs matching ETL output
- Final insights documented

