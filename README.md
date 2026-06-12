Jumia Product Performance Analysis Dashboard
Project Overview
https://dev.to/nelly_mogere_194bac0cb2ba/how-excel-is-used-in-real-world-data-analysis-g1

This project focuses on analyzing product performance data from Jumia and presenting actionable insights through an interactive Excel dashboard. The analysis explores the relationship between product pricing, discounts, customer reviews, and ratings to help identify trends, popular products, and areas for improvement.

The dashboard was developed using Microsoft Excel and incorporates data cleaning, transformation, analysis, Pivot Tables, Pivot Charts, and Slicers to provide an interactive user experience.

Objectives

The primary objectives of this project were to:

Analyze product pricing and discount strategies.
Evaluate customer engagement through reviews and ratings.
Identify top-performing and underperforming products.
Examine relationships between discounts, ratings, and customer reviews.
Build an interactive dashboard that enables users to explore product performance dynamically.
Dataset Description

The dataset contains information about products listed on Jumia and includes the following fields:

Column	Description
Product	Name of the product
Current Price	Current selling price (KSh)
Old Price	Original price before discount (KSh)
Discount	Percentage discount offered
Review	Number of customer reviews
Rating	Average customer rating out of 5
Data Cleaning and Preparation

Before analysis, several preprocessing steps were performed to ensure data quality and consistency.

1. Handling Missing Values
Checked for missing entries in reviews and ratings.
Verified completeness of pricing information.
Addressed any missing values to maintain analytical accuracy.
2. Duplicate Removal
Identified and removed duplicate product records where applicable.
3. Data Type Standardization
Price Columns

The Current Price and Old Price columns were converted into numeric format by:

Removing the "KSh" currency symbol.
Removing comma separators.
Converting values into numerical data types suitable for calculations.
Rating Column

The rating values were standardized by:

Removing text such as "out of 5".
Converting ratings into decimal numeric values.
Data Enrichment

Additional calculated fields were created to support deeper analysis.

1. Discount Amount

Calculated using:

Discount Amount = Old Price - Current Price

This metric measures the actual monetary value saved by customers.

2. Rating Categories

Products were categorized based on customer ratings:

Rating Range	Category
Below 3.0	Poor
3.0 – 4.4	Average
4.5 and Above	Excellent
3. Discount Categories

Products were grouped according to discount percentages:

Discount Percentage	Category
Less than 20%	Low Discount
20% – 40%	Medium Discount
Greater than 40%	High Discount
Data Analysis
Descriptive Statistics

The following summary statistics were generated:

Average Current Price
Average Old Price
Average Discount Percentage
Average Product Rating
Total Number of Products
Total Reviews

Additional insights include:

Most expensive product
Least expensive product
Average rating by discount category
Average discount percentage by rating category
Trend Analysis
1. Discount vs Reviews

This analysis investigated whether products with higher discounts receive more customer reviews.

Key questions:

Do larger discounts attract more customers?
Is there a positive relationship between discounts and review counts?

Visualization Used:

Scatter Plot
Pivot Chart
2. Rating vs Reviews

This analysis examined whether highly-rated products receive more reviews.

Key questions:

Do customers engage more with highly-rated products?
Is product popularity reflected in review volume?

Visualization Used:

Scatter Plot
Pivot Chart
3. Product Ranking

Products were ranked according to ratings.

Outputs:

Top 5 Highest Rated Products

Products with the strongest customer satisfaction scores.

Top 5 Lowest Rated Products

Products that may require quality improvements or better customer support.

Product Performance Analysis
Top 10 Products with Highest Discounts

Products offering the largest percentage discounts were identified to evaluate promotional effectiveness.

Visualization Used:

Bar Chart
Top 10 Products with Most Reviews

Products with the highest customer engagement were identified.

Visualization Used:

Horizontal Bar Chart
High Discount vs Low Discount Comparison

Products were grouped into discount categories and compared based on:

Average Rating
Average Number of Reviews
Customer Engagement

This analysis helps determine whether aggressive discounting impacts customer perception and interaction.

Dashboard Design
Dashboard Features

The Excel dashboard was designed to be:

Interactive
User-friendly
Visually appealing
Easy to navigate

The dashboard leverages:

Pivot Tables
Pivot Charts
Slicers
KPI Cards
Dashboard Sections
1. Overview Section

Provides key performance indicators including:

Total Products
Average Rating
Average Discount Percentage
Total Reviews

These metrics offer a quick summary of overall marketplace performance.

2. Pricing and Discount Analysis

Visualizes:

Price distribution
Discount distribution
Top discounted products
Discount category performance
3. Review and Rating Analysis

Displays:

Rating distribution
Review trends
Rating versus review relationship
Top-rated and lowest-rated products
4. Product Performance Section

Highlights:

Best-performing products
Most reviewed products
Products with highest discounts
Category comparisons
5. Interactive Filtering

Slicers allow users to dynamically filter dashboard views by:

Rating Category
Discount Category
Product Selection

This enables customized exploration of product performance metrics.

Tools and Techniques Used
Microsoft Excel Features
Pivot Tables
Pivot Charts
Slicers
Conditional Formatting
Calculated Columns
Sorting and Filtering
Statistical Analysis
Data Preparation Techniques
Data Cleaning
Data Transformation
Feature Engineering
Categorization
Key Business Insights

The dashboard enables stakeholders to:

Monitor overall product performance.
Identify highly-rated products.
Evaluate discount effectiveness.
Understand customer engagement patterns.
Discover products requiring attention or improvement.
Support pricing and promotional decision-making.
Conclusion

This project demonstrates how Excel can be used as a powerful data analytics and business intelligence tool. Through data cleaning, enrichment, statistical analysis, and dashboard development, meaningful insights were extracted from Jumia product data. The resulting interactive dashboard provides decision-makers with a comprehensive view of product performance, customer engagement, pricing strategies, and discount effectiveness, enabling data-driven business decisions.

Author: Nelly Mogere
Project: Jumia Product Performance Analysis Dashboard
Tool Used: Microsoft Excel
Focus Areas: Data Cleaning, Data Analysis, Business Intelligence, Dashboard Design, Data Visualization
