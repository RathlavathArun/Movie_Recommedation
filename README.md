🎬 Movie Recommendation System
A personalized movie recommendation system built using collaborative filtering with the K-Nearest Neighbors (KNN) algorithm. This system suggests similar movies based on user ratings and preferences using the MovieLens dataset.

🚀 Features
Collaborative filtering using KNN (user-based or item-based).

Efficient use of sparse matrix representation for memory optimization.

Real-time input to search movies and get top similar recommendations.

Handles large datasets with ease using SciPy's sparse matrix and sklearn.

🧠 Algorithms Used
Collaborative Filtering

K-Nearest Neighbors (KNN) using sklearn.neighbors

Cosine Similarity for distance metric

📦 Requirements
Make sure the following packages are installed:

pip install pandas numpy scikit-learn scipy

🧪 How to Run
Clone the repository:
git clone https://github.com/RathlavathArun/Movie_Recommedation.git
cd movie-recommendation-system

Launch the notebook:
jupyter notebook movierecomdetation.ipynb

Run all the cells in sequence and provide a movie name when prompted.

📝 Usage Example
You will be prompted:
Enter a movie name (or type 'exit' to quit):
> Toy Story
The system will then print the top 10 most similar movies to "Toy Story" based on user ratings.

📊 Dataset Source
This project uses a subset of the MovieLens Dataset (GroupLens) which contains:

movies.csv: Movie IDs and titles

ratings.csv: User ID, Movie ID, Rating, and Timestamp