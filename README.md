Project Objective:
creating a system that suggests movies based on what users have liked before.

Techniques Used:
Cosine Similarity: This calculates how similar two movies are based on their descriptions or keywords.
Count Vectorizer: It turns words in movie descriptions into numbers the computer can understand, helping with the similarity calculations.

Dataset:
Movies = /kaggle/input/tmdb-movie-metadata/tmdb_5000_movies.csv
credits = /kaggle/input/tmdb-movie-metadata/tmdb_5000_credits.csv
using the TMDB 5000 Movie Dataset, which provides a lot of information about different movies.

Implementation:
Convert movie descriptions into numbers using count vectorization.
Used cosine similarity to compare movies and find similar ones.
Recommend movies that are most similar to ones the user has liked.

Outcome:
Users get recommendations tailored to their tastes.
The system uses advanced techniques to make these recommendations.
This improves user satisfaction by suggesting movies they're likely to enjoy.
