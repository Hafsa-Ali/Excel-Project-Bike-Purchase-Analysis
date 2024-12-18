# Excel-Project-Bike-Purchase-Analysis
This project demonstrates my ability to clean, transform, and visualize data using Microsoft Excel. I created an interactive and beginner-friendly dashboard to analyze the "Bike Buyers" dataset. Below is an overview of the project and the steps involved.

What's Included:
- Bike Purchase Dataset
- Bike Purchase Dashboard: Contains 4 different sheets(dataset, working sheet, pivot table, and dashboard).

## Project Overview##
Objective: Analyze the bike buyers dataset to uncover patterns and trends in purchase behaviors based on various demographics and present insights in an interactive dashboard.

### Tools Used: Microsoft Excel

### Key Features:
- Data cleaning and transformation.
- Creation of pivot tables and charts for analysis.
- Interactive dashboard with slicers.

## Steps Involved

### 1. Dataset Preparation (Sheet: bike_buyers(dataset))
The dataset contains information about bike buyers, including age, gender, marital status, commute distance, and income levels.

### 2. Data Cleaning & Transformation (Sheet: working sheet)
Key steps taken:   
- **Removed Duplicates:** Ensured data integrity by eliminating duplicate rows.
- **[Gender] Column Transformation:** Replaced "M" and "F" with "Male" and "Female."
- **[Marital Status] Transformation:** Replaced "M" and "S" with "Married" and "Single."
- **New Column - [Age Brackets]:** Created an Age Brackets column using the following formula:
  ```sql
      =IF(L2>55, "Old", IF(L2>=31, "Middle Age", IF(L2<31, "Adolescent", "Invalid")))
     ```
