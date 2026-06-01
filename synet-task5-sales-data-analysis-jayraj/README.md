# Task 5: Sales Data Analysis

## Overview

This project focuses on analyzing sales data to evaluate business performance and identify key revenue-driving factors. Using a retail sales dataset, the analysis explores sales trends, product performance, category-wise sales, regional performance, and overall business insights.

The goal is to transform raw sales data into meaningful business intelligence that can support decision-making and future sales strategies.

---

## Dataset

**Dataset:** Sales Forecasting Dataset

The dataset contains transactional sales records including order details, customer information, product information, regional data, and sales values.

### Features

* Order ID
* Order Date
* Ship Date
* Ship Mode
* Customer ID
* Customer Name
* Segment
* Country
* City
* State
* Postal Code
* Region
* Product ID
* Category
* Sub-Category
* Product Name
* Sales

---

## Objectives

* Analyze monthly revenue trends
* Identify top-selling products
* Analyze category-wise performance
* Evaluate regional sales performance
* Generate business insights through data visualization
* Support business decision-making using data

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Kaggle Notebook

---

## Data Preprocessing

### Date Conversion

The `Order Date` column was converted into datetime format to enable time-series analysis.

### Feature Engineering

Additional features were created:

* Year
* Month
* Month-Year

These features were used to analyze monthly sales trends and seasonal patterns.

---

## Analysis Performed

### 1. Monthly Revenue Trend

Monthly sales were aggregated to identify changes in revenue over time.

**Purpose:**

* Monitor business growth
* Detect seasonal sales patterns
* Identify peak and low-performing periods

---

### 2. Sales Distribution Analysis

A histogram was used to visualize the distribution of sales values.

**Purpose:**

* Understand sales variability
* Identify high-value transactions
* Detect skewness in sales data

---

### 3. Top-Selling Products

Products were ranked according to total sales generated.

**Purpose:**

* Identify best-performing products
* Support inventory planning
* Guide product promotion strategies

---

### 4. Category Analysis

Sales performance was analyzed across different product categories.

**Purpose:**

* Determine revenue contribution by category
* Identify strong and weak product segments

---

### 5. Sub-Category Analysis

Sales were further analyzed at the sub-category level.

**Purpose:**

* Gain detailed product-level insights
* Identify niche growth opportunities

---

### 6. Regional Analysis

Sales performance was compared across business regions.

**Purpose:**

* Identify high-performing markets
* Support geographic expansion strategies
* Improve regional sales planning

---

### 7. Correlation Analysis

Relationships between numerical variables were explored using a correlation heatmap.

**Purpose:**

* Understand feature relationships
* Support future predictive modeling

---

## Visualizations Generated

The project includes:

* Monthly Revenue Trend Line Chart
* Sales Distribution Histogram
* Top-Selling Products Bar Chart
* Category Sales Analysis
* Sub-Category Sales Analysis
* Regional Sales Comparison Chart
* Correlation Heatmap

---

## Key Insights

### Revenue Trends

* Revenue fluctuates across months, indicating seasonal business behavior.
* Certain months generate significantly higher sales than others.

### Product Performance

* A small number of products contribute a substantial portion of total revenue.
* Identifying top-performing products helps optimize inventory management.

### Category Performance

* Some categories consistently outperform others in total sales.
* Category-level analysis highlights revenue concentration areas.

### Regional Performance

* Sales performance varies significantly across regions.
* Certain regions contribute a larger share of overall revenue.

### Customer Demand

* Sales distribution indicates the presence of both low-value and high-value transactions.
* Understanding customer purchasing behavior supports marketing strategies.

---

## Output

The analysis produces:

* Revenue trend reports
* Product performance rankings
* Category and sub-category insights
* Regional sales comparisons
* Business intelligence visualizations
* Sales summary statistics

---

## Results

The analysis successfully identifies:

* Revenue growth patterns
* High-performing products
* Strong product categories
* Leading sales regions
* Seasonal sales behavior
* Business opportunities for optimization

---

## Business Insights

1. Revenue trends reveal important seasonal fluctuations.
2. A small percentage of products contribute a large portion of sales revenue.
3. Product category performance varies significantly.
4. Regional sales analysis helps identify profitable markets.
5. Sales data can support inventory optimization and demand forecasting.
6. Business decisions can be improved through data-driven insights.

---

## Limitations

The provided dataset contains **Sales** information but does not include:

* Profit
* Discount
* Quantity

Therefore, true profitability analysis could not be performed. The analysis focuses on revenue-based performance metrics and sales trends.

---

## Conclusion

Sales data analysis provides valuable insights into business performance, customer purchasing behavior, product success, and regional market trends. The findings can support strategic decision-making, inventory management, marketing initiatives, and future sales forecasting efforts.
