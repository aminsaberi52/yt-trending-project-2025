# yt-trending-project-2025
Data analysis project based on the multi-country YouTube Trending dataset. Includes dataset integration, data cleaning, feature engineering, time-based clustering, and analytical tasks required by the 2025–26 Foundations of Computer Science course.

# Dataset should be placed locally in trendingYT/ folder

📊 YouTube Trending Data Analysis
Foundations of Computer Science — Project 2025–26

This repository contains a complete data analysis project based on the Trending YouTube Videos dataset, developed in Python using Jupyter Notebook.
The project focuses on data cleaning, merging, feature extraction, and analytical tasks across multiple countries.

🚀 Project Overview

This project includes:

📁 Merging all country-specific CSV files into a single unified dataset

🧹 Data cleaning and filtering

📊 Analytical insights on views, tags, ratios, and categories

⏱️ Time-based clustering

🌍 Country-level comparisons

🗂️ Category mapping from JSON metadata

📈 Identifying top-performing videos by date and month

All analysis steps, transformations, and explanations are documented inside the notebook.

📌 Main Features
🔹 Data Preparation

Concatenation of all CSV files

Adding a country column

Handling empty or non-informative tags ("", "[none]", whitespace)

🔹 Filtering & Cleaning

Extracting videos without tags

Detecting disabled comments, disabled ratings, or removed videos

Creating an excluded dataset and cleaning the main dataframe

🔹 Feature Engineering

Computing like_ratio = likes / dislikes

Clustering publish times into 10-minute intervals

Splitting trending dates into year, month, and day

🔹 Analytical Tasks

Total views per channel

Most common tags

Like/dislike ratio per (tag, country)

Most-viewed videos per (trending_date, country)

Most-viewed videos per (month, country)

🔹 Category Validation

Reading category JSON files

Detecting videos with missing or invalid category assignments

📂 Folder Structure
📁 trendingYT/
    ├── CAvideos.csv
    ├── USvideos.csv
    ├── ... (other country CSVs)
    ├── CA_category_id.json
    ├── ... (other JSON files)

📄 finalProject.ipynb   ← Main analysis notebook

README.md

🛠️ Technologies Used

Python 3

Pandas

NumPy

Matplotlib / Seaborn

JSON handling

Jupyter Notebook

🎓 Course Information

This project was developed for the
Foundations of Computer Science — Academic Year 2025/2026
Università degli Studi di Milano–Bicocca.
