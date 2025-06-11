# 🎬 K-Drama Recommendation System

A personalized **K-Drama Recommendation System** built using **Python**, **Streamlit**, and **TMDb API**, designed to help users discover similar Korean dramas based on their preferences.

> ⚠️ This is **not a website**. The application runs locally using **Streamlit** or can be executed via **Google Colab**.

---

## 📌 Project Overview

This project is a content-based recommendation system that suggests K-Dramas similar to the one selected by the user. It uses Natural Language Processing (NLP) techniques such as **TF-IDF** and **cosine similarity** on metadata like overview and genre.

---

## 💻 Technologies Used

| Tool / Library       | Purpose                               |
|----------------------|----------------------------------------|
| Python               | Core programming language              |
| Streamlit            | User interface framework               |
| TMDb API             | Source for K-Drama metadata            |
| Pandas               | Data manipulation                     |
| Scikit-learn         | TF-IDF vectorization & similarity calc |
| Requests, JSON       | API interaction                        |

---

## 🎯 Features

- Input any K-Drama title from the TMDb dataset
- Get top 5 similar K-Drama recommendations
- Display poster, overview, and rating for each suggestion
- Clean and interactive interface using Streamlit (locally)

---

## 🛠️ How to Run the App

### 🧑‍💻 On Your Local Machine

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/kdrama-recommender.git
   cd kdrama-recommender
