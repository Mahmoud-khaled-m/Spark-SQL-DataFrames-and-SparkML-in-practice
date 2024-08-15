# SparkSQL, DataFrames, and SparkML in practice
This repository showcases practical examples and projects using Apache Spark's SQL, DataFrames and SparkML APIs. It demonstrates various data processing, analysis, and transformation techniques using PySpark.

## Overview

These projects were created to gain hands-on experience with Spark, focusing on:
* Data manipulation using Spark DataFrames
* Complex queries and data analysis with Spark SQL
* ETL (Extract, Transform, Load) processes

## Project1: SparkDFs
  This practice project focuses on data transformation and integration using PySpark. You will work with two datasets, and perform various transformations such as adding columns, renaming columns, dropping       unnecessary columns, joining dataframes, and finally, writing the results into a Hive warehouse and an HDFS file system.
### Scenario
  You have been hired as a Junior Data Engineer by BDPS Corporation and you have been provided with links to two raw datasets that you need to acquire and perform ETL on using PySpark and Hive warehouse.


## Project2: SparkSQL
  This project focuses on mastering Spark SQL, a powerful component of Apache Spark that allows you to work with structured data using SQL-like queries. You will create a DataFrame from a CSV file, define a schema for the data, and leverage Spark SQL to perform transformations and actions on the data.
### Scenario 
  You have been tasked by the HR department of a company to create a data pipeline that can take in employee data in a CSV format. Your responsibilities include analyzing the data, applying any required transformations, and facilitating the extraction of valuable insights from the processed data.
  Given your role as a data engineer, you've been requested to leverage Apache Spark components to accomplish the tasks.

## SparkML:
  ### Practice Project:
  In this project you will create an end-to-end solution using machine learning pipelines for regression. Your objective is to clean the dataset, create a model that predicts the SoundLevel based on the other columns, evaluate its performance, and persist the model for future use.

  #### This project has four parts, each building on the previous one. 

  * In part one, you will perform ETL activities, including loading the CSV dataset, removing duplicate rows, if any, dropping rows with null values, applying necessary transformations, and storing the cleaned data in the parquet format. 

  * Moving on to part two, you will create a machine learning pipeline with three stages, including a regression stage. This pipeline will be the backbone of your model development, enabling you to process the data and train a predictive model efficiently. 

  * Once you’ve trained the model, you will proceed to part three to evaluate its performance using relevant metrics. This step is crucial in understanding how well your model predicts SoundLevel and identifying areas for improvement. 

  * Finally, in part four, you will persist the model, allowing you to load and utilize it in real-world applications when predicting new data. As the final step, you will load and verify the stored model to ensure its integrity and usability in future tasks or deployments.


  ### Final Project - Build an ML Pipeline for Airfoil noise prediction:
  In this project, you will work with the modified version of the NASA Airfoil Self Noise dataset. The goal is to clean the dataset, create a Machine Learning pipeline, evaluate the model's performance, and persist it for future use. 

  You will begin by cleaning the dataset and removing duplicate rows and rows with null values. Doing this step ensures the data is consistent and reliable for further analysis. Next, you will construct a Machine Learning pipeline with three stages, including a regression stage. This pipeline will enable you to build a model that predicts the SoundLevel based on other columns in the dataset. Once you’ve trained the model, you will evaluate its performance using appropriate metrics to assess its accuracy and effectiveness. Finally, you will persist with the model, saving it for future use. This step ensures that the trained model can be stored and retrieved later, enabling its deployment in real-world applications and making predictions on new data. 

  There are four parts to this project. In part one, you will perform ETL activities, including loading the CSV dataset, cleaning it, applying transformations, and storing the cleaned data in the parquet format. Part two involves creating the Machine Learning pipeline, which forms the backbone of your model development. In part three, you will evaluate the model using relevant metrics to gain insights into its performance. Finally, in part four, you will save the model for future production use and verify its successful loading. 
  
