# OIBSIP
# Superstore Sales Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Superstore Sales dataset to understand sales performance, product trends, customer purchasing behaviour, and profitability.

The analysis uses Python libraries to clean, explore, analyze, and visualize retail sales data.

## Objectives
- Analyze overall sales and profit performance.
- Identify monthly and quarterly sales trends.
- Find the top 10 best-selling products.
- Compare revenue across product categories.
- Understand relationships between numerical variables.
- Analyze sales across customer segments and regions.
- Provide actionable business recommendations.

## Dataset Information
- **Dataset:** Sample Superstore
- **Total Records:** 9,994
- **Total Columns:** 21
- **Data Type:** Retail sales transaction data

The dataset includes order details, customer information, product categories, sales, quantity, discount, profit, and shipping information.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure

```text
Superstore_Sales_Analysis/
│
├── dataset/
│   └── Sample - Superstore.csv
│
├── Sanjana_Task1.ipynb
│
└── README.md
```

## Analysis Performed

### 1. Data Inspection and Cleaning
- Loaded and inspected the dataset.
- Checked missing values and duplicate records.
- Converted order and shipping dates into datetime format.

### 2. Descriptive Statistical Analysis
Calculated:
- Mean
- Median
- Mode
- Standard Deviation

### 3. Sales Trend Analysis
- Monthly sales trend.
- Quarterly sales trend.

### 4. Product Performance Analysis
- Top 10 best-selling products.
- Revenue by product category.

### 5. Correlation Analysis
- Calculated correlation between Sales, Quantity, Discount, and Profit.
- Created a correlation heatmap.

### 6. Additional Visualization
- Analyzed average profit across different discount levels.

### 7. Customer and Regional Analysis
- Sales by customer segment.
- Sales by geographical region.

## Key Findings
- The dataset contains 9,994 records and 21 columns.
- No missing values or duplicate rows were detected.
- Technology generated the highest revenue among the three product categories.
- Staples was the top-selling product by quantity, with 215 units sold.
- The West region recorded the highest sales.
- The South region recorded the lowest sales.
- Sales and Profit showed a moderate positive correlation of 0.48.
- Higher discount levels generally showed negative average profit.

## Dataset Limitation
The dataset does not contain customer Age or Gender information. Therefore, demographic analysis based on age groups and gender could not be performed. Customer analysis was conducted using the available Segment and Region columns.

## Conclusion
This project demonstrates how Exploratory Data Analysis can help identify business trends, understand product performance, analyze customer segments, and support data-driven business decisions.

## Author
**Sanjana Chauhan**

