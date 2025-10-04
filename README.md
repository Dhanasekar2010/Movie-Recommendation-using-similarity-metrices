# Movie-Recommendation-using-similarity-metrices

🎬 Movie Recommendation System

This project is a content-based movie recommendation system implemented in a Google Colab.
It leverages similarity measures such as cosine similarity and Euclidean distance to suggest movies most similar to a given title.

🚀 Features

Load and process movie data from a CSV file

Compute pairwise similarity between movies

Generate recommendations using the recommended_movie() function

Support for multiple similarity measures

Step-by-step notebook implementation for easy learning

📂 Project Structure
.
├── movie_recommendation.ipynb   # Main Jupyter Notebook
├── movie.csv                    # Dataset (required)
└── README.md                    # Documentation

# Manually install:

pip install pandas numpy scikit-learn

# 📊 Dataset

The notebook requires a dataset file named movie.csv in the root directory.
A typical structure may look like this:

movie_id	title	genre	features (vectorized)
1	The Matrix	Sci-Fi	...
2	Inception	Sci-Fi	...
3	Titanic	Romance	...

👉 Ensure your dataset has descriptive attributes (genres, keywords, or embeddings) for meaningful similarity calculations.

# 🛠️ Usage

Launch Jupyter Notebook:
jupyter notebook movie_recommendation.ipynb
Run all cells sequentially.
Use the recommendation function:
recommended_movie("Inception"
The output will list the most similar movies based on the dataset.

# 📈 Example Output

For input "Inception", the system might recommend:

1. Interstellar
2. The Matrix
3. Shutter Island


#🧰 Technologies Used

Python 3.x
Pandas & NumPy for data handling
Scikit-learn for similarity metrics
