# Road-to-Data-Engineer-2.0

Data engineering Bootcamp with 'admin Pertg.' and 'admin Fon.' - **[DataTH](https://school.datath.com/)**

We learned 7 chapters during the 2-month intensive program. These are the projects/homework I have done in `DataTH` Bootcamp.

## CH 0 Intro to Data Engineering
พื้นฐานเกี่ยวกับงานของ Data Engineer
พื้นฐานการเขียน SQL และ Python
  
## CH 1 Data Collection & Workshop 1 
เรียนรู้การสร้าง database ที่ sqlfiddle.com 
การดึงข้อมูลจากแหล่งข้อมูลต่าง ๆ เช่น REST API ด้วย Pandas 
### Workshop 1: Data Collection with Python (Google Colab)
1. Import data from the database (MYSQL_HOST = x.x.x.x) 
2. Convert to pandas 
3. get data from 'REST API' by package 'requests' 
4. input URL 
5. Convert to pandas 
6. Join the data 
7. Export to CSV file
    
## CH 2 Data Cleansing & Workshop 2 
การทำความสะอาดข้อมูล ด้วย Apache Spark 
### Workshop 2: Data Cleansing with Spark (Google Colab)
1. Load data (CSV file) from the URL 
2. Data Profiling
    1. Check missing value
3. EDA - Exploratory Data Analysis
    1. Non-Graphical EDA
    2. Graphical EDA
4. Data Cleansing with Spark
    1. Transform Data Type
    2. Anomalies Check
       1. Syntactical Anomalies 
       2. Semantic Anomalies 
       3. Missing values 
       4. Outliers

    Clean ข้อมูลด้วย Spark SQL
   1. Transform Spark DataFrame to TempView or GlobalTempView
   2. Use SQL query or transform on TempView
6. Save data to CSV

## CH 3 Basic Cloud & Workshop 3
การใช้ Google Cloud สร้าง Data Lake แบบเบื้องต้น
### Workshop 3: Upload to Data Lake (Google Cloud Storage)
1. Apply to Google Cloud member
2. Create a project on Google Cloud Platform(GCP)
3. Create a bucket on GCP methods
     + Cloud Console on Web-UI
     + gsutil command via Cloud shell
4. Upload data to Google Cloud Storage(GCS) methods
    + Cloud Console on Web-UI
    + gsutil command via Cloud shell
    + Python SDK library
## CH 4 Data Pipeline Orchestration & Workshop 4
การสร้าง Data Pipeline ที่ทำงานอัตโนมัติ ด้วย Apache Airflow
### Workshop 4: Automated Data Pipeline with Airflow (Cloud Composer)
1. Create a Cloud Composer cluster
2. Install Python packages in Airflow
3. Upload taskflow*.py to GCS in the dags folder
#### Exercise 1: Simple Pipeline
#### Exercise 2: Fan-out Pipeline
#### Exercise 3: Fan-in Pipeline
4. Create a MySQL connection on Airflow to Database
#### Exercise 4: Final Pipeline
- Read data from the Database
- Read API as CSV
- Merge data and save to [Bucket]/data folder.
  
## CH 5 Data Warehouse & Workshop 5
การใช้ Google BigQuery สร้าง Data Warehouse
### Workshop 5: Data Warehouse with BigQuery
1. Create a Dataset and a table on BigQuery
2. Import data to BigQuery methods
    1. Cloud Console (Web UI)
    2. bq command by BashOperator on Airflow
    3. GCSToBigQueryOperator
3. Explore data on BigQuery by SQL

## CH 6 Data Visualization & Workshop 6
การใช้ Google Data Studio (Looker Studio) สร้าง Dashboard
### Workshop 6: Data Visualization with Google Data Studio (Looker Studio)
1. Create a View from the table in BigQuery(Workshop 5)
     + Selected columns to show
3. Create Dashboard
     1. Overview
          + Revenue
          + Number of Customers
          + Number of sales
          + Book best seller
          + Catagories best seller
     2. Search book by revenue
          + Parameter
          + Calculated field

## CH 7 Advanced Data Engineering
ความรู้เพิ่มเติมที่ Data Engineer สมัยใหม่ต้องรู้ เช่น Databricks, Delta Lake
