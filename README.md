# Projects
Overview of the projects completed for BUSI 653: Cloud Computing Technologies. 
---
## Project 1: Exploratory Data Analysis (EDA)

### Project Title: 
**Implementation of DAP for EDA of the City of Vancouver**
![Data Analytics Platform Diagram](https://github.com/Daman-Portfolio/data-analyst-daman/blob/main/Descriptive.png)
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
- Loading data from S3 to Athena
- Writing SQL Rules
- Business questions answer: avg(expense), min(remuneration), expnse and remuneration relationship over the years. 
###  Tools & Technologies:
- AWS S3 storage to load data and output
- Used AWS Athena for SQL queries 
- Rules set to answer business questions
###  Deliverables:
- SQL queries
- Output saved in S3 curated bucket
---

##  Project 2: Descriptive Analysis
###  Project Title:
**Implementation of DAP for Descriptive Analysis of Vancouver City**
![Descriptive Analysis Tools](https://github.com/Daman-Portfolio/data-analyst-daman/blob/main/Descriptive.png) 
### Objective:
The Descriptive Analysis consists of examining the trends and metrics for Vancouver City's HR Department based on remuneration and expenses.
### Dataset:
Extracted from the [City of Vancouver Open Data Portal](https://opendata.vancouver.ca), this dataset contains historical records of employee remuneration and expenses from 2016 to 2023 with details such as:
- Year : 2016 to 2023
- Name : Name of the employees in various Titles
- Department: Human Resource
- Title: All the different Titiles under HR Depeartment
- Remuneration: Yearly remuneration for each employee
- Expense: Yearly expense of each employee
### Methodology:
- Data ingestion
- Data profiling
- Data cleaning
- Data cataloging
- Data summarization
### Tools & Technologies:
- S3 bucket to stored raw data
- Amazon EC2 to ingest data using PowerShell command
- AWS Glue DataBrew for examining the dataset
- Data cleaning by working with data problems such as encoding, missing values, null values
- Data cataloging using AWS Crawlwer
- ETL jobs to filter, group, summarize
### Deliverables:
- Ingested dataset
- Successful profiling job
- Cleaned data stored in two formats (CSV and Paraquet)
- Data Catagloing
- Cleaned data set grouped by year according to titles
---

##  Project 3: Data Wrangling
###  Project Title:
**Data Enriching for Substance use policy at University Canada West**
![Data Wrangling Platform](https://github.com/Daman-Portfolio/data-analyst-daman/blob/main/Data%20Wrangling.png) 
### Objective:
The main objective is to clean raw dataset gathered as it is  of poor quality, has data issues, and needs to be fixed for reliable analysis. 
### Dataset:
Extracted from [University Canada West repository](https://wpvip.guscancolleges.ca/ucanwest/wp-content/uploads/sites/3/2022/08/UCW-8006-Substance-Use-Policy.pdf)  

- Policy Number: 8006
- Policy Title: Substance Use
- Approved by: President
- Approval date: August, 2020
- Effective date: August 30, 2020
- Next review date: June 2025
### Methodology:
- Analysing the policy for proper representation as a tabular format
- Identifying Key and non key fields
- Data ingestion of policy 8006 after converting it to a tabular format
- Cleaning and profiling
- Transforming and enrichment
- Cataloging using Crawler  
### Tools & Technologies:
- EC2 instances for virtual operational environment
- Powershell to injest files to S3 buckets
- S3 raw buckets for storing data
- AWS Glude Databrew for profiling
- AWS Glue using Visual ETL to filter and joining  datasets
- AWS Glude DataCatalog for transformed dataset
### Deliverables:
- Transformed data stored as user friendly and system friendly output
- Cataloged tables with corrected schemas
- Cleaning and structuring completed

##  Project 4: Diagnostic Analysis 
###  Project Title:
**Data Enriching for Substance use policy at University Canada West**
![Descriptive Data Analysis](Descriptive%20Data%20Analysis.png) 
### Objective:
The main objective is to clean raw dataset gathered as it is  of poor quality, has data issues, and needs to be fixed for reliable analysis. 
### Dataset:
Extracted from [University Canada West repository](https://wpvip.guscancolleges.ca/ucanwest/wp-content/uploads/sites/3/2022/08/UCW-8006-Substance-Use-Policy.pdf)  

- Policy Number: 8006
- Policy Title: Substance Use
- Approved by: President
- Approval date: August, 2020
- Effective date: August 30, 2020
- Next review date: June 2025
### Methodology:
- Analysing the policy for proper representation as a tabular format
- Identifying Key and non key fields
- Data ingestion of policy 8006 after converting it to a tabular format
- Cleaning and profiling
- Transforming and enrichment
- Cataloging using Crawler  
### Tools & Technologies:
- EC2 instances for virtual operational environment
- Powershell to injest files to S3 buckets
- S3 raw buckets for storing data
- AWS Glude Databrew for profiling
- AWS Glue using Visual ETL to filter and joining  datasets
- AWS Glude DataCatalog for transformed dataset
### Deliverables:
- Transformed data stored as user friendly and system friendly output
- Cataloged tables with corrected schemas
- Cleaning and structuring completed

