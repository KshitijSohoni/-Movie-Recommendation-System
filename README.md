# -Movie-Recommendation-System

This Python project implements a movie recommendation system that analyzes plot summaries, genres, actors, and directors to suggest similar movies. It leverages text preprocessing techniques and TF-IDF (Term Frequency-Inverse Document Frequency) to create a vector representation of each movie's content, enabling the calculation of cosine similarity between movies.

### Data Preprocessing
- Clean plot summaries: Removes non-alphanumeric characters, extra spaces, and converts everything to lowercase for consistent analysis.
- Remove stopwords: Excludes common words like "the," "a," "an," etc., focusing on content-bearing terms.
- Clean other text fields: Processes genre, actor, and director data for compatibility with the vectorizer.

### TF-IDF Vectorization
- Creates a document-term matrix where each row represents a movie and each column represents a unique word.
- Weights words based on their frequency within a movie (TF) and how rare they are across all movies (IDF), emphasizing words that are distinctive to a specific movie.

### Cosine Similarity
Calculates cosine similarity between movie vectors, capturing the degree of similarity based on the angle between the vectors in a high-dimensional space.
Higher cosine similarity indicates more similar movies.


## Example 
![image](https://github.com/KshitijSohoni/-Movie-Recommendation-System/assets/108518838/a0c35074-b51f-44a0-83db-d5070f05e0ea)

  
