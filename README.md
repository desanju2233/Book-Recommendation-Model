# 📚 Book Recommender System

A Book Recommender System built using Python and Jupyter Notebook. This project implements two recommendation techniques:

- 📈 Popularity-Based Filtering
- 🔁 Collaborative Filtering (Item-Based using Cosine Similarity)

---

## 🚀 Features

- Recommends popular books based on the number of ratings and average score.
- Suggests similar books using item-based collaborative filtering.
- Cleaned and preprocessed real-world book dataset.
- Efficient cosine similarity computation with sparse matrices.
- Easy-to-use function to generate recommendations for any book title.

---

## 🧠 Algorithms Used

### 1. Popularity-Based Recommender
- Filters books with high number of ratings and average ratings.
- Ranks books based on their popularity score (votes * average rating).

### 2. Collaborative Filtering (Item-Based)
- Uses a pivot table of users vs. books.
- Applies cosine similarity between book vectors.
- Recommends books that are similar to the ones a user likes.

---

## 📂 Dataset

Merged from three CSV files:
- `Books.csv` - Metadata about books (title, author, ISBN, etc.)
- `Users.csv` - User demographic info
- `Ratings.csv` - Book ratings by users

Dataset Source: [Book-Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/)

---

## 📊 Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (optional for visuals)
- Jupyter Notebook

---
