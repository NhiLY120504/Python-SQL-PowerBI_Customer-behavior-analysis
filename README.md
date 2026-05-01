# Customer Purchasing Behavior Analysis

## 1. Overview
This project analyzes customer purchasing behavior using transaction data from 3,900 purchases across various product categories. 
The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

---

## 2. Dataset Summary 
- **Rows:** 3,900
- **Columns:** 18
- **Missing data:** 37 values in the Review Rating column

### Key Features

| Fields | Variables |
| :--- | :--- |
| Customer demographics | Age, Gender, Location, Subscription Status |
| Purchase details | Item Purchased, Category, Purchase Amount, Season, Size, Color |
| Shopping behavior | Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type |

---

## 3. EDA using Python
[View details](Initial-data.png)

### Initial Exploration
![Initial Exploration](Initial-data.png)

### Data Processing

| Procedure | Details |
| :--- | :--- |
| **Handling Missing values** | Check for null values and fill in any missing values in the Review Rating column using the median rating for each product category. |
| **Standardization** | Convert the columns to snake case. |
| **Feature Engineering** | - Create an `age_group` column by grouping customers by age.<br>- Create a `purchase_frequency_days` column from the purchase data. |
| **Data Consistency** | Verify that `discount_applied` and `promo_code_used` are duplicates; `promo_code_used` has been removed. |

---

## 4. Data Analysis using SQL 
[View details](link_to_your_sql_file_here)

### 4.1. Revenue by Gender 
![Revenue by Gender](link_to_image_4.1_here) 

### 4.2. High-Spending Discount Users 
![High-Spending Discount Users](link_to_image_4.2_here) 

### 4.3. Top 5 Products by Rating 
![Top 5 Products by Rating](link_to_image_4.3_here) 

### 4.4. Shipping Type Comparison 
![Shipping Type Comparison](link_to_image_4.4_here) 

### 4.5. Subscribers vs. Non-Subscribers 

### 4.6. Discount-Dependent Products
![Discount-Dependent Products](link_to_image_4.6_here) 

### 4.7. Customer Segmentation 
![Customer Segmentation](link_to_image_4.7_here) 

### 4.8. Top 3 Products per Category 
![Top 3 Products per Category](link_to_image_4.8_here) 

### 4.9. Repeat Buyers & Subscriptions 
![Repeat Buyers & Subscriptions](link_to_image_4.9_here) 

### 4.10. Revenue by Age Group 
![Revenue by Age Group](link_to_image_4.10_here) 

---

## 5. Dashboard in Power BI 
[View details](link_to_your_pbix_file_here)

![Power BI Dashboard Overview](link_to_your_dashboard_image_here)
