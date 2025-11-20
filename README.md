# SQL + AI Product Recommender

## Overview
This project is a product recommendation system using SQL and machine learning. Products from Amazon are stored in a SQLite database and recommendations are generated based on text similarity using TF-IDF and Nearest Neighbors.

## Dataset
The dataset `ecommerce_data.csv` contains:
- product_title
- discounted_price
- product_category
- product_image_url

The data is stored in a SQLite database `amazon.db`.

## Features
- Store and load products in/from SQLite database
- Shorten long product names for display
- TF-IDF vectorization for product text
- Nearest Neighbors recommendation system
- Streamlit interface for interactive recommendations

## Installation
1. Install required packages:
2. Make sure `ecommerce_data.csv` is in the project directory.

## Usage
1. Run the Streamlit app:
2. Select a product from the dropdown to see recommended products with images, names, and prices.

## Author
Obada Issa
