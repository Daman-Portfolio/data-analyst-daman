# Projects
Overview of the projects completed for BUSI 653: Cloud Computing Technologies. 
---

## Project 1: Exploratory Data Analysis (EDA)

### Project Title:

### 🔹 Objective:
To explore employee remuneration and expenses data from the City of Vancouver to identify trends, patterns, and insights related to department spending and employee compensation.

### 🔹 Dataset:
Sourced from the [City of Vancouver Open Data Portal](https://opendata.vancouver.ca), this dataset contains historical records of employee remuneration and expenses from 2016 to 2023.

### 🔹 Methodology:
- Data ingestion and cleaning using **AWS S3** and **Glue Databrew**
- Profiling and summarizing the dataset
- Analysis using **SQL in Athena** for identifying average expenses, minimum remuneration, and yearly trends
- Visualization with **QuickSight** and **Excel**

### 🔹 Tools & Technologies:
`AWS S3`, `Glue`, `Athena`, `SQL`, `Python`, `Excel`, `QuickSight`

### 🔹 Deliverables:
- Cleaned dataset in S3
- SQL queries for key business questions
- Summary graphs and interpretation of results

---

## 📈 Project 2: Descriptive Analysis

### 🔹 Project Title:
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

