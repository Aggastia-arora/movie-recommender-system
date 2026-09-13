# CineMatch AI

A content-based movie recommendation system built using Python and cosine similarity.

## About

This project recommends movies similar to a movie selected by the user. Movie information is processed and converted into numerical vectors, and cosine similarity is used to find movies with similar content.

## Features

- Recommend movies based on similarity
- Content-based recommendation
- Uses movie metadata for finding similar movies
- Simple Streamlit interface

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Jupyter Notebook

## How It Works

1. Movie data is loaded and processed.
2. Relevant movie information is combined into features.
3. The features are converted into vectors.
4. Cosine similarity is calculated between the movies.
5. The most similar movies are returned as recommendations.

## Project Files

- `app.py` - Streamlit application
- `notebook86c26b4f17.ipynb` - Data processing and model development notebook

## Run the Project

Install the required libraries:

```bash
pip install streamlit pandas numpy scikit-learn
