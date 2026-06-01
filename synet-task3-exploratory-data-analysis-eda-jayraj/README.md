# Task 3: Exploratory Data Analysis (EDA)

## Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Shows Dataset to identify trends, patterns, and insights related to Netflix content. EDA helps in understanding the structure of the dataset, discovering hidden relationships, and generating business insights through statistical analysis and visualizations.

The analysis focuses on content distribution, release trends, ratings, genres, countries, and correlations among numerical variables.

---

## Dataset

**Dataset:** Netflix Shows Dataset

The dataset contains information about movies and TV shows available on Netflix, including details such as title, type, country, release year, rating, duration, and genre.

### Features

* show_id
* type
* title
* director
* cast
* country
* date_added
* release_year
* rating
* duration
* listed_in
* description

---

## Objectives

* Perform exploratory data analysis on Netflix content
* Generate summary statistics
* Analyze content trends over time
* Explore country-wise and genre-wise distributions
* Perform correlation analysis
* Visualize patterns using graphs
* Generate meaningful business insights

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Kaggle Notebook

---

## Data Preparation

### Date Conversion

The `date_added` column was converted into datetime format to enable time-based analysis.

### Feature Engineering

Additional features were extracted:

* Year Added
* Month Added

These features were used to identify content growth trends and seasonal patterns.

---

## Exploratory Analysis Performed

### 1. Summary Statistics

Statistical summaries were generated to understand:

* Data distribution
* Missing values
* Feature characteristics
* Dataset structure

---

### 2. Movies vs TV Shows Analysis

A count plot was created to compare:

* Total Movies
* Total TV Shows

**Purpose:**

* Understand content composition on Netflix

---

### 3. Top Content Producing Countries

Country information was analyzed to identify the leading contributors of Netflix content.

**Purpose:**

* Identify geographic distribution of content production

---

### 4. Content Addition Trend

A yearly trend analysis was performed to examine how Netflix expanded its content library over time.

**Purpose:**

* Measure platform growth

---

### 5. Ratings Analysis

Content ratings were analyzed to determine the most common audience categories.

**Purpose:**

* Understand target audience demographics

---

### 6. Genre Analysis

Genre frequencies were examined to identify the most popular categories on Netflix.

**Purpose:**

* Discover viewer content preferences

---

### 7. Monthly Content Addition Analysis

Monthly upload patterns were studied to detect seasonal trends.

**Purpose:**

* Understand content release cycles

---

### 8. Correlation Analysis

A correlation matrix and heatmap were generated using numerical features.

**Purpose:**

* Identify relationships between variables

---

### 9. Release Year Trend

Content release years were analyzed to understand historical production trends.

**Purpose:**

* Explore how content production evolved over time

---

## Visualizations Generated

The project includes:

* Movies vs TV Shows Count Plot
* Top Producing Countries Bar Chart
* Content Added Over Years Line Chart
* Ratings Distribution Chart
* Top Genres Bar Chart
* Monthly Content Addition Trend
* Correlation Heatmap
* Release Year Trend Plot

---

## Key Insights

### Content Type Distribution

* Movies significantly outnumber TV shows on Netflix.

### Country Contribution

* The United States contributes the largest share of Netflix content.

### Growth Trend

* Netflix experienced rapid growth in content additions after 2015.

### Ratings

* TV-MA and TV-14 are among the most common ratings, indicating a strong focus on mature audiences.

### Popular Genres

* International Movies, Dramas, and Comedies are among the most represented genres.

### Seasonal Trends

* Content additions vary throughout the year, indicating periodic release patterns.

### Correlation Findings

* Numerical features show varying levels of correlation and support further analysis.

---

## Output

The analysis produces:

* Statistical summaries
* Trend visualizations
* Correlation heatmaps
* Country-wise insights
* Genre-based insights
* Business-oriented observations

---

## Results

The exploratory analysis successfully identifies:

* Content distribution patterns
* Netflix growth trends
* Popular content categories
* Audience targeting strategies
* Geographic content distribution
* Seasonal upload behavior

---

## Business Insights

1. Movies dominate Netflix's content library.
2. The United States remains the primary content producer.
3. Content growth accelerated significantly after 2015.
4. Mature audience content represents a large portion of the catalog.
5. International and drama-based content are highly prevalent.
6. Seasonal trends may influence content release strategies.

---

## Conclusion

Exploratory Data Analysis of the Netflix dataset provides valuable insights into content trends, audience targeting, geographic distribution, and platform growth. The findings can help support content strategy, recommendation systems, and future business decisions related to streaming platforms.
