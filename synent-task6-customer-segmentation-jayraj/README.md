# Task 6: Customer Segmentation

## Overview

This project focuses on customer segmentation using unsupervised machine learning techniques. The objective is to group customers with similar characteristics and purchasing behavior into distinct segments. Customer segmentation helps businesses better understand their customers and design personalized marketing strategies.

The project uses the Mall Customers Dataset and applies K-Means Clustering to identify meaningful customer groups based on demographic and spending behavior.

---

## Dataset

**Dataset:** Mall Customers Dataset

The dataset contains customer demographic and spending information collected from a shopping mall.

### Features

* CustomerID
* Gender
* Age
* Education
* Marital Status
* Annual Income (k$)
* Spending Score (1-100)

### Feature Description

| Feature                | Description                                        |
| ---------------------- | -------------------------------------------------- |
| CustomerID             | Unique customer identifier                         |
| Gender                 | Customer gender                                    |
| Age                    | Customer age                                       |
| Education              | Educational qualification                          |
| Marital Status         | Marital status of customer                         |
| Annual Income (k$)     | Annual income in thousands of dollars              |
| Spending Score (1-100) | Score assigned based on customer spending behavior |

---

## Objectives

* Perform data preprocessing
* Encode categorical variables
* Apply K-Means clustering
* Determine the optimal number of clusters
* Visualize customer segments
* Generate business insights from customer groups

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Kaggle Notebook

---

## Data Preprocessing

### Data Cleaning

* Checked for missing values
* Verified dataset structure
* Standardized column names

### Feature Encoding

Categorical variables were converted into numerical form using Label Encoding:

* Gender
* Education
* Marital Status

### Feature Scaling

StandardScaler was applied to normalize feature values before clustering.

**Purpose:**

* Improve clustering performance
* Ensure equal contribution of all features

---

## Features Used for Clustering

The following features were selected:

* Age
* Annual Income (k$)
* Spending Score (1-100)

These variables provide valuable information about customer demographics and purchasing behavior.

---

## K-Means Clustering

### Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

**Purpose:**

* Minimize within-cluster variance
* Identify the most suitable number of customer segments

### Cluster Formation

K-Means Clustering was applied to divide customers into distinct groups based on similarity.

---

## Cluster Evaluation

### Silhouette Score

The Silhouette Score was calculated to evaluate clustering quality.

**Purpose:**

* Measure cluster separation
* Assess clustering effectiveness

Higher scores indicate better-defined customer segments.

---

## Visualizations Generated

The project includes:

### 1. Elbow Method Plot

* Identifies optimal cluster count

### 2. Customer Segmentation Scatter Plot

* Annual Income vs Spending Score
* Color-coded customer clusters

### 3. Age vs Spending Score Visualization

* Highlights age-related spending behavior

### 4. Cluster Distribution Chart

* Number of customers in each segment

### 5. Income Distribution by Cluster

* Compares customer purchasing power

### 6. Cluster Centroid Visualization

* Displays cluster centers

---

## Customer Segments

The clustering process identifies customer groups such as:

### Cluster 1: Premium Customers

* High income
* High spending score

### Cluster 2: Potential Customers

* High income
* Low spending score

### Cluster 3: Regular Customers

* Moderate income
* Moderate spending score

### Cluster 4: Budget Customers

* Low income
* Low spending score

### Cluster 5: Young High-Spenders

* Lower age
* High spending score

---

## Key Insights

### Spending Behavior

* Customers with similar spending habits naturally form groups.
* High-income customers do not always spend the most.

### Income Analysis

* Certain customer segments have high purchasing power but low spending activity.

### Customer Value

* Premium customers contribute significantly to potential revenue.

### Marketing Opportunities

* Targeted campaigns can increase spending among underperforming customer segments.

---

## Output

The project generates:

* Customer clusters
* Cluster visualizations
* Cluster summaries
* Customer behavior insights
* Business recommendations

---

## Results

The clustering model successfully:

* Segmented customers into meaningful groups
* Identified spending patterns
* Revealed customer purchasing behavior
* Supported customer-focused marketing strategies

---

## Business Recommendations

### Premium Customers

* Offer loyalty programs
* Provide exclusive benefits

### High-Income Low-Spending Customers

* Launch personalized promotions
* Encourage repeat purchases

### Young High-Spenders

* Target with digital marketing campaigns
* Promote trending products

### Budget Customers

* Offer discounts and value-based products

### Regular Customers

* Maintain engagement through rewards and personalized offers

---

## Applications

Customer segmentation can be used for:

* Personalized Marketing
* Customer Retention
* Product Recommendation Systems
* Customer Lifetime Value Analysis
* Business Growth Strategies

---

## Conclusion

Customer segmentation using K-Means Clustering provides valuable insights into customer behavior and purchasing patterns. By identifying distinct customer groups, businesses can develop targeted marketing strategies, improve customer satisfaction, and maximize revenue through data-driven decision-making.
