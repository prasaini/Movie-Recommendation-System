# Movie-Recommendation-System

This is a Python Jupyter Notebook project that recommends movies similar to what is entered using TMDB dataset. The recommendation system uses Cosine Similarity, TFIDF Vectorizer, and Count Vectorizer to compute the similarity between the movies.

## Dataset
The dataset used in this project is the TMDB dataset, which contains information about movies and TV shows such as title, overview, release date, budget, revenue, etc. You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

## Concepts Used

### Cosine Similarity
Cosine Similarity is a measure of similarity between two non-zero vectors of an inner product space that measures the cosine of the angle between them. It is often used to measure document similarity in text analysis.

### TFIDF Vectorizer
TF-IDF stands for Term Frequency-Inverse Document Frequency. It is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus. TF-IDF is often used as a weighting factor in information retrieval and text mining.

### Count Vectorizer
Count Vectorizer is a simple method for converting text into a bag-of-words representation, where each word is represented by a count of its occurrences in the text.

## Usage
Open the Jupyter Notebook movie_recommendation_system.ipynb  
Run the notebook cells sequentially.  
Enter the name of the movie you want to get recommendations for.  
The system will output 7 movie names similar to what was entered.  
