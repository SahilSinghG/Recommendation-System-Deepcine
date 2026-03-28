# 🎬 Movie Recommendation System (Deepcine)

A content-based movie recommendation system that suggests movies based on user preferences using TF-IDF vectorization and cosine similarity.
The project also includes an interactive Streamlit web application that allows users to search for a movie and receive similar movie recommendations instantly.

## 📌 Project Overview

Recommendation systems are widely used by modern platforms to personalize user experiences. This project demonstrates how machine learning techniques can be used to analyze movie metadata and generate recommendations based on content similarity.

The system analyzes movie attributes such as genres, keywords, and descriptions to compute similarity scores and recommend movies that closely match the user's selected movie.

## 🚀 Features

• Content-based movie recommendation system
• Interactive user interface built with Streamlit
• TF-IDF vectorization for feature extraction
• Cosine similarity for computing movie similarity
• Fast recommendations using precomputed similarity matrices
• Simple and user-friendly interface

## 🧠 Machine Learning Approach

The recommendation engine follows these steps:

1. Data preprocessing
2. Clean movie metadata
3. Combine relevant textual features
4. Feature extraction
5. TF-IDF vectorization is applied to convert text data into numerical vectors
6. Similarity computation
7. Cosine similarity is used to measure similarity between movie vectors
8. Recommendation generation
9. When a user selects a movie, the system returns the most similar movies based on similarity scores

# 🗂 Project Structure

Movie-Recommendation-System
│
├── app.py                  # Streamlit application
├── main.py                 # Core recommendation logic
├── Movies.ipynb            # Model development notebook
├── movies_metadata.csv     # Dataset used for training
├── df.pkl                  # Processed movie dataset
├── indices.pkl             # Movie index mapping
├── tfidf.pkl               # TF-IDF vectorizer
├── tfidf_matrix.pkl        # TF-IDF feature matrix
├── requirements.txt        # Project dependencies
├── runtime.txt             # Python runtime version
└── README.md               # Project documentation
📊 Dataset

The dataset contains movie metadata including:

• Movie titles
• Genres
• Overview / descriptions
• Keywords

This metadata is used to compute similarity between movies and generate recommendations.

## ⚙️ Installation

Clone the repository

git clone https://github.com/SahilSinghG/Recommendation-System-Deepcine
cd movie-recommendation-system

## Install dependencies

pip install -r requirements.txt

▶️ Running the Application

Start Render:

uvicorn main:app --reload

then start the Streamlit app:

streamlit run app.py

Then open your browser at:

http://localhost:8501

## 💻 Tech Stack

Programming Language

Python

Libraries

Pandas
NumPy
Scikit-learn
Streamlit

Machine Learning Techniques:

TF-IDF Vectorization
Cosine Similarity
Content-Based Recommendation

## 📈 Future Improvements

• Hybrid recommendation systems (content + collaborative filtering)
• Deep learning based recommendations
• User preference learning
• Improved UI/UX

## 👨‍💻 Author

Sahil Guleria

Data Science | Machine Learning | Python

LinkedIn: [[LinkedIn]](https://www.linkedin.com/in/sahil-guleria-4b22511bb/)
