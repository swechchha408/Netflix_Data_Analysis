Project Overview
# Netflix_Data_Analysis

This project performs exploratory data analysis (EDA) on Netflix’s catalog dataset to uncover trends, patterns, and insights that can help the company make data-driven decisions about content production, audience targeting, and regional strategies.
The dataset contains details such as title, director, cast, country, release year, rating, duration, and genre for all TV shows and movies available on Netflix.

🎯 Objectives

Analyze the ratio of Movies vs TV Shows on Netflix.

Identify most popular genres and top content-producing countries.

Explore release trends over time.

Examine audience ratings and target demographics.

Find top directors and frequent actors.

Study movie durations and number of seasons for TV shows.

Determine which months Netflix adds the most content.

🧹 Data Preprocessing

Cleaned and standardized column names.

Converted date_added to datetime format and extracted year/month.

Split multi-valued columns (like genre, cast, country) for analysis.

Parsed duration into minutes for movies and seasons for shows.

Handled missing values for director, cast, and country with "Unknown".

📈 Insights

Movies dominate the Netflix catalog compared to TV Shows.

Dramas, Comedies, and Documentaries are the most common genres.

The U.S., India, and the U.K. produce the most Netflix content.

Content addition has risen sharply after 2015.

TV-MA and TV-14 are the most frequent ratings.

Average movie duration ≈ 100 minutes.

December and October see the highest number of new titles added.

🧰 Tools & Libraries Used

🐍 Python

📊 Pandas, NumPy

📉 Matplotlib, Seaborn

📓 Jupyter Notebook
