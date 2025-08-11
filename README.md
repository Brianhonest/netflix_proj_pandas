📺 Netflix Movies and TV Shows Analysis
Author: Your Name
Dataset: Netflix Movies and TV Shows – Kaggle
Tools: Python, Pandas, Matplotlib, Jupyter Notebook

📌 Project Overview
This project explores Netflix’s catalog of movies and TV shows to uncover trends in content type, countries of origin, genres, and release timelines.
The dataset contains 8,807 titles with metadata including release year, director, cast, country, genre, and date added to Netflix.

📂 Dataset
Rows: 8,807

Columns: 12 (show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description)

Missing Data: director, cast, country, date_added, rating, and duration contain NaN values.

🔍 Analysis Steps
Data Cleaning

Removed duplicates.

Converted date_added to datetime format.

Filled missing countries with “Unknown”.

Exploratory Data Analysis

Distribution of Movies vs TV Shows.

Top countries producing Netflix content.

Content added per year (growth trend).

Most common genres.

Visualization

Bar plots, line charts, and category counts.

📊 Key Insights
Movies dominate Netflix’s catalog (~70% of titles).

USA is the top content producer, with Japan ranking unexpectedly high.

2019 saw the peak in titles added, followed by a drop in 2020 (likely COVID-19 impact).

International Movies is the most common genre, surpassing action-oriented content.

🛠 Technologies Used
Python – data cleaning and analysis

Pandas – data manipulation

Matplotlib – data visualization

Jupyter Notebook – interactive coding environment




