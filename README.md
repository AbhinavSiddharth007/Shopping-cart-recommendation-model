# Shopping-cart-recommendation-model
# via Clustering

## Project Overview
This project implements a shopping cart product recommendation system using **unsupervised learning** with **KMeans clustering**  By analyzing customer purchase behavior, it groups similar product buying patterns to recommend relevant products based on a user's cart content.

## Objective
The main goal is to predict what additional items a customer might add to their cart by analyzing existing product clusters.

## Motivation
In e-commerce, improving the shopping experience through intelligent recommendations can significantly boost:
- Average order value
- Customer satisfaction
- Conversion rates

This system simulates a feature commonly used in major e-commerce platforms like Amazon.

## Dataset Description
The dataset is created by merging four structured CSV files:
- `customers.csv` — contains customer demographics and location
- `orders.csv` — order-level data
- `products.csv` — product attributes
- `sales.csv` — sales records linking products and orders

All files are stored in the `/data/` directory.

## Features and Engineering
The selected and engineered features include:
- Customer: `age`, `gender`
- Product: `price`, `colour`, `size`, `product_name_length`
- Order: `price_per_unit`, `quantity`, `total_price`
- All numerical features are standardized before clustering

## Methodology
1. **Data Preparation**
   - Loaded and merged data
   - Handled missing values and basic cleaning

2. **Exploratory Data Analysis**
   - Visualized feature distributions, correlations, and outliers

3. **Feature Engineering**
   - Created new features
