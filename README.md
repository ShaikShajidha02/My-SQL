**#Zepto SQL Data Analysis Project**

This project contains SQL-based data analysis performed on a Zepto dataset. The goal of this project is to explore, clean, and analyze product-level data to extract meaningful business insights.

**Project Structure**
* Zepto-SQL-Project
* Zepto SQL project.sql     
* zepto_v2.csv              
* README.md                 

**Dataset Information**

File: zepto_v2.csv

The dataset contains product-level information from Zepto, including details such as:
* Product name
* Category
* Sub-category
* Brand
* Price
* Discount
* Rating
* Stock availability
* Other relevant attributes
  
The dataset is used for performing SQL-based exploratory data analysis (EDA).

**Technologies Used**

* SQL (MySQL / PostgreSQL compatible queries)
* CSV dataset
* Any SQL client (MySQL Workbench / pgAdmin / DBeaver / etc.)

**Project Objectives**

The SQL queries in Zepto SQL project.sql are designed to:
* Perform data cleaning
* Analyze pricing and discount patterns
* Identify top-rated products
* Find best-selling or high-stock items
* Category-wise product analysis
* Extract business insights from structured data

**Data Cleaning Steps**

Some common cleaning operations performed:
* Handling NULL values
* Removing duplicate records
* Standardizing column formats
* Converting data types where necessary

**Key Analysis Performed**

Examples of insights generated:
* Average price by category
* Top discounted products
* Highest-rated products
* Brand-wise product distribution
* Price range segmentation
* Stock availability insights

**How to Use This Project**

1️⃣ Import Dataset into SQL

Create a table and import zepto_v2.csv into your database.
Example (MySQL):

CREATE TABLE zepto (
    column1 datatype,
    column2 datatype,
    ...
);

Then import the CSV file using your SQL client.

2️⃣ Run SQL Queries

Open:
Zepto SQL project.sql
Execute the queries step by step to reproduce the analysis.

**Skills Demonstrated**

* SQL querying
* Data cleaning
* Aggregations & Grouping
* Subqueries
* Joins (if applicable)
* Business data interpretation
* Analytical thinking

**Conclusion**

This project uses SQL to analyze the Zepto dataset and extract useful business insights. Through data cleaning and structured queries, we explored product prices, discounts, ratings, brands, and stock availability.
The analysis helped identify pricing trends, top-rated products, and category-wise patterns. Overall, this project demonstrates practical SQL skills and shows how data can be used to support better business decisions.
