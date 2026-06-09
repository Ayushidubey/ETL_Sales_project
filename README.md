# Sales Data Processing | ETL Project using Python


## Introduction

This project demonstrates an end-to-end ETL pipeline using Python, where sales data is extracted from multiple sources like CSV, JSON, Parquet, and SQL. The data is then transformed and cleaned before being loaded into a structured database for analysis.

## Architecture

      Multiple Data Sources 
      (csv,json,parquet,sql)
               |
               ▼
        🔹 Extract Layer
        (pandas, sqlite3)
               |
               ▼
        🔹 Transform Layer
         (cleaning, type fixing,
         feature creation likerev_per_unit)
               |
               ▼
        🔹 Load Layer
          (SQLite Database)
               |
               ▼
        🔹 Analysis / Visualization
         (pandas, matplotlib)

  ## Tools Used 
  1.Python
  
  2.Pandas
  
  3.Jupyter Notebook

  ## Dataset Used
  Dataset not included in this repository.
  please use your own sample data.

  ## Script for Project
  [Sales project](ETL_Sales_project/Sales_ETL_Proj_Python.ipynb)
  
  
