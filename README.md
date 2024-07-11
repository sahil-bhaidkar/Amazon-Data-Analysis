# Amazon Data Analysis Report

## Table of Contents
1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Data Cleaning](#data-cleaning)
4. [Data Analysis](#data-analysis)
5. [Visualizations](#visualizations)
6. [Insights](#insights)
7. [Conclusion](#conclusion)
8. [Usage](#usage)
9. [References](#references)

## Introduction
This project analyzes data from Amazon product reviews to gain insights into product performance, customer satisfaction, and sales metrics. The analysis is performed using Power BI, a powerful data visualization tool.

## Data Description
The dataset contains information about various products, including:
- `product_id`: Unique identifier for each product.
- `product_name`: Name of the product.
- `category`: Categories the product belongs to.
- `discounted_price`: The discounted price of the product.
- `actual_price`: The original price of the product.
- `discount_percentage`: Percentage of discount on the product.
- `rating`: Average customer rating of the product.
- `rating_count`: Number of ratings received.
- `about_product`: Description and features of the product.
- `user_id`: Unique identifiers for the users who reviewed the product.
- `user_name`: Names of the users who reviewed the product.
- `review_id`: Unique identifiers for the reviews.
- `review_title`: Titles of the reviews.
- `review_content`: Content of the reviews.
- `img_link`: Link to the product image.
- `product_link`: Link to the product page on Amazon.

## Data Cleaning
Data cleaning steps included:
1. Removing duplicates.
2. Handling missing values.
3. Correcting data types.
4. Standardizing category names.
5. Splitting `about_product` into individual features for more granular analysis.

## Data Analysis
The analysis focuses on the following aspects:
1. **Product Performance**: Analyzing sales metrics and discount patterns.
2. **Customer Satisfaction**: Analyzing ratings and reviews to gauge customer satisfaction.
3. **Category Analysis**: Comparing performance across different product categories.

## Visualizations
The following visualizations were created using Power BI:
1. **Sales Dashboard**: Displays total sales, discount trends, and top-performing products.
2. **Customer Satisfaction Dashboard**: Shows average ratings, distribution of ratings, and sentiment analysis of reviews.
3. **Category Comparison**: Highlights the performance of various product categories in terms of sales and customer satisfaction.

## Insights
Key insights derived from the analysis:
1. Products with higher discounts tend to receive more ratings.
2. Certain categories consistently outperform others in terms of sales.
3. Positive customer reviews often highlight durability and compatibility as key product strengths.

## Conclusion
This analysis provides valuable insights into product performance and customer satisfaction on Amazon. Businesses can leverage these insights to optimize pricing strategies, improve product features, and enhance customer engagement.

## Usage
To use this Power BI report:
1. Download the Power BI Desktop application.
2. Open the `.pbix` file provided in this repository.
3. Refresh the data to ensure you have the latest updates.
4. Navigate through the dashboards to explore the insights.

## References
- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [Amazon Product Advertising API](https://affiliate-program.amazon.com/)
