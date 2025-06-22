# 🎬 Movie Recommender System

A content-based movie recommendation engine that suggests similar movies based on genre, cast, keywords, and overview. Built using Python, NLP, and cosine similarity.

## 🚀 Features
- Combines metadata into a unified 'tags' feature
- Uses CountVectorizer and cosine similarity for recommendations
- Recommends top 5 similar movies for any given input

## 🧰 Tech Stack
- Python
- Pandas, NumPy
- scikit-learn
- NLTK (for text preprocessing)

## 🧠 Recommendation Logic
- Preprocess text using stemming and stopword removal
- Vectorize using CountVectorizer
- Compute similarity matrix and return top results

## ✅ Example
Input: `Inception`  
Output: `[Interstellar, The Prestige, The Matrix, Memento, Shutter Island]`

---

