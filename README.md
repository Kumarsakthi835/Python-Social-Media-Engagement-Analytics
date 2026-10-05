# 📱 Social Media Engagement Analytics Using Python

## 📌 Project Overview

This project analyzes social media engagement data containing 5000 records
across multiple platforms and countries. The analysis includes data cleaning,
transformation, statistical analysis, and comprehensive visualizations using
Pandas, Matplotlib, Seaborn, and Plotly to extract meaningful insights about
user behavior and content performance.

---

## 🎯 Project Objectives

- Load and clean social media engagement dataset
- Handle missing values and duplicates
- Perform exploratory data analysis
- Create new engagement metrics
- Generate statistical insights
- Build 13+ visualizations across Matplotlib, Seaborn, and Plotly
- Extract actionable insights about content performance

---

## 📂 Assignment Information

| Item | Details |
|------|---------|
| **Assignment Name** | Python DA – Social Media Engagement Analytics |
| **Module** | Data Analytics (DA) – Module 5 |
| **Dataset** | social_media_engagement_5000.csv |
| **Records** | 5000 rows × 19 columns |
| **Tool Used** | Google Colab |
| **Language** | Python 3 |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Plotly |

---

## 🛠 Tools & Technologies

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

---

## 📁 Dataset Description

| Column | Description |
|--------|-------------|
| user_id | Unique user identifier |
| age | User age |
| gender | User gender |
| country | User country |
| post_type | Type of post (image/reel/text/video) |
| post_category | Category of post |
| likes | Number of likes |
| comments | Number of comments |
| shares | Number of shares |
| watch_time_sec | Watch time in seconds |
| impression_count | Total impressions |
| posted_at | Post date and time |
| follower_count | Number of followers |
| is_verified | Verified account status |
| device_type | Device used (mobile/tablet/desktop) |
| sentiment | Post sentiment |
| hashtags | Hashtags used |
| engagement_rate | Engagement rate |

---

## 📝 Tasks Completed

### Task 1 – Data Import & Setup
- Imported CSV using Pandas
- Verified data types
- Converted posted_at to datetime format

### Task 2 – Data Cleaning
- Detected missing values in 6 columns
- Filled numerical columns with median
- Filled categorical columns with mode
- Removed duplicates
- Standardized gender and sentiment labels
- Fixed unrealistic values
- Extracted hashtag count

### Task 3 – Data Exploration
- Viewed dataset structure with head, tail, shape
- Checked data types with info() and dtypes
- Generated summary statistics with describe()
- Analyzed categorical distributions
- Created correlation matrix
- Grouped data by post_type and country

### Task 4 – Data Wrangling
- Created engagement_score metric
- Added log-transformed metrics
- Extracted hour, day, month from posted_at
- Performed groupby summaries
- Combined verified and non-verified DataFrames

### Task 5 – Statistical Analysis
- Computed mean, median, mode
- Calculated standard deviation and variance
- Found percentiles (25th, 75th)
- Computed skewness and kurtosis

### Task 6 – Data Visualization (13 plots)
- Scatter, Line, Bar, Pie, Histogram, Box (Matplotlib)
- Count, Bar, Violin, Pair, Heatmap, Swarm (Seaborn)
- Interactive Scatter Chart (Plotly)

### Task 7 – Final Insights
- Content performance analysis
- User behavior trends
- Device and time analysis
- Sentiment impact analysis

---

## 📸 Screenshots

### Task 1 – Data Import and Setup
<img width="561" height="280" alt="image" src="https://github.com/user-attachments/assets/cf5d6531-857e-4941-bb06-cb679acb248f" />

<img width="575" height="294" alt="image" src="https://github.com/user-attachments/assets/102cf9c8-9184-4ad8-927e-025b33af258f" />

<img width="850" height="298" alt="image" src="https://github.com/user-attachments/assets/49c5b398-a3ea-4ee0-ac89-38e878749fc6" />




### Task 2 – Data Cleaning
<img width="585" height="307" alt="image" src="https://github.com/user-attachments/assets/8d9c7ad3-7943-48c6-94d6-13fe269ea122" />

<img width="527" height="362" alt="image" src="https://github.com/user-attachments/assets/1bdb1cef-7428-41ab-87db-121903060e42" />

### Task 3 – Data Exploration

<img width="353" height="320" alt="image" src="https://github.com/user-attachments/assets/e71f5f17-2f52-47ab-aec3-2a2ab9535674" />

<img width="364" height="359" alt="image" src="https://github.com/user-attachments/assets/6be5b1d0-0312-4156-b812-004d0f5fdfb9" />

### Task 4 – Data Wrangling
<img width="549" height="262" alt="image" src="https://github.com/user-attachments/assets/6b8af672-9136-4d12-b611-fadad54b188d" />

<img width="416" height="251" alt="image" src="https://github.com/user-attachments/assets/5235e8e1-ff44-4df3-9700-ac93488dc2da" />



### Task 5 – Statistical Analysis
<img width="533" height="204" alt="image" src="https://github.com/user-attachments/assets/0ed8c5fa-fe5d-4ef3-9d9f-90146db99f7d" />


### Plot 1 – Scatter: Likes vs Impressions

<img width="480" height="332" alt="image" src="https://github.com/user-attachments/assets/bd01f2e4-72c7-4206-a65c-fac2ca88accd" />


### Plot 2 – Line: Daily Engagement Trend
<img width="514" height="281" alt="image" src="https://github.com/user-attachments/assets/8d9627a7-b09f-4d52-a666-66592d0aeb7c" />


### Plot 3 – Bar: Posts by Category
<img width="514" height="281" alt="image" src="https://github.com/user-attachments/assets/931ef1ae-aa68-4f8b-96ea-53c1b3a08cce" />


### Plot 4 – Pie: Gender Distribution
<img width="531" height="308" alt="image" src="https://github.com/user-attachments/assets/bb1176b2-6364-4f27-8472-9a05b1b99f82" />


### Plot 5 – Histogram: Age Distribution
<img width="506" height="269" alt="image" src="https://github.com/user-attachments/assets/548f2856-5816-43aa-825a-56ba0ebb0dd1" />


### Plot 6 – Box: Engagement Rate

<img width="440" height="263" alt="image" src="https://github.com/user-attachments/assets/2d7c373a-c1fe-4ed2-b72a-e43f5b0eef78" />


### Plot 7 – Count Plot: Post Type
<img width="416" height="263" alt="image" src="https://github.com/user-attachments/assets/7ca5cb43-e2f8-4777-9509-805365c7df4d" />


### Plot 8 – Bar: Avg Likes by Category
<img width="407" height="273" alt="image" src="https://github.com/user-attachments/assets/c189c9f0-5240-41fe-8886-7f54e991366f" />


### Plot 9 – Violin: Followers vs Sentiment
<img width="442" height="270" alt="image" src="https://github.com/user-attachments/assets/8606b7ce-07ea-46b7-af1d-e5b4a31f9ad7" />


### Plot 10 – Pair Plot: Numeric Features
<img width="533" height="83" alt="image" src="https://github.com/user-attachments/assets/823ac67e-8a05-4b27-ae98-1645ee827a12" />

<img width="511" height="313" alt="image" src="https://github.com/user-attachments/assets/f7d2d230-375c-4def-8b4a-5ab141596bad" />


### Plot 11 – Heatmap: Correlation Matrix
<img width="479" height="362" alt="image" src="https://github.com/user-attachments/assets/f87ce089-4f2a-4612-ba3e-9d2e73a885a7" />


### Plot 12 – Swarm: Engagement vs Device

<img width="563" height="323" alt="image" src="https://github.com/user-attachments/assets/68907d55-0bc5-4d4e-8f9d-193f82604e49" />


### Plot 13 – Plotly Interactive: Likes vs Impressions

<img width="902" height="278" alt="image" src="https://github.com/user-attachments/assets/05b5f5cc-eb3f-4827-8dc8-7f431dfd4888" />


### Task 7 – Final Insights

<img width="485" height="310" alt="image" src="https://github.com/user-attachments/assets/edae078f-3265-49d0-810f-ae89176df928" />

<img width="545" height="355" alt="image" src="https://github.com/user-attachments/assets/dd0c766b-3d96-4653-a213-a62c504b0bd9" />



---

## 🔍 Key Insights

### 📊 Content Performance
- Reels and Videos generated highest engagement rates
- Tech and Fitness categories had the highest average likes
- Brazil and Canada showed higher engagement rates

### 👤 User Trends
- Users aged 25-35 showed highest engagement
- Verified accounts had slightly higher engagement rates
- Female users had marginally higher engagement than male users

### ⏰ Behavioral Insights
- Evening hours generated highest impressions
- Mobile users had higher watch time than desktop users
- Weekend posts showed better engagement trends

### 💬 Sentiment Analysis
- Positive sentiment posts outperformed others
- Neutral posts had moderate engagement
- Negative sentiment had lowest engagement rates

---

## 🎓 Skills Demonstrated

- Data Loading and Type Conversion
- Missing Value Handling and Imputation
- Duplicate Detection and Removal
- Feature Engineering
- Statistical Analysis
- Matplotlib Visualizations
- Seaborn Visualizations
- Plotly Interactive Charts
- GroupBy Aggregations
- Insight Generation

---

---

## 👨‍💻 Author

**Kumar S**
- Data Analyst
- Python Module End Assignment – Social Media Engagement Analytics
