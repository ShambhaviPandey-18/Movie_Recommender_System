# Content-Based Movie Recommendation System

A Content-Based Movie Recommendation System that suggests movies similar to a user-selected movie based on their features like genres, cast, crew, and keywords.
It uses TF-IDF vectorization and cosine similarity to measure similarity between movies.

Features:
- Recommends movies similar to the one selected by the user.
- Uses content-based filtering (no user ratings required).
- Built using Python, pandas, NumPy, and scikit-learn.

  
Dataset:
- The project uses the TMDB 5000 Movies Dataset, which contains:
- Title of the movie
- Overview (description/summary)
- Genres, Cast, Crew, and Keywords
- Other metadata like popularity, vote count, etc.

How It Works:
1. Data Preprocessing
Extract important features like genres, cast, crew, and keywords.
Combine them into a single text column called tags.

2. Feature Vectorization
Use TF-IDF Vectorizer or Count Vectorizer to convert tags into a numerical vector.

3. Calculate Similarity
Apply Cosine Similarity to measure similarity between movies.

4. Recommend Movies
For a selected movie, find the top 5 most similar movies.

Example Recommendation:

Input: "The Dark Knight"
Output:
Batman Begins
The Dark Knight Rises
Man of Steel
Iron Man
Avengers: Age of Ultron
