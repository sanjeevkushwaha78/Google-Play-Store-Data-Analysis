# 📊 Google Play Store Data Analysis

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) and Feature Engineering on the Google Play Store dataset to uncover insights about app popularity, installs, pricing, and categories.

---

## 🎯 Objectives
- Identify the most popular app categories
- Find apps with highest installs
- Analyze pricing trends
- Understand distribution of ratings and reviews

---

## 📂 Dataset
- Rows: 10,841
- Columns: 20
- Source: Google Play Store Dataset

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧹 Data Cleaning
- Removed invalid and duplicate rows
- Converted data types (Reviews, Size, Installs, Price)
- Handled missing values
- Cleaned special characters (+, $, ,)

---

## ⚙️ Feature Engineering
Extracted:
- Day
- Month
- Year

From `Last Updated` column

---

## 📊 Exploratory Data Analysis

### Numerical Features
- Right Skewed: Reviews, Size, Installs, Price
- Left Skewed: Rating, Year

### Categorical Features
- Majority apps are Free
- Most apps target "Everyone"

---

## 🔍 Key Insights
- Free apps dominate the platform
- Few apps account for most installs
- Ratings are generally high
- App size varies significantly

---

## 📌 Conclusion
The Play Store ecosystem is highly competitive, with free apps leading in popularity. Proper data cleaning and feature engineering are essential for meaningful insights.

---

## 🚀 Future Work
- Build recommendation system
- Perform predictive modeling
- Sentiment analysis on reviews
