# 📊 Project: Sales Data Cleaning and Standardization

## 🔍 Overview  
This project focuses on cleaning and standardizing a messy raw sales dataset to enable accurate and consistent analysis. The raw data contained inconsistent city names, item descriptions, payment methods, customer feedback, and quantity values, along with duplicates and formatting issues.

## 🛠️ Key Tasks Performed  
- **Standardized Text Fields:** Cleaned variations in city names, item categories, payment methods, and customer feedback using conditional logic and string manipulation for consistency.  
- **Formatted Quantitative Data:** Converted text-based quantity values to numeric format for reliable aggregation.  
- **Normalized Customer Names:** Applied uniform capitalization to customer names for consistency across records.  
- **Removed Duplicates:** Identified and filtered out duplicate transactions using ROW_NUMBER() window function based on customer ID, name, purchase date, and item.  
- **Consolidated Clean Data:** Created a final, deduplicated table with all standardized fields for easy consumption by downstream analytics and reporting.

## 🚀 Impact  
This standardized and clean dataset ensures data integrity, reduces errors in analysis, and facilitates meaningful business insights on sales trends, customer behavior, and payment preferences. It lays a strong foundation for advanced analytics, forecasting, and strategic decision-making.
