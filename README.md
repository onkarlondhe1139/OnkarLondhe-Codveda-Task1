# OnkarLondhe-Codveda-Task1

---
# Task 1: Power Query for Data Transformation

## Project Overview

This project demonstrates the use of **Microsoft Excel Power Query** to perform **data extraction, transformation, and loading (ETL)** on a social media sentiment dataset.
The objective is to automate data cleaning, restructuring, and preparation for analytical use.

Power Query enables efficient handling of large datasets by creating a repeatable and automated data transformation workflow.

---

# Dataset Information

Dataset: Social Media Sentiment Dataset

Total Records: 732
Total Columns: 15

Key Fields Included

Text – Social media post content

Sentiment – Positive / Neutral / Negative classification

Timestamp – Date and time of post

User – Username

Platform – Social media platform

Hashtags – Hashtags used in posts

Likes – Number of likes

Retweets – Number of retweets

Country – User location

---

# Tools & Technologies

Microsoft Excel

Power Query Editor

Data Transformation Techniques

ETL Workflow

---

# Power Query Workflow

The project follows the **ETL (Extract – Transform – Load)** process.

## 1. Extract

Imported dataset using:

Data → Get Data → From CSV

Power Query automatically detected columns and data structure.

---

## 2. Transform

### Data Cleaning

Removed unnecessary columns such as index columns.

Handled missing values and ensured data consistency.

---

### Data Type Conversion

Assigned correct data types to columns.

Examples

Timestamp → DateTime
Likes → Whole Number
Retweets → Whole Number
Sentiment → Text

---

### Column Splitting

The Timestamp column was split to extract date and time information.

Example

Timestamp → Date + Time

This enables time-based analysis.

---

### Data Filtering

Filtered records to remove invalid values and blank entries.

Ensures high data quality for analysis.

---

### Data Aggregation

Used **Group By** feature to generate summarized insights.

Examples

Sentiment Distribution
Platform-wise engagement
Country-wise activity

---

### Data Shaping

Applied transformations including

Sorting data
Removing duplicates
Restructuring columns for better analysis

---

### Engagement Metric Creation

Created a custom column to calculate engagement.

Formula

Engagement = Likes + Retweets

This metric helps identify highly interactive posts.

---

## 3. Load

The transformed dataset was loaded back into Excel using:

Close & Load

The final cleaned dataset is ready for analysis and visualization.

---

# Key Insights

Positive sentiment posts generate higher engagement.

Twitter contains the highest number of posts in the dataset.

Posts with hashtags show higher interaction levels.

Engagement tends to increase during evening hours.

Some countries show stronger positive sentiment trends.

---

# Project Files

Dataset – https://github.com/onkarlondhe1139/OnkarLondhe-Codveda-Task1/blob/main/3)%20Sentiment%20dataset.csv

Excel File – 

Workflow Diagram – 

<img width="2046" height="1239" alt="Screenshot 2026-02-23 151655" src="https://github.com/onkarlondhe1139/OnkarLondhe-Codveda-Task1/blob/main/Workflow.png" />


# Skills Demonstrated

Power Query

Data Cleaning

Data Transformation

ETL Pipeline Implementation

Data Aggregation

Automation using Query Refresh

---

# Future Improvements

Create Power BI dashboard for visualization

Automate refresh using scheduled data pipelines

Perform deeper sentiment trend analysis

---
