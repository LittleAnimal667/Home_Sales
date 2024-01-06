# Home Sales Analysis with SparkSQL
## Overview

This project demonstrates the effective use of SparkSQL to derive key metrics from home sales data. The tasks encompass creating temporary views, partitioning data, caching and uncaching a temporary table, and verifying the uncaching process.

## Process 

To kick off the Home Sales Analysis project, a new repository named Home_Sales was created, and the provided files from [Module 22 Challenge](https://static.bc-edx.com/data/dl-1-2/m22/lms/starter/Starter_Code.zip) were downloaded. The project's main notebook, initially named Home_Sales_starter_code.ipynb, was renamed to Home_Sales.ipynb for clarity. PySpark SQL functions were imported, and the home sales data from home_sales_revised.csv was read into a Spark DataFrame.

Following this, a temporary table named home_sales was successfully created. Key questions were then addressed using SparkSQL queries, including computing the average price for various house configurations and determining the "view" rating for homes exceeding $350,000. Subsequently, caching of the temporary table was implemented for enhanced query performance. The caching status was verified, and the specified queries were rerun on the cached data, comparing the runtime with the uncached scenario. Additionally, the home sales dataset was partitioned by the "date_built" field, creating a formatted parquet dataset. A temporary table for the parquet data was established, and the specified query was executed, comparing the runtime with the uncached scenario. Finally, the home_sales temporary table was uncached, and the uncaching process was verified. The project's notebook, Home_Sales.ipynb, was then downloaded and uploaded to the "Home_Sales" GitHub repository for submission.
