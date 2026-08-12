# 📊 Twitter Engagement Analytics Dashboard

A **Power BI dashboard project** built to analyze Twitter engagement data and identify patterns in audience interactions, media performance, engagement rates, and top-performing tweets.

## 📌 Project Overview

This project analyzes a Twitter Analytics Dataset using **Microsoft Power BI**. Multiple visualizations, filters, calculated columns, measures, and time-based conditions were used to explore different aspects of tweet engagement.

The project was completed as part of a **Data Analytics internship at ElevanceSkills**.

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **DAX**
* **Power Query**
* **Twitter Analytics Dataset**

## 📈 Project Tasks

### 1. Tweet Interaction Breakdown by Category

* Compared **URL Clicks, Profile Clicks, and Hashtag Clicks**.
* Used Tweet Categories to analyze different types of interactions.
* Applied filters based on tweet date, word count, and visibility time.
* The Word Count > 40 condition resulted in no records because the maximum word count in the dataset was 36.

### 2. Engagement Rate Comparison

* Compared **Average Engagement Rate** for tweets with and without App Opens.
* Applied weekday, time, impression, date, character count, and text-based filters.
* Implemented a visual visibility condition based on IST time intervals.

### 3. Media Interaction by Day of Week

* Compared **Media Views and Media Engagements** by day of the week.
* Focused on **Q4 2020**.
* Used a Line and Clustered Column Chart.
* Added a **Max Line** to highlight the highest interaction level.

### 4. Replies, Likes & Retweets

* Compared total **Replies, Likes, and Retweets**.
* Used SUM aggregation.
* Filtered tweets between **June and August 2020**.
* The visualization provides an overview of overall audience interaction.

### 5. Monthly Engagement Rate Trend

* Analyzed the monthly trend of **Average Engagement Rate**.
* Compared tweets **with media vs. without media**.
* Used Month Number to maintain the correct chronological order.

### 6. Top 10 Tweets by Engagement

* Created a **Total Engagement** measure using Retweets + Likes.
* Identified the **Top 10 tweets** based on combined engagement.
* Applied filters for weekdays, impressions, tweet dates, and word count.
* Added a time-based visual visibility condition.

## 📊 Dashboard Features

The final Power BI dashboard includes visualizations for:

* 📌 Engagement Rate
* 📌 Total Engagement
* 📌 Likes
* 📌 Retweets
* 📌 Replies
* 📌 Media Views
* 📌 Media Engagements
* 📌 Tweet Categories
* 📌 Top Performing Tweets
* 📌 Monthly Engagement Trends

  <img width="1315" height="732" alt="Screenshot 2026-08-11 225718" src="https://github.com/user-attachments/assets/40357c11-c24c-4948-b33b-7126e6aa6579" />


## 🧮 DAX & Data Transformation

The project involved creating calculated columns and measures for analysis, including:

* Date and time-based columns
* Day Name
* Month Name
* Year
* Word Count
* Tweet Categories
* Total Engagement
* Visual Visibility Measures

These transformations helped prepare the dataset for filtering and visualization in Power BI.

## 📂 Project Structure

```text
Twitter-Engagement-Analytics/
│
├── 📊 Twitter_Engagement_Dashboard.pbix
├── 📄 Twitter_Dashboard_Report.docx
├── 📁 Dataset/
│   └── Twitter_Analytics_Dataset.xlsx
├── 📁 Screenshots/
│   └── Dashboard screenshots
│
└── README.md
```

## 🎯 Key Outcomes

The project demonstrates how Power BI can be used to:

* Analyze social media engagement.
* Compare different engagement metrics.
* Identify high-performing tweets.
* Analyze media interaction patterns.
* Track engagement trends over time.
* Apply complex filtering conditions.
* Create calculated measures using DAX.
* Build an interactive analytical dashboard.

## 👩‍💻 Author

**Karina**
Data Analytics Intern
**ElevanceSkills**

---

⭐ If you find this project useful, feel free to explore the dashboard and analysis.
