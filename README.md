# 📊 Google Play Store EDA & Dashboard Project

## 📌 Project Title

**What Drives App Success on the Google Play Store?**

---

## 📖 Overview

This project performs an **Exploratory Data Analysis (EDA)** on Google Play Store apps and user reviews to identify key factors influencing app success.

The analysis combines:

* App-level data (ratings, installs, price, category)
* User sentiment data (reviews, polarity)

The final output is an **interactive Power BI dashboard** that provides actionable insights.

---

## 🎯 Objectives

* Identify which app categories perform best
* Analyze relationship between ratings and installs
* Compare performance of free vs paid apps
* Evaluate whether user sentiment aligns with ratings
* Understand key drivers of app success

---

## 📂 Dataset

### 1. Google Play Store Dataset

Contains:

* App name
* Category
* Rating
* Reviews
* Installs
* Price
* Type (Free/Paid)

### 2. User Reviews Dataset

Contains:

* App
* Sentiment (Positive/Negative/Neutral)
* Sentiment Polarity
* Subjectivity

---

## 🧹 Data Cleaning

* Removed missing/null values
* Converted:

  * Installs → numeric
  * Price → numeric
  * Reviews → numeric
* Removed invalid entries (e.g., “Free” in numeric columns)
* Merged datasets using **App name**

---

## 📊 Analysis Performed

### ✔ Category Analysis

* Communication and Social apps dominate installs

### ✔ Rating vs Installs

* High ratings do not always guarantee higher downloads

### ✔ Free vs Paid Apps

* Free apps dominate total downloads and market share

### ✔ Sentiment Analysis

* User sentiment varies even among highly rated apps

---

## 📈 Dashboard Features (Power BI)

* KPI Cards:

  * Average Rating
  * Total Downloads
  * Total Apps

* Visualizations:

  * Top Categories by Installs
  * Free vs Paid App Performance
  * Rating vs Installs
  * Rating vs Sentiment

* Interactive Filter:

  * Category slicer

---

## 🧠 Key Insights

* App success is strongly influenced by **category and accessibility**
* Free apps significantly outperform paid apps in downloads
* Ratings alone are not a reliable indicator of success
* User sentiment provides deeper insight than ratings

---

## 🛠 Tools Used

* Python (Pandas, Matplotlib, Seaborn)
* Power BI
* Jupyter Notebook

---

## 🎤 Conclusion

This project demonstrates that:

> **App success is driven more by accessibility and category demand than by ratings alone.**

Combining quantitative metrics with user sentiment provides a more complete understanding of app performance.

---

## 📎 Future Improvements

* Include time-based trends
* Perform predictive modeling
* Add revenue analysis

---

## 👨‍💻 Author

George C A

---
