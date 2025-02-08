# Netflix Data Analysis

This project involves analyzing and preprocessing a Netflix dataset (`netflix_titles.xlsx`) that contains information about various TV shows and movies available on Netflix, including titles, directors, cast, country of origin, release year, ratings, duration, genres, and descriptions.

## Key Tasks Performed

- **Data Loading**: The dataset is loaded using Pandas, and basic information is displayed.
- **Data Cleaning**:
  - Handling missing values in key columns like `director`, `cast`, `country`, `rating`, and `date_added`.
  - Removing duplicate entries.
  - Converting categorical ratings into numerical values.
  - Standardizing the `duration` column (e.g., converting "2 Seasons" into minutes).
- **Data Transformation**:
  - Splitting the `listed_in` column (which contains multiple genres) into separate rows.
  - Converting `date_added` into a datetime format.
- **Exploratory Data Analysis (EDA)**: Performing basic statistical summaries and data exploration to understand the structure of the dataset.

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization (though not extensively used in this notebook).

## Purpose

This notebook is designed to preprocess and clean the Netflix dataset, making it ready for further analysis, visualization, or machine learning tasks. It serves as a foundational step in understanding the dataset and preparing it for more advanced workflows.

## Dataset Source

The dataset used in this notebook is `netflix_titles.xlsx`, which contains information about Netflix titles, including both movies and TV shows.

## How to Run

1. Clone the repository:  
   `git clone https://github.com/yourusername/netflix-data-analysis.git`

2. Install the required dependencies:  
   `pip install -r requirements.txt`

3. Open and run the Jupyter Notebook:  
   `jupyter notebook`

