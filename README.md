# 📌 YouTube Trending Videos Dataset — Beginner-Friendly Mini Project

---

## 🔹 Summary

This project provides a **multi-country YouTube trending dataset** from Pakistan, India, and Germany, collected over multiple days.  

It is designed for beginners to practice **Exploratory Data Analysis (EDA), correlation analysis, visualization, and basic predictive modeling**.  

The dataset is structured, real-world, and includes **views, likes, comments, publish date, and country** for each video.  

---

## 🔹 Overview

YouTube trending data reflects what is currently popular across different countries and how users engage with content.  
By analyzing this data, learners can explore **relationships between engagement metrics**, understand trends, and build basic models predicting virality.  

  

---

## 🔹 Problem Statement

Many beginners struggle to find **real, accessible, multi-feature datasets** to practice data science concepts.  

This project addresses that by providing a **ready-to-use YouTube trending dataset** with:

- Multi-country coverage  
- Key engagement metrics (views, likes, comments)  
- Timestamped data  
- Channel information  

Beginners can use it to explore **correlations, trends, and engagement patterns**.  

---

## 🔹 Dataset Description

| Column | Description |
|--------|-------------|
| `video_id` | Unique YouTube video identifier |
| `title` | Video title |
| `channel` | Name of the channel publishing the video |
| `publish_time` | Date and time the video was published |
| `views` | Number of views |
| `likes` | Number of likes |
| `comments` | Number of comments |
| `country` | Country code of trending video |
| `date_collected` | Date the data was collected |
| `engagement_rate` | (likes + comments)/views, optional calculated column |

---

## 🔹 Tools and Techniques

**Tools Used:**

- Python (pandas, glob, datetime)  
- Jupyter Notebook  
- CSV / Excel for data viewing  
- GitHub / Kaggle for sharing  

**Techniques Applied:**

- Data merging and cleaning  
- Handling missing values  
- Sorting and ranking by engagement metrics  
- Exploratory Data Analysis (EDA)  
- Correlation analysis  
- Engagement rate calculation  

---

## 🔹 Key Insights (Examples)

- Top trending videos differ by country  
- Engagement rate helps identify highly interactive content, not just views  
- Likes generally correlate with views, but comments can highlight audience interaction  
- Daily snapshots can show **time-based trends** for virality  

---

## 🔹 How to Run This Project

1. **Clone repository:**

```bash
git clone https://github.com/DataWithAkaasha/youtube-trending-mini-project.git
pip install pandas

## 🔹 Sample Questions / Exercises

Beginners can explore:

- Which country has the highest average engagement rate?
- Does a higher number of likes always mean higher views?
- Which channel consistently produces top trending videos?
- Are comments a better predictor of virality than likes?
- How does publish time affect trending success?
- Identify outliers in views and engagement rate.

---

## 🔹 Results (Example)

- **Top Trending Video Globally:** “Bol Kaffara Kya Hoga” with 35M views
- **Highest Engagement Rate:** 0.12 (likes + comments / views) for a music video
- **Country-wise Trends:** Pakistan showed highest interaction per video on average

> *(Note: Actual results will vary based on dataset snapshots.)*

---

## 🔹 Conclusion

This project provides a **practical, beginner-friendly dataset** to practice data analysis and modeling skills.

- Beginners can explore real-world social media trends  
- Data is clean, structured, and ready for EDA  

---

## 🔹 Future Work

- Collect data continuously to create **time series analysis**  
- Build **predictive models** for video virality  
- Add **more countries** for global comparison  
- Include **sentiment analysis** from video comments  

---

## 🔹 Author

**Jagia**  
BS Mathematics Student | Data Science Enthusiast | Erasmus MATHS-DISC Applicant
