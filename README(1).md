# Social Media Sentiment Analytics

## Project Overview

**Project Title:** Social Media Sentiment Analytics

**Project Type:** Data Analytics & Visualization Course Project

**Dataset:** Social Media Sentiment Dataset

This project analyzes social media data to understand **sentiment patterns, platform activity, user engagement, country distribution, and time-based trends**.

The project follows a complete Data Analytics and Visualization workflow, starting from raw data inspection and cleaning and continuing through exploratory analysis, visualization, and data-driven insights.

---

## Project Objective

The main objective of this project is to analyze social media posts and identify meaningful patterns related to:

- Sentiment and emotions
- Social media platforms
- Likes and Retweets
- Overall engagement
- Country-wise activity
- Monthly and hourly activity
- Relationship between Likes and Retweets
- Correlation between numerical variables

### Central Analytical Question

> How do sentiment, engagement, platform activity, and time-based patterns vary across social media data?

---

# Dataset

The project uses a CSV dataset containing **732 social media records**.

### Dataset Columns

| Column | Description |
|---|---|
| `Text` | Social media post content |
| `Sentiment` | Sentiment or emotion associated with the post |
| `Timestamp` | Date and time of the post |
| `User` | User information |
| `Platform` | Social media platform |
| `Hashtags` | Hashtags used in the post |
| `Retweets` | Number of retweets |
| `Likes` | Number of likes |
| `Country` | Country associated with the post |
| `Year` | Year of posting |
| `Month` | Month of posting |
| `Day` | Day of posting |
| `Hour` | Hour of posting |

The dataset also contains index-related columns which are removed during data cleaning.

---

# Data Analytics Workflow

The project follows a standard Data Analytics workflow:

```text
RAW DATA
    ↓
DATA INSPECTION
    ↓
DATA CLEANING
    ↓
DATA PREPARATION
    ↓
EXPLORATORY DATA ANALYSIS
    ↓
SENTIMENT ANALYSIS
    ↓
PLATFORM ANALYSIS
    ↓
ENGAGEMENT ANALYSIS
    ↓
TIME & COUNTRY ANALYSIS
    ↓
DATA VISUALIZATION
    ↓
INSIGHTS
    ↓
CONCLUSION
```

### High-Level Flow

`RAW DATA → INSPECTION → CLEANING → EDA → ANALYSIS → VISUALIZATION → INSIGHTS`

---

# Project Assignments

This project contains two major Data Analytics & Visualization assignments.

---

## Assignment 1 — Data Analysis

### File

`DAV_Lab_Assignment_1_Social_Media_Analysis_FINAL.ipynb`

Assignment 1 focuses on analyzing and preparing the social media dataset.

### Topics Covered

#### Task 1 — Data Profiling & Duplicate Detection
- Dataset inspection
- Number of rows and columns
- Dataset information
- Duplicate record detection

#### Task 2 — Missing Values & Imputation
- Missing value identification
- Missing value summary
- Data preparation

#### Task 3 — Data Cleaning
- Removal of unnecessary columns
- Cleaning categorical values
- Preparing data for analysis

#### Task 4 — Statistical Analysis
- Descriptive statistics
- Numerical data analysis
- Summary statistics

#### Task 5 — Social Media Platform Analysis
- Platform distribution
- Platform-wise post analysis
- Platform comparison

#### Task 6 — Visualization
- Graphical representation of the dataset
- Charts for understanding patterns

#### Task 7 — Sentiment Analysis
- Sentiment distribution
- Sentiment frequency
- Analysis of sentiment categories

#### Task 8 — Engagement Analysis

Engagement is calculated using:

`Engagement = Likes + Retweets`

The analysis includes:
- Likes
- Retweets
- Engagement
- Platform-wise engagement

#### Task 9 — Country & Time Analysis
Analysis of:
- Countries
- Years
- Months
- Days
- Hours

#### Task 10 — Highly Engaging Posts
Analysis of posts having higher engagement based on Likes and Retweets.

#### Task 11 — Sentiment & Engagement Comparison
Comparison between sentiment categories and engagement metrics.

#### Task 12 — Hashtag Analysis
Analysis of hashtags present in the social media dataset.

#### Task 13 — Likes vs Retweets
Analysis of the relationship between Likes and Retweets.

#### Task 14 — Correlation Analysis
Correlation analysis between numerical variables.

#### Task 15 — Platform Comparison of Highly Engaging Posts
Comparison of highly engaging posts across social media platforms.

#### Task 16 — Final Dataset Summary
Final summary of the analyzed dataset and major observations.

---

# Assignment 3 — Data Visualization

### File

`DAV_Lab_Assignment_3_Social_Media_Analysis.ipynb`

Assignment 3 focuses mainly on **visualization and graphical analysis** of the social media dataset.

### Visualization Topics

#### Step 0 — Setup
- Import required libraries
- Load the CSV dataset

#### Step 0.1 — Understand the Dataset
- Dataset preview
- Dataset information
- Descriptive statistics

#### Step 0.2 — Clean the Dataset
- Remove unnecessary columns
- Clean categorical values
- Convert timestamp
- Prepare numerical data

#### Step 0.3 — Check Cleaned Columns
- Check cleaned data
- Verify numerical columns
- Check missing values

### Boxplot Analysis

#### Platform-wise Engagement Boxplot
Used to compare engagement across different platforms.

#### Platform-wise Likes Boxplot
Used to compare the distribution of Likes across platforms.

### Histogram + KDE

An **Engagement Histogram with KDE** is used to understand the distribution of engagement values.

### Correlation Heatmap

A correlation heatmap is used to visualize relationships between numerical variables such as Likes, Retweets, and Engagement.

### Violin Plot

Violin plots are used to understand the distribution of engagement and Likes across platforms.

### Platform Analysis

The project analyzes:
- Number of posts by platform
- Average Likes by platform
- Average Retweets by platform
- Average Engagement by platform

### Posts by Year
The project analyzes the number of social media posts by year.

### Posts by Month
The project analyzes monthly posting activity.

### Posts by Hour
The project analyzes the number of posts made during different hours.

### Top 15 Sentiments
A visualization is created for the **Top 15 sentiment categories** in the dataset.

### Likes vs Retweets
A scatter plot is used to visualize the relationship between Likes and Retweets.

---

# Main Analytical Areas

## 1. Sentiment Analysis

The project analyzes sentiment and emotion categories in social media posts.

The analysis focuses on:
- Sentiment frequency
- Sentiment distribution
- Most common sentiments
- Sentiment-related patterns

## 2. Platform Analysis

Social media activity is analyzed across the platforms present in the dataset.

The analysis includes:
- Number of posts
- Average Likes
- Average Retweets
- Average Engagement

## 3. Engagement Analysis

Engagement is calculated as:

`Engagement = Likes + Retweets`

Engagement is analyzed using:
- Boxplots
- Histograms
- KDE plots
- Violin plots
- Platform comparisons

## 4. Country Analysis

Country information is analyzed to understand the geographic distribution of social media posts.

## 5. Time Analysis

The dataset contains:
- Year
- Month
- Day
- Hour

The project analyzes:
- Posts by year
- Posts by month
- Posts by hour

## 6. Correlation Analysis

Numerical variables are analyzed using correlation techniques. A heatmap provides a visual representation of relationships between numerical variables.

---

# Data Cleaning

The following cleaning operations are performed:

- Remove unnecessary index columns
- Remove unwanted whitespace from categorical values
- Convert `Timestamp` into datetime format
- Prepare numerical columns
- Create the `Engagement` column

### Data Cleaning Flow

```text
RAW CSV
   ↓
REMOVE UNNECESSARY COLUMNS
   ↓
CLEAN CATEGORY VALUES
   ↓
CONVERT TIMESTAMP
   ↓
PREPARE NUMERICAL DATA
   ↓
CREATE ENGAGEMENT
   ↓
CLEAN DATASET
```

---

# Visualizations

The project uses multiple visualization techniques:

- Engagement Boxplot
- Likes Boxplot
- Engagement Histogram
- KDE Plot
- Correlation Heatmap
- Engagement Violin Plot
- Likes Violin Plot
- Platform Distribution
- Posts by Year
- Posts by Month
- Posts by Hour
- Top 15 Sentiments
- Likes vs Retweets Scatter Plot

---

# Dashboard Concept

The project can be represented using a Social Media Analytics Dashboard.

### Dashboard Components

- Total Posts
- Total Likes
- Total Retweets
- Platform Distribution
- Sentiment Distribution
- Engagement Analysis
- Country Analysis
- Time-based Analysis

### Dashboard User Flow

```text
USER
  ↓
FILTER
  ↓
VIEW DATA
  ↓
VISUALIZE
  ↓
COMPARE
  ↓
INSIGHT
```

---

# Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **CSV**

---

# Project Structure

```text
SOCIAL-MEDIA-SENTIMENT-ANALYTICS/
│
├── Social_Media_Sentiment_Dataset.csv
│
├── DAV_Lab_Assignment_1_Social_Media_Analysis_FINAL.ipynb
│
├── DAV_Lab_Assignment_3_Social_Media_Analysis.ipynb
│
└── README.md
```

---

# Key Insights

The project focuses on identifying data-supported patterns related to:

1. Social media platform activity
2. Sentiment distribution
3. Likes and Retweets
4. Overall engagement
5. Platform-wise engagement
6. Country-wise activity
7. Monthly posting activity
8. Hourly posting activity
9. Relationship between Likes and Retweets
10. Correlation between numerical variables

All insights are derived from the dataset and corresponding visualizations.

---

# Future Scope

The project can be extended with:

- Interactive dashboards
- Real-time social media data
- Machine Learning-based sentiment classification
- Sentiment prediction
- Trend detection
- Advanced platform comparison
- Automated analytical reports
- Real-time engagement monitoring

---

# Conclusion

**Social Media Sentiment Analytics** demonstrates how raw social media data can be transformed into meaningful information using Data Analytics and Visualization techniques.

The project combines:

- Data Cleaning
- Exploratory Data Analysis
- Sentiment Analysis
- Platform Analysis
- Engagement Analysis
- Country Analysis
- Time Analysis
- Correlation Analysis
- Data Visualization

The complete project follows:

```text
DATA
  ↓
CLEANING
  ↓
ANALYSIS
  ↓
VISUALIZATION
  ↓
INSIGHTS
```

---

# Author

**Manish Kumar**

**Course:** B.Tech CSE (AI/ML)

**Subject:** Data Analytics & Visualization

**Project:** Social Media Sentiment Analytics
