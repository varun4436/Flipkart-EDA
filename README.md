# Flipkart E-commerce Data Analysis using Python

## Overview

This project focuses on analyzing Flipkart e-commerce product data using Python. The analysis includes data cleaning, preprocessing, exploratory data analysis (EDA), and visualizations to gain insights into product pricing, discounts, brands, and categories.

The project is implemented in a Google Colab and uses popular Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

---

## Features

* Data loading and preprocessing
* Handling missing values and duplicate records
* Discount percentage calculation
* Analysis of top product brands
* Analysis of top product categories
* Data visualization using charts and plots
* Retail price vs discounted price comparison

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Dataset

The project uses the Flipkart e-commerce dataset:

**File Name:** `flipkart_com-ecommerce_sample.csv`

The dataset contains information such as:

* Product Name
* Brand
* Product Category
* Retail Price
* Discounted Price
* Product Description
* Ratings and other product details

---

## Project Workflow

### 1. Import Required Libraries

The notebook begins by importing essential Python libraries:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

### 2. Upload and Load Dataset

The dataset is uploaded and loaded into a Pandas DataFrame.

### 3. Data Cleaning

* Checked missing values
* Removed duplicate records
* Filled missing brand values with `unknown`


### 4. Exploratory Data Analysis (EDA)

The following analyses were performed:

* Top 10 brands
* Top 10 product categories
* Brand market share
* Retail price vs discounted price analysis

### 5. Data Visualization

Visualizations include:

* Bar charts
* Pie charts
* Scatter plots

---

## Visualizations Included

### Top 10 Brands

Displays the most popular brands based on the number of products.

### Top Product Categories

Shows the most common product categories available in the dataset.

### Top 5 Brand Share

Pie chart representing market share distribution among top brands.

### Retail Price vs Discounted Price

Scatter plot comparing original product prices with discounted prices.

---

## Project Structure

```text
flipkart-ecommerce-analysis/
│
├── Flipkart.ipynb
├── flipkart_com-ecommerce_sample.csv
└── README.md
```

---

## Future Improvements

* Add advanced data visualizations
* Perform sentiment analysis on product reviews
* Build recommendation systems
* Create interactive dashboards using Plotly or Power BI
* Apply machine learning models for price prediction

---
