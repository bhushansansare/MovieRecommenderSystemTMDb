![Movie Posters](https://drive.google.com/uc?export=view&id=1ygYLSWw6RWqPTrKtpJG4ikNsIacV0TWF)
# Movie Recommender System - TMDb

This is a content based movie recommender system that uses cosine similarity to recommend movies to users. The system takes in a title of movie as input and generates recommendations for a given user based on their movie preferences.

## Features
The system uses the following features to generate recommendations:

- Movie title
- Overview
- Genre
- Actor/Actress
- Director
- Plot keywords

## How it works
1. The system first preprocesses the movie data by converting the movie features into numerical vectors on the basis of the frequency (count) of each word that occurs in the entire text.
2. The system then calculates the cosine similarity between the movie vectors and the user's movie vectors. The cosine similarity measure is a metric used to determine the similarity between two non-zero vectors. It is defined as the dot product of the vectors divided by the product of the vectors' magnitudes.
3. The system then ranks the movies based on their cosine similarity scores and recommends the top 5 movies to the user.
