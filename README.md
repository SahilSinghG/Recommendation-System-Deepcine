🎬 DeepCine – Neural Network Powered Movie Recommendation System

DeepCine is a production-ready AI-powered movie recommendation system that delivers personalized movie suggestions using a neural network–based recommendation engine. The system is built with a scalable FastAPI backend and an interactive Streamlit frontend, deployed on cloud platforms for real-time recommendations.

The system analyzes movie features and learned representations to compute similarity scores and recommend relevant movies efficiently.

🚀 Live Demo

🔹 Frontend (Streamlit): https://your-streamlit-url.streamlit.app

🔹 Backend (FastAPI on Render): [https://your-render-backend-url.onrender.com](https://recommendation-system-deepcine.onrender.com)

🔹 API Docs: [https://your-render-backend-url.onrender.com/docs](https://recommendation-system-deepcine.onrender.com/docs)

🧠 Features

Neural network–based recommendation engine

Real-time personalized movie recommendations

Scalable FastAPI backend

Interactive Streamlit frontend

REST API architecture

Cloud deployment (Render + Streamlit Cloud)

High-performance similarity computation

Production-ready modular architecture

🏗️ System Architecture
User
 ↓
Streamlit Frontend (UI)
 ↓
FastAPI Backend (Render)
 ↓
Neural Network Recommendation Engine
 ↓
Similarity Computation
 ↓
Recommended Movies Returned to User

🛠️ Tech Stack
Backend

FastAPI

Python 3.11

Uvicorn

Frontend

Streamlit

Machine Learning

Neural Networks

Scikit-learn

NumPy

Pandas

Deployment

Render (Backend Deployment)

Streamlit Cloud (Frontend Deployment)

Dataset

MovieLens Dataset

🧠 Machine Learning Approach

DeepCine uses a neural network–based approach to learn latent feature representations of movies.

Steps involved:

Data preprocessing and feature extraction

Neural network learns movie embeddings

Similarity scores computed between movie embeddings

Top similar movies returned as recommendations

This approach improves recommendation accuracy compared to traditional filtering methods.

🔌 API Endpoints
Get Home Feed
GET /home


Returns trending or popular movies.

Get Recommendations
GET /recommend?movie_name=Inception


Returns similar recommended movies.

API Documentation
/docs

⚙️ Local Installation
Clone repository
git clone https://github.com/SahilSinghG/Recommendation-System-Deepcine.git
cd Recommendation-System-Deepcine

Create virtual environment
python -m venv venv
venv\Scripts\activate

Install dependencies
pip install -r requirements.txt

Run backend
uvicorn main:app --reload


Backend runs at:

http://127.0.0.1:8000

Run frontend
streamlit run app.py


Frontend runs at:

http://localhost:8501

☁️ Deployment

Backend deployed on:

Render using FastAPI

Frontend deployed on:

Streamlit Cloud

📈 Future Improvements

User-based recommendation

Hybrid recommendation system

Deep learning optimization

Docker containerization

Database integration

Scalable distributed architecture

👨‍💻 Author

Sahil Guleria

GitHub: https://github.com/SahilSinghG

LinkedIn: (add your LinkedIn)

⭐ Why this project is important

This project demonstrates:

Real-world ML system design

Neural network–based recommendation engine

Backend API development

Frontend integration

Cloud deployment

Production-level architecture
