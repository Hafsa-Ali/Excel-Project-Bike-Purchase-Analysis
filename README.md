# Excel-Project-Bike-Purchase-Analysis
This project demonstrates my ability to clean, transform, and visualize data using Microsoft Excel. I created an interactive and beginner-friendly dashboard to analyze the "Bike Buyers" dataset. Below is an overview of the project and the steps involved.

What's Included:
- Bike Purchase Dataset
- Bike Purchase Dashboard: Contains 4 different sheets(dataset, working sheet, pivot table, and dashboard).

## Project Overview
Objective: Analyze the bike buyers dataset to uncover patterns and trends in purchase behaviors based on various demographics and present insights in an interactive dashboard.

#### Tools Used: Microsoft Excel

#### Key Features:
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
  This categorized individuals into Adolescent, Middle Age, and Old based on their age.

### 3. Pivot Table & Visualizations (Sheet: pivot table)
Utilized pivot tables to analyze trends and create the following charts:
1. Income vs Gender
   ![](https://github.com/Hafsa-Ali/Excel-Project-Bike-Purchase-Analysis/blob/main/chats/avg_salary.PNG)
2. Age vs Bike Purchase
   ![](https://github.com/Hafsa-Ali/Excel-Project-Bike-Purchase-Analysis/blob/main/chats/age_brackets.PNG)
3. Commute Distance vs Bike Purchase
   ![](https://github.com/Hafsa-Ali/Excel-Project-Bike-Purchase-Analysis/blob/main/chats/customer_commute.PNG)

### 4. Interactive Dashboard (Sheet: dashboard)
Compiled all charts into a simple, interactive dashboard:
- Included slicers for dynamic filtering.
- Designed for ease of use and interpretation.
  ![](https://github.com/Hafsa-Ali/Excel-Project-Bike-Purchase-Analysis/blob/main/chats/Dashboard.PNG)

## Key Insights
### 1.Average Salary per Purchase:
#### - Observation by Gender:
  - Males who purchased bikes have a higher average income than those who did not.
  - Similarly, females who purchased bikes earn slightly more than those who didn’t.
  - Overall, males have a higher income than females, regardless of the purchase decision.
### 2.Customer Age Brackets:
#### - Purchasing Trend by Age Group:
  - Middle-aged customers dominate the purchasing category compared to adolescents or older customers.
### 3.Commute Distance and Purchases:
#### - Purchase Likelihood by Commute Distance:
  - Highest Purchase Percentage: 2–5 Miles indicates a peak interest in bike purchasing for moderate-distance commutes.
  - Lowest Purchase Percentage: More than 10 Miles suggests that long commutes may deter bike purchases, possibly due to physical or time-related constraints.
