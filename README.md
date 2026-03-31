##  Customer Shopping Behavior Analysis

##  Project Overview

This project focuses on analyzing customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The objective is to uncover insights into:

Customer spending patterns
Product preferences
Subscription behavior
Customer segmentation

These insights help businesses make data-driven decisions to improve marketing strategies, customer retention, and revenue growth.

##  Dataset Summary

Total Records: 3,900
Total Features: 18

##  Key Attributes

Customer Demographics

Age
Gender
Location
Subscription Status

Purchase Details

Item Purchased
Category (Clothing, Accessories, Footwear, Outerwear)
Purchase Amount
Season, Size, Color

Behavioral Data

Discount Applied
Promo Code Used
Previous Purchases
Purchase Frequency
Review Rating
Shipping Type

##  Data Preprocessing (Python)

Data cleaning and preparation were performed using Python (Pandas):

Loaded dataset using pandas
Checked structure with df.info() and summary stats with describe()
Handled missing values:
37 missing values in Review Rating
Imputed using median rating per category
Standardized column names (snake_case)
Removed redundant columns (promo_code_used)

##  Feature Engineering
Created age_group (Young Adult, Adult, Middle-aged, Senior)
Created purchase_frequency_days
Performed data consistency checks

##  SQL Analysis (PostgreSQL)

After cleaning, data was loaded into PostgreSQL for business analysis.

##  Key Business Questions Answered:

Revenue comparison by gender
High-spending customers using discounts
Top 5 highest-rated products
Subscribers vs Non-subscribers analysis
Shipping type vs purchase behavior
Customer segmentation:
New
Returning
Loyal
Discount-dependent products
Top 3 products per category
Revenue contribution by age group
Relationship between repeat buyers and subscriptions

##  Dashboard (Power BI)

An interactive dashboard was built using Power BI to visualize insights.

##  Key Metrics:

 Total Customers: 3.9K
 Average Purchase Amount: $59.76
⭐ Average Rating: 3.75
- ## Dashboard Insights:
    - Revenue & sales by category
    - Customer distribution by subscription
    - Sales & revenue by age group
    - Category performance comparison
    - Customer segmentation insights

##  Business Recommendations

-  Boost Subscriptions
  - Offer exclusive benefits to subscribers
  - Encourage non-subscribers to convert
-  Targeted Marketing
  - Focus on high-revenue age groups
  - Personalize campaigns based on behavior
-  Product Positioning
  - Highlight top-rated and best-selling products
-  Review Discount Strategy
  - Balance discounts with profitability
  - Identify discount-dependent products
-  Customer Loyalty Programs
  - Reward repeat customers
  - Convert returning users into loyal customers
-  Tools & Technologies
  - Python (Pandas, NumPy) – Data Cleaning & EDA
  - PostgreSQL – Data Analysis
  - Power BI – Data Visualization & Dashboard
##  Dashboard Preview
<img width="1436" height="835" alt="Screenshot 2026-03-24 173901" src="https://github.com/user-attachments/assets/28409fdb-ecf1-4fc2-a6e4-bc3f13d70077" />


## Project Structure

├── Bussiness Problem Document/

├── Report/

├── Presentation/

├── Jupyter Notebook/

├── README.md/

├── Power BI DASHBOARD/

├── SQL/

├── Dataset

##  Conclusion

This project demonstrates how combining Python, SQL, and Power BI can transform raw transactional data into meaningful business insights.

It highlights the importance of:

- Data cleaning
- Analytical thinking
- Visualization
  
for effective decision-making.

## ⭐ Support
If you like this project:

👉 Star this repository

👉 Connect with me on LinkedIn

https://www.linkedin.com/in/prince-kumar-giri-450114331?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
