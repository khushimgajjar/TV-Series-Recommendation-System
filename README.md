# TV Series Recommendation System

This project is a TV series recommendation system that uses natural language processing and cosine similarity to suggest similar TV series based on their descriptions and parental ratings. 
The system leverages a dataset containing top TV series from IMDb, including a dataset developed by [Khushi Gajjar](https://www.kaggle.com/datasets/khushikhushikhushi) available on [Kaggle Dataset link](https://www.kaggle.com/datasets/khushikhushikhushi/imdb-top-rated-tv-series-dataset), and provides recommendations for a given TV series title.



## Features

- **Data Cleaning**: Removes numerical prefixes from TV series titles.
- **Feature Engineering**: Combines the description and parental rating of each TV series to form a comprehensive feature set.
- **Vectorization**: Uses TF-IDF Vectorizer to convert textual data into numerical vectors.
- **Cosine Similarity**: Computes the similarity between TV series based on their TF-IDF vectors.
- **Recommendations**: Provides a list of the top 10 most similar TV series for a given TV series title.

## Dataset
The
The dataset includes the following columns:

- **Title**: The title of the TV series.
- **Year**: The years during which the TV series was aired.
- **Parental Rating**: The parental rating of the TV series (e.g., TV-MA, TV-14).
- **Rating**: The IMDb rating of the TV series.
- **Number of Votes**: The number of votes the TV series received on IMDb.
- **Description**: A brief description of the TV series.


## How to Run

1. Clone the repository.
2. Ensure you have the necessary libraries installed (`pandas`, `scikit-learn`, `re`).
3. Load the dataset into a DataFrame.
4. Run the script to generate recommendations.

## Notes

- The example dataset provided here is a small subset. You can replace it with a larger dataset of your choice.
- Ensure the dataset does not contain null values before running the recommendation function.


