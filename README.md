# Movie-Recommender-System

📘 Overview

This project builds a personalized movie recommendation system using collaborative filtering and matrix factorization to suggest movies based on user preferences. It leverages user ratings, demographics, and movie metadata to enhance viewing experience.

🎯 Objective

To recommend movies similar to those a user has liked or rated, using techniques like Pearson Correlation, Cosine Similarity, and Matrix Factorization (SVD).

📂 Dataset

Dataset: MovieLens (Google Drive)

ratings.dat – UserID, MovieID, Rating, Timestamp

users.dat – Gender, Age, Occupation, Zip-code

movies.dat – Title, Genres

🧠 Approaches

Item-Based Collaborative Filtering (Pearson):
Finds similar movies based on correlation of user ratings.
Example → “Liar Liar” → “The Mask”, “Ace Ventura”, “Bruce Almighty”

Cosine Similarity (KNN):
Uses vector-based similarity to recommend top 5 similar movies.

Matrix Factorization (SVD):
Learns latent user & movie features for prediction.
Results: RMSE ≈ 0.89 | MAPE ≈ 12.4%

📊 Key Insights

Most users: 25–34 age group, majority Male

Top occupations: Programmers & Students

Most movies released in 1990s

Popular movie: “American Beauty”

⚙️ Tech Stack

Python, Pandas, NumPy, scikit-learn, Surprise, Matplotlib, Seaborn, Jupyter Notebook

✅ Conclusion

The system successfully recommends personalized movies using collaborative filtering and latent factor models, improving user engagement and satisfaction.
