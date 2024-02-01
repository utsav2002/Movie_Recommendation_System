# Movie_Recommendation_System

Description:
This project develops a movie recommendation system using Python. It aims to suggest movies similar to the user's preferences. The system utilizes a dataset containing various movie attributes (such as genres, keywords, tagline, cast, and director) to generate recommendations. By processing this data, the system identifies movies with similar features to the user's favorite movie, leveraging techniques like TF-IDF vectorization and cosine similarity for efficient similarity scoring.

Dataset:
The recommendation system uses a dataset named movies.csv, which includes details such as movie genres, keywords, taglines, cast, and directors, essential for determining movie similarities.

Technologies(Librarires) Used:
- Python: The core programming language for implementing the recommendation logic.
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Scikit-learn: Specifically, the TfidfVectorizer for converting text data into a matrix of TF-IDF features, and cosine_similarity to compute similarity scores between movies.
- Difflib: To find the closest match of the user's favorite movie within the dataset.

Outcomes:
The system successfully recommends a list of movies similar to a given input movie. It demonstrates the practical application of text vectorization and similarity measures in creating a recommendation engine. The model's effectiveness was showcased through examples where users input movies like "Iron Man" and "Cargo," and the system provided a list of movies with thematic and feature-based similarities.
