# 🎬 Movie Recommender System

A simple and effective content-based movie recommender system built using Python, NLP, and Streamlit. This app suggests movies similar to a selected movie using keyword extraction, cosine similarity, and metadata from the TMDB 5000 dataset.

---

## 📦 Features

- Recommends top 5 similar movies based on metadata.
- Utilizes movie descriptions, cast, crew, genres, and keywords.
- Visual display of movie posters using TMDB API.
- Interactive Streamlit interface for users.

---

## 🛠️ Tech Stack

- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, NLTK, Streamlit, Requests
- **NLP:** CountVectorizer, PorterStemmer
- **Similarity Metric:** Cosine Similarity
- **Frontend:** Streamlit
- **API:** TMDB API for fetching movie posters

---

## 📂 Dataset

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

Both datasets are publicly available and were loaded and preprocessed for extracting important tags for each movie.

---

## 🚀 Getting Started

### 🔧 Installation

```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
pip install -r requirements.txt
