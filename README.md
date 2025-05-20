# nyc-taxi-sql-analytics
# 🚕 FareSight: NYC Taxi Analytics Using SQL and Databricks

A batch data analytics project using **NYC Yellow Taxi data** on **Databricks Community Edition**, focused on showcasing **SQL skills (basic to advanced)** and **Python-based data visualization**.

---

## 📊 Project Highlights

- Batch processing of real-world taxi trip data (Parquet format)
- Creation of Delta Lake table for structured SQL analysis
- Advanced SQL queries using:
  - `GROUP BY`, `ORDER BY`
  - Window functions (`RANK()`, `SUM() OVER`)
  - Aggregations (daily trips, revenue, average fares)
- Visual insights using Python (`matplotlib`, `seaborn`)
- Executed entirely on **Databricks Community Edition (free tier)**

---

## 🛠️ Tech Stack

- **Platform**: Databricks Community Edition  
- **Language**: SQL, Python (Pandas, Matplotlib, Seaborn)  
- **Data Source**: NYC Yellow Taxi Parquet Dataset  
- **Storage Format**: Delta Lake  

---

## 📁 Data Used

- **File**: `yellow_tripdata_2023-01.parquet`  
- **Source**: [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
- Uploaded to Databricks: `/FileStore/taxi/yellow_tripdata_2023-01.parquet`

---

## 🔍 SQL Use Cases

1. 📅 Total Trips Per Day  
2. 💳 Average Fare by Payment Type  
3. 📈 Running Total of Trips  
4. 💰 Top 5 Revenue Days (with Window Function + Ranking)

---


## 🚀 How to Run

1. Login to [Databricks Community Edition](https://community.cloud.databricks.com/)
2. Upload the Parquet file to `/FileStore/taxi/`
3. Run the notebook step by step:
    - Load and explore the data
    - Create Delta table
    - Perform SQL analysis
    - Generate visualizations in Python

---

## 📂 Project Assets

- 📓 Jupyter/Databricks notebook included
- 📦 SQL and visualization code

---

## 👩‍💻 About Me

I'm **Aishwarya Deshmukh**, a data engineer passionate about working with real-world datasets, cloud platforms, and scalable SQL analytics.

This project highlights my ability to work with batch data processing, build reusable SQL models, and create clear visual insights.

---



## 📬 Connect with Me

- 💼 [LinkedIn](https://www.linkedin.com/in/aishwarya-deshmukh-543704154) 
- 🧠 [GitHub Profile](https://github.com/AishwaryaSolunke))
