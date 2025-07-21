# Data-Cleaning
# Prime Video – Data Cleaning

This project focuses on cleaning and preparing a dataset of Prime Video titles for analysis. The raw data includes metadata about movies and TV shows, such as title, release year, duration, country, and genre. Cleaning this data helps make it ready for visualizations, dashboards, or further analysis.

## Dataset

- Source: [Kaggle – Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)
- Format: CSV

## Cleaning Tasks

- Handled missing values in `director`, `cast`, `country`, and `rating` columns
- Converted `date_added` to datetime format
- Split `duration` into numeric value and unit (e.g. 90 minutes, 2 seasons)
- Normalized text columns (lowercase and trimmed whitespace)
- Parsed `listed_in` into genre lists and extracted main genre
- Created new features: `main_country`, `year_added`, `month_added`, and `length_category`
- Dropped duplicate records

## Skills Used

Python, Pandas, Data Cleaning, Feature Engineering, Regular Expressions (RegEx)

## Output

- Cleaned dataset: `cleaned_amazon_prime.csv`
- Ready for analysis or Tableau dashboards

## Next Steps

- Exploratory Data Analysis (EDA)
- Visualization in Python or Tableau
- Genre trends, yearly content growth, and content type breakdown
