# 📊 Project: Sales Data Cleaning and Standardization Using SQL

## 🔍 Overview  
This project leverages SQL to clean and standardize a messy raw sales dataset, enabling accurate and consistent data analysis. The dataset contained inconsistent city names, item descriptions, payment methods, customer feedback, and quantity values, along with duplicates and formatting irregularities.

## 🛠️ Key SQL Techniques and Functions Used  
- **CASE Statements:** Applied conditional logic to standardize text fields such as city names, item categories, payment methods, and customer feedback.  
- **String Functions:** Used functions like `LOWER()`, `UPPER()`, `TRIM()`, `LEFT()`, and `SUBSTRING()` to normalize text formatting, including customer names and categorical fields.  
- **Window Functions:** Utilized `ROW_NUMBER()` with `PARTITION BY` to identify and remove duplicate records effectively based on customer ID, name, purchase date, and item.  
- **Date Functions:** Converted string dates to proper date formats using `STR_TO_DATE()` for consistent date handling.  
- **Null Handling:** Managed missing or empty values in payment methods and other fields by applying `CASE` logic for accurate categorization.

## 🚀 Impact  
By using SQL for comprehensive data cleaning and transformation, the resulting standardized dataset ensures data integrity and minimizes errors in downstream analysis. This enables reliable insights into sales trends, customer behavior, and payment preferences, forming a robust foundation for advanced analytics and strategic decision-making.

## You can find all SQL queries related to this project in the [sales_data_cleaning_sql](https://github.com/Pranshul-cloud/data_cleaning.sql/blob/main/sales_data_cleaning.sql) folder.
