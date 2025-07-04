## Amazon-Product-Review-Analysis
 This project analyzes Amazon product data to generate insights that can guide sellers on product improvements, pricing, discounts, and customer engagement.
 ## Project Topic
 Amazon-Product-Review-Analysis
##  Project Overview

- **Role:** Junior Data Analyst
- **Company:** RetailTech Insights
- **Dataset:** 1,465 Amazon product records, 16 fields
- **Tools Used:** Microsoft Excel (Pivot Tables, Formulas, Charts)

## Data Source
The primary source of data use here is Amazon case study.xlsx and this is an open source data that can be downloaded from LMS

##  Dataset Description
The dataset includes:

- Product details:
  - `Product_Name`
  - `Category`
  - `Actual_Price`
  - `Discounted_Price`
  - `Discount_Percentage`
  - `Rating`
  - `Review_Count`
Each row represents one unique product on Amazon.

##  Analysis Objectives

The following business questions were answered:

1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g. how many products are rated 3.0, 4.0, etc.)?
9. What is the total potential revenue (actual_price × review_count) by category?
10. What is the number of unique products per price range bucket (< ₹200, ₹200–₹500, > ₹500)?
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.

---

##  Methods & Steps
All analysis was performed in Excel:
- Pivot Tables for aggregations
- Calculated columns for custom metrics:
  - Potential Revenue = `Actual_Price × Review_Count`
  - Discount Flag ≥ 50%
  - Price Buckets (< ₹200, ₹200–₹500, > ₹500)
  - Rating × Review Count for product ranking
- Charts:
  - Bar Charts
  - Pie Charts
  - Column Charts
  - Scatter Plots
- Slicers for interactivity in the dashboard

  ##  Dashboard Features
The Excel dashboard includes:
- KPIs:
  - Total Products
  - Average Discount
  - Total Reviews
  - Total Potential Revenue
- Visuals:
  - Avg Discount % by Category
  - Product Count by Category
  - Average Actual vs Discounted Price by Category
  - Distribution of Ratings
  - Scatter plot of Rating vs Discount
  - Top Products by combined rating & reviews
- Slicers:
  - Category
  - Price Range

---

##  Key Insights

- Certain categories offer higher average discounts.
- A significant number of products are priced under ₹500.
- Ratings tend to cluster around specific discount levels.
- A small set of products drive high engagement via reviews.
- Potential revenue varies strongly by category.

  ##  Files Included

- **Amazon case study.xlsx** → Cleaned data, pivot tables, and dashboard.
