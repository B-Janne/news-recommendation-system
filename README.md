# News Recommendation System

This project implements a **Collaborative Filtering (CF)** based recommendation system using matrix factorization techniques on the [MIND Dataset](https://www.kaggle.com/datasets/arashnic/mind-news-dataset/data). The goal is to predict which news articles a user is likely to engage with, based on their previous behavior.

## 📂 Dataset

We use the **MIND dataset** from Microsoft, which contains:

- User impression logs: impression ID, user ID, timestamp, click history, impressions.
- News content metadata: news ID, category, subcategory, title, and abstract.

## 🧠 Methods
We explore user-news interactions through:

  - User-Based Collaborative Filtering
  - Item-Based Collaborative Filtering
  - Matrix Factorization (MF)
  
## 📈 Future Work
  - Add Transformer-based session modeling
  - Incorporate news embeddings (e.g., MiniLM)
  - Hybrid models combining content + CF
