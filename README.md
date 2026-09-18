SWYNEX – Data Cleaning & Preparation
📌 Project Overview
This project was completed as part of Task 1 of my SWYNEX internship**.
The objective of this task was to clean and prepare a raw retail sales dataset for further analysis by identifying and handling data-quality issues such as missing values, duplicate records, incorrect data types, and inconsistent values.

📊 Dataset
Dataset: Retail Store Sales – Dirty for Data Cleaning
Source: Kaggle
Tool Used: Microsoft Excel

The dataset contains retail transaction information including:
* Transaction ID
* Customer ID
* Category
* Item
* Price Per Unit
* Quantity
* Total Spent
* Payment Method
* Location
* Transaction Date
* Discount Applied

🔍 Data Quality Issues Identified
The raw dataset was inspected for the following issues:
1. Missing values
2. Duplicate records
3. Incorrect data types
4. Inconsistent values
5. Invalid or inconsistent transaction values
6. Extra spaces and formatting inconsistencies

🧹 Data Cleaning Performed
The dataset was cleaned using Microsoft Excel.
1. Missing Values
Missing values were identified using Excel filters and formulas.
Relevant fields were reviewed individually to determine the appropriate treatment for missing data.
 2. Duplicate Records
Duplicate transaction records were checked using Excel's Remove Duplicates feature.
3. Data Types
Columns were checked and converted to appropriate data types:
* Transaction ID / Customer ID → Text or numeric identifier
* Price Per Unit → Number
* Quantity → Number
* Total Spent → Number
* Transaction Date → Date
* Discount Applied → Consistent value format
4. Inconsistent Values
Inconsistent entries were identified and standardized to maintain consistency across categorical columns such as:
* Category
* Item
* Payment Method
* Location
5. Data Validation
Transaction values were reviewed for logical consistency, including checking the relationship between:
Quantity × Price Per Unit = Total Spent
Potential incorrect values were investigated and corrected where sufficient information was available.

✅ Final Result
After cleaning and validation, the dataset was prepared for further analysis.
The cleaned dataset can be used for:
* Exploratory Data Analysis
* Sales analysis
* Customer analysis
* Product analysis
* Visualization and reporting

🛠️ Tools & Skills Used
* Microsoft Excel
* Data Cleaning
* Data Validation
* Missing Value Handling
* Duplicate Detection
* Data Type Correction
* Data Standardization

📁 Project Files
Raw Dataset – [Raw Dataset](./Dataset/retail_store_sales.csv) – Original dataset obtained from Kaggle
Cleaned Dataset– [Cleaned Dataset](./Dataset/retail_store_sales_datacleaning.xlsx) – Dataset after data cleaning and validation

🎯 Key Learning
Through this task, I gained practical experience in identifying real-world data-quality problems and preparing raw data for reliable analysis.
