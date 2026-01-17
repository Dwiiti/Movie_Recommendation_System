# 🎬 Movie Recommendation System (Content-Based Filtering)

## 👤 Author
**Name:** Dwiti Ranjan Parida  
**Project Type:** Final Year Project / Machine Learning Project  

---

## 📌 Project Overview
This project implements a **Movie Recommendation System** using a **Content-Based Filtering** approach.  
The system recommends movies similar to a selected movie by analyzing movie content such as **genres** and **descriptions**.

Unlike collaborative filtering, this system does **not depend on user ratings or past behavior**, making it effective even for new users (cold-start problem).

---

## 🎯 Problem Statement
Online streaming platforms host thousands of movies, making it difficult for users to decide what to watch.  
Manual searching is inefficient and time-consuming.

**Goal:**  
To recommend relevant movies automatically based on movie content without relying on user history.

---

## 💡 Solution Approach
To solve this problem, a **content-based recommendation system** is built that:
- Extracts meaningful textual features from movies
- Converts text into numerical vectors
- Measures similarity between movies
- Recommends the most similar movies

---

## 🧠 Recommendation Technique Used
**Content-Based Filtering**

- Uses movie attributes (genres, overview)
- Avoids dependency on user data
- Works well for new users
- Easy to scale and explain

---

## 📊 Dataset
- **Source:** TMDB Movie Dataset (via Kaggle)
- **Size:** ~10,000 movies
- **Important Columns Used:**
  - Movie ID
  - Title
  - Overview
  - Genres

---

## 🔧 Data Preprocessing
1. Selected only relevant columns
2. Combined `Overview` and `Genres` into a new column called **Tags**
3. Removed unnecessary metadata such as popularity and vote count
4. Cleaned and prepared text data for vectorization

---

## 🔢 Text Vectorization
- Used **CountVectorizer** from `scikit-learn`
- Removed English stop words
- Limited features to 10,000
- Converted textual movie data into numerical vectors

---

## 📐 Similarity Measurement
- Applied **Cosine Similarity**
- Measures similarity between movie vectors
- Smaller angle between vectors → higher similarity

---

## 🔁 Recommendation Logic
1. User selects a movie
2. Movie index is identified
3. Similarity scores are retrieved
4. Scores are sorted in descending order
5. Top 5 most similar movies are recommended

---

## 🌐 Web Application
A web interface was developed using **Streamlit**:
- Dropdown to select a movie
- Button to generate recommendations
- Displays top 5 similar movies instantly

---

## 🛠️ Technologies Used
- **Language:** Python
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn
  - streamlit
- **Tools:**
  - Jupyter Notebook (model development)
  - VS Code
  - Ubuntu Linux

---

## ▶️ How to Run the Project

### 1️⃣ Clone or Copy Project Files
Ensure the following files exist:
