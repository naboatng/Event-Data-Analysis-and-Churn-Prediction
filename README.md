## Overview
- This project provides a data pipeline for loading, processing, and analyzing user event data from Excel files, storing them in a PostgreSQL database, and building machine learning models to predict user churn.   
A Flask web interface enables file uploads and result downloads.


## Key Objectives:  
- Load and preprocess event data.
  
- Store data in PostgreSQL.
  
- Perform exploratory data analysis and cohort analysis.
  
- Train a RandomForest classifier to predict user churn.
 
- Serve an API endpoint for file uploads and downloading results.
 



## Features  
- File Processing: Load data from Excel, preprocess it, and log results.
  
- Database Integration: Insert data into PostgreSQL, handle retries, and create tables if needed.
   
- Machine Learning Pipeline: Train a RandomForest classifier to predict churn based on event data.
  
- Cohort Analysis: Identify user activity over time, grouping by cohorts.
  
- Flask API for File Uploads: Upload Excel files via a Flask web app and export results.
  
