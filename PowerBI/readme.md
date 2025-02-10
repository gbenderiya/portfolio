📌 About the Data
This dataset tracks BI Platform Performance Logs, capturing system activity, user interactions, and error occurrences to monitor platform health and efficiency. It includes key performance indicators (KPIs) such as user activity, query execution time, system resource utilization, and error rates.

This dataset contains a CSV table with 50,000+ records, each representing an individual system event.

💡 Highlights

User Activity Trends: Peak system usage hours identified through login and report access patterns.
Error Rate Analysis: Average error rate per user action, helping to detect platform stability issues.
Performance Monitoring: Query execution times and system resource (CPU & Memory) consumption trends.
Departmental Impact: Analysis of BI platform usage by different departments to optimize resource allocation.

✏️ Data Wrangling
Performed data preprocessing and transformation:

Removed duplicate and missing values.
Converted Query_Time_ms, CPU_Usage, and Memory_Usage to numerical formats.
Categorized Action_Type for better filtering and aggregation.
Merged user details from the User Lookup Table to enrich analysis.
📍 Jupyter Script: BI_Performance_Cleaning.ipynb
📍 Clean Data: BI_Performance_Logs_Clean.csv

📊 Visualization
PowerBI
![image](https://github.com/user-attachments/assets/b40e3110-b201-4b45-8751-a2a6fdc88bf6)


