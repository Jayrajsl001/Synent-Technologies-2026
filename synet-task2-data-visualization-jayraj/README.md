# Task 2: Data Visualization

## Overview

This project focuses on visualizing the Iris dataset to identify patterns, relationships, and trends among different flower species. Data visualization is an essential step in exploratory data analysis (EDA) as it helps transform raw data into meaningful insights through graphical representations.

The Iris dataset is one of the most widely used datasets in machine learning and contains measurements of iris flowers from three different species.

---

## Dataset

**Dataset:** Iris Dataset

The dataset contains measurements of iris flowers belonging to three species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

### Features

* SepalLengthCm
* SepalWidthCm
* PetalLengthCm
* PetalWidthCm
* Species

---

## Objectives

* Visualize feature distributions
* Compare characteristics of different iris species
* Identify relationships between variables
* Explore patterns using graphical analysis

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Kaggle Notebook

---

## Visualizations Created

### 1. Bar Chart

A bar chart was created to display the number of flowers belonging to each species.

**Purpose:**

* Understand class distribution
* Compare species counts

---

### 2. Histogram

A histogram was used to visualize the distribution of sepal length values.

**Purpose:**

* Analyze data spread
* Identify skewness and frequency distribution

---

### 3. Scatter Plot

A scatter plot was generated to compare Sepal Length and Petal Length across different species.

**Purpose:**

* Identify relationships between features
* Observe species separation

---

### 4. Pair Plot

A pair plot was used to compare all numerical features simultaneously.

**Purpose:**

* Explore relationships among all variables
* Detect clusters and patterns

---

### 5. Correlation Heatmap

A heatmap was generated to visualize correlations between numerical features.

**Purpose:**

* Identify strongly related features
* Support feature selection for machine learning

---

### 6. Box Plot

A box plot was created to compare petal lengths across species.

**Purpose:**

* Detect outliers
* Compare feature distributions among species

---

## Project Workflow

1. Load Iris dataset
2. Explore dataset structure
3. Generate summary statistics
4. Create visualizations
5. Analyze feature relationships
6. Identify trends and patterns
7. Draw conclusions from graphical insights

---

## Key Insights

### Species Distribution

* The dataset contains an equal number of samples for each species.

### Feature Relationships

* Petal Length and Petal Width show a strong positive correlation.
* Sepal features exhibit weaker correlations compared to petal features.

### Species Separation

* Iris-setosa is clearly separable from the other species based on petal measurements.
* Iris-versicolor and Iris-virginica show some overlap but remain distinguishable.

### Data Distribution

* Most feature distributions appear approximately normal.
* Few significant outliers are present.

---

## Output

The project generates the following visualizations:

* Species Count Bar Chart
* Sepal Length Histogram
* Sepal Length vs Petal Length Scatter Plot
* Pair Plot
* Correlation Heatmap
* Species-wise Box Plot

These visualizations provide a clear understanding of the dataset and support further analysis and machine learning tasks.

---

## Results

The visualizations successfully reveal:

* Species distribution
* Feature correlations
* Data distributions
* Species-specific characteristics
* Potential feature importance for classification

---

## Conclusion

Data visualization provides valuable insights into the Iris dataset and helps uncover patterns that may not be apparent from raw data alone. The generated charts demonstrate clear differences among iris species and highlight relationships between flower measurements, making the dataset suitable for classification and machine learning applications.
