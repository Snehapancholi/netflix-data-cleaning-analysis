# Netflix Data Cleaning & Analysis 

##  Project Overview
This project performs end-to-end data cleaning, feature engineering, and exploratory data analysis (EDA) on a real-world Netflix dataset.

The goal is to understand Netflix’s content strategy by analyzing trends in content type, genres, countries, durations, and release patterns using Python.

---

##  Data Cleaning
- Handled missing values using appropriate placeholders
- Cleaned and converted date fields into datetime format
- Removed duplicate records
- Processed multi-value columns such as cast, genres, and countries
- Carefully handled missing country data to avoid misleading analysis

---

##  Feature Engineering
- Extracted movie duration in minutes
- Created time-based features (`year_added`, `month_added`, `weekday_added`)
- Derived `main_country`, `num_cast`, `num_genres`, and `multi_country`
- Categorized content length into Short, Medium, and Long

---

##  Exploratory Data Analysis (EDA)
- Movies vs TV Shows trend over time
- Top content-producing countries
- Genre distribution and genre trends over years
- Movie duration distribution and outlier detection
- Most frequent actors and directors
- Content addition patterns by weekday and month

---

##  Key Insights
- Netflix adds more movies than TV shows
- The United States and India dominate content production
- Drama is the most common genre on Netflix
- Most movies are between 60–100 minutes long
- Content is most frequently added during weekdays

---

##  Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Dataset
Netflix Movies and TV Shows dataset sourced from Kaggle.

---

##  Future Improvements
- Build a Streamlit dashboard for interactive exploration
- Integrate IMDb ratings for deeper analysis
- Apply machine learning models for content classification

