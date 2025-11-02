# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions[attached_file:1].

## Dataset Description
- **Rows:** 3,900
- **Columns:** 18
- **Key Features:**
  - Customer demographics: Age, Gender, Location, Subscription Status
  - Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  - Shopping behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
- **Missing Data:** 37 values missing in the Review Rating column[attached_file:1].

## Data Preparation and Analysis

### Data Cleaning & Feature Engineering
- Handled missing values and standardized column names.
- Created new features: age group (by binning ages) and purchase frequency (days).
- Imputed missing review ratings by the median rating of each product category.
- Ensured data consistency by checking redundant columns and integrating with PostgreSQL for SQL-based analysis[attached_file:1].

### Exploratory Data Analysis (EDA)
- Performed initial data exploration and summary statistics using Python (pandas).
- Visualized distributions and trends in customer shopping patterns[attached_file:1].

### SQL Business Analysis
- Structured analysis in SQL Server Management Studio (SSMS) to answer business questions:
  - Revenue by Gender
  - High-Spending Discount Users
  - Top 5 Products by Rating
  - Shipping Type Comparison
  - Subscribers vs. Non-Subscribers spend/revenue
  - Discount-Dependent Products
  - Customer Segmentation (New, Returning, Loyal)
  - Top Products per Category
  - Repeat Buyers and Subscription Likelihood
  - Revenue by Age Group[attached_file:1]

## Dashboard

The findings are presented in an interactive dashboard built using Power BI to visually communicate key insights and trends to stakeholders[attached_file:1].

<img width="1672" height="1070" alt="Screenshot 2025-11-02 105052" src="https://github.com/user-attachments/assets/c9c4b2b2-4c7e-4b9b-bfad-10b929d4e35b" />


## Business Recommendations
- **Boost Subscriptions:** Promote exclusive benefits for subscribers.
- **Customer Loyalty Programs:** Reward repeat buyers to increase loyalty.
- **Review Discount Policy:** Balance between sales uplift and profit margin.
- **Product Positioning:** Highlight top-rated and best-selling products.
- **Targeted Marketing:** Focus on high-revenue age groups and express shipping users[attached_file:1].

## How to Run

1. Clone this repository.
2. Open and run the provided Jupyter Notebooks for data cleaning and analysis.
3. View the Power BI dashboard (dashboard file included).
4. For SQL analysis, use the provided `.sql` scripts in SSMS or PostgreSQL.

## Requirements

- Python 3.x
- pandas
- Jupyter Notebook
- PostgreSQL or MySQL or SQL Server
- Power BI Desktop

## License

This project is for educational and portfolio purposes.
