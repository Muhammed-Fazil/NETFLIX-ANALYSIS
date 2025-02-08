# Netflix Data Analysis

This project involves analyzing and preprocessing a Netflix dataset (`netflix_titles.xlsx`). It includes various TV shows and movies available on Netflix, with information such as titles, directors, cast, country of origin, release year, ratings, duration, genres, and descriptions.

## Key Tasks Performed

- **Data Loading:** Loaded the dataset using Pandas and displayed basic information.
  
- **Data Cleaning:**
  - Handled missing values in key columns (e.g., director, cast, country, rating, and date_added).
  - Removed duplicate entries.
  - Converted categorical ratings into numerical values for easier analysis.
  - Standardized the duration column (e.g., converted "2 Seasons" into minutes).

- **Data Transformation:**
  - Split the `listed_in` column (which contains multiple genres) into separate rows.
  - Converted `date_added` into a datetime format.

- **Exploratory Data Analysis (EDA):** Performed basic statistical summaries and data exploration to understand the structure of the dataset.

## Libraries Used

- **Pandas:** Data manipulation and analysis.
- **NumPy:** Numerical operations.
- **Matplotlib & Seaborn:** Data visualization (though not extensively used in this notebook).

## Purpose

This notebook is designed to preprocess and clean the Netflix dataset, making it ready for further analysis, visualization, or machine learning tasks. It serves as a foundational step in understanding the dataset and preparing it for more advanced workflows.

## Dataset Source

The dataset used in this notebook is `netflix_titles.xlsx`, which contains information about Netflix titles, including both movies and TV shows.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
