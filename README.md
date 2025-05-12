
# 🎬 Movie Recommendation System

This project is a content-based movie recommendation system developed using Python and Jupyter Notebook. It suggests movies based on user preferences by analyzing the content features of top-rated movies.

## 📁 Project Structure

- `Movie_recommendation_system.ipynb`: Main Jupyter Notebook containing the code and explanation of how the recommendation system works.
- Dataset: The data used is sourced from Kaggle and contains information about 10,000 top-rated TMDB movies.

## 🧠 Features Used

The recommendation system leverages the following features from the dataset:
- Genres
- Keywords
- Overview (plot summaries)

These features are combined into a textual format and then vectorized using **TF-IDF** techniques. Similarities between movies are calculated using **cosine similarity**.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## 💡 How It Works

1. The dataset is cleaned and preprocessed to extract relevant content-based features.
2. Text data is vectorized for similarity computation.
3. The system compares a user's favorite movie with others in the dataset using cosine similarity.
4. It then suggests the most similar movies.

## 📊 Dataset Reference

- Dataset Title: [Top Rated TMDB Movies (10k)](https://www.kaggle.com/datasets/ahsanaseer/top-rated-tmdb-movies-10k?fbclid=IwAR2MpWrWpcw2QNCv_FZg2l0sjBh9xAvhrqtnZBO9K-QS6PHI1aHkdB6qLa0)
- Description: This dataset contains metadata of 10,000 top-rated movies from The Movie Database (TMDB), including genres, cast, crew, and more.

## 🚀 How to Run

1. Make sure you have the required Python libraries installed:
   ```bash
   pip install pandas numpy scikit-learn nltk
   ```
2. Run the Jupyter Notebook `Movie_recommendation_system.ipynb`.

## 📌 Future Improvements

- Adding collaborative filtering techniques.
- Building a web interface using Flask or Streamlit.
- Including user ratings for hybrid recommendations.
