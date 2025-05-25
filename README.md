# 🎬 Netflix Movies Recommender System

This project is a **Content-Based Filtering Recommender System** built using Python, scikit-learn, and TF-IDF vectorization. It recommends similar Netflix shows/movies based on their descriptions.

---

## 📌 Project Description

The notebook demonstrates how to build a **content-based recommendation system** using the TF-IDF technique to vectorize movie/show descriptions and measure similarity via **cosine similarity**.

Given a title (e.g., *"The Crown"*), the system recommends other similar titles from the dataset based on textual similarity of the descriptions.

---

## 🚀 Features

- 📖 Content-based filtering
- 🧠 TF-IDF vectorization
- 📐 Cosine similarity for ranking
- 📊 Cleaned Netflix dataset
- ✅ Robust error handling if title not found
- 🔍 Top-N recommendations

---

## 📁 Dataset

The dataset includes a collection of Netflix movies and TV shows with metadata such as:
- `title`
- `description`

If you're using your own dataset, ensure it includes a `title` and a `description` column.

---

## 🛠️ Libraries Used

- `pandas`
- `scikit-learn`
  - `TfidfVectorizer`
  - `cosine_similarity`
- `numpy` (optional)

---

## 🧪 How It Works

1. **Load dataset**
2. **Clean and preprocess data**
3. **Convert descriptions into TF-IDF vectors**
4. **Compute pairwise cosine similarities**
5. **Build a reverse index of movie titles**
6. **Return top N most similar items**

---

## 🖥️ Getting Started

### 🔧 Installation

Clone the repo and install the required libraries:
```bash
git clone https://github.com/RishitSaxena55/netflix-movies-recommender.git
cd netflix-movies-recommender
pip install -r requirements.txt
