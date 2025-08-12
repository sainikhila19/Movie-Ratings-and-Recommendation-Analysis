# Movie-Ratings-and-Recommendation-Analysis
## Project Overview
This project analyzes a movie ratings dataset using MovieLens dataset to explore user rating behaviors, identify popular genres, and build a simple movie recommendation system.

## Dataset
**Source:** (https://grouplens.org/datasets/movielens/latest/)

**Description:** The dataset contains millions of movie ratings and metadata including genres and timestamps.

**Files Used:**
`ratings.csv` – User ratings with user ID, movie ID, rating, and timestamp
`movies.csv` – Movie metadata including movie titles and genres

## Objectives
Analyze the distribution of movie ratings to understand user preferences.
Identify the most popular movie genres based on ratings and counts.
Build a simple recommendation system based on collaborative filtering or popularity.
Visualize key insights using Python libraries.

## Tools and Technologies
Python (pandas, numpy, matplotlib, seaborn, scikit-learn)

Jupyter Notebook for analysis and visualization

SQLite or simple SQL queries for data manipulation

## Key Findings
The rating distribution is skewed towards higher ratings (4 and 5 stars), indicating general user positivity.
Popular genres include Drama, Comedy, and Action based on the number of ratings.
The recommendation system provides movie suggestions based on user similarity and popular titles.

## Project Structure

```plaintext
Movie-Ratings-Recommendation/
│
├── data/
│   └── movie.csv                   # Raw dataset with userId, movieId, rating, timestamp
│
├── notebooks/
│   ├── 01_data_exploration.ipynb    # Initial EDA and data cleaning
│   ├── 02_model_training.ipynb      # Building recommendation models
│
├── src/
│   ├── data_preprocessing.py        # Data cleaning and transformation scripts
│   ├── model.py                     # Model building functions
│   ├── evaluation.py                # Model evaluation metrics
│
├── requirements.txt                 # Python dependencies
├── README.md                        # Project documentation
└── .gitignore                       # Files and folders to ignore in Git

