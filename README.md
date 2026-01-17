
# 🎬 Content Recommendation System (Movie Recommendation)

## 👤 Student Details
**Name:** Dwiti Ranjan Parida  
**Project Type:** Final AI / Machine Learning Project  

---

## 📌 Project Overview
This project implements a **Content Recommendation System** that suggests movies to users based on their past preferences and rating behavior.  
The system uses **Collaborative Filtering** and **Machine Learning techniques** to predict user ratings for unseen movies and recommend the most relevant content.

Recommendation systems are widely used by platforms such as Netflix, Amazon, and YouTube to personalize user experience and improve engagement.

---

## 🎯 Objectives
- Build a movie recommendation system using collaborative filtering  
- Predict ratings for movies that a user has not watched  
- Recommend top-N movies personalized to each user  
- Minimize prediction error using evaluation metrics like RMSE and MAPE  

---

## 🧠 Approach
The project follows these main steps:

1. **Data Loading & Exploration**
   - User ratings and movie metadata are loaded and analyzed
   - Sparsity and rating distribution are examined

2. **Data Preprocessing**
   - Cleaning and formatting data
   - Creating user–item interaction matrices

3. **Similarity Computation**
   - User–User similarity
   - Movie–Movie similarity

4. **Model Implementation**
   - Baseline models (User Average, Movie Average)
   - KNN-based Collaborative Filtering
   - Matrix Factorization (SVD, SVD++)
   - Hybrid Machine Learning models using XGBoost

5. **Evaluation**
   - Performance evaluated using RMSE and MAPE
   - Comparison of different models

6. **Recommendation Generation**
   - Top movie recommendations generated for each user

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Surprise  
  - XGBoost  
  - Matplotlib  
- **Environment:** Jupyter Notebook  

---

## 📊 Evaluation Metrics
- **RMSE (Root Mean Square Error)**
- **MAPE (Mean Absolute Percentage Error)**

### Results (Approximate)
- Train RMSE: ~0.80  
- Test RMSE: ~1.00  
- Test MAPE: ~36%  

These results indicate good generalization and minimal overfitting.

---

## ⚠ Limitations
- Cold start problem for new users and new movies  
- Depends only on historical ratings  
- Does not consider movie content such as actors, plot, or genre in detail  

---

## 🚀 Future Improvements
- Add content-based filtering  
- Use deep learning models for recommendations  
- Include user demographic data  
- Deploy the system as a web or mobile application  
- Support real-time recommendations  

---

## 📚 Dataset
- **Source:** MovieLens Dataset (GroupLens)
- Link: https://grouplens.org/datasets/movielens/

---

## 🤖 AI Usage Disclosure
AI tools were used for:
- Documentation refinement  
- Code explanation  
- Presentation preparation  

All implementation logic and analysis were reviewed and validated by the author.

---

## ✅ Conclusion
This project demonstrates how **AI-powered recommendation systems** can effectively personalize user experience.  
The system is scalable, practical, and applicable to real-world platforms such as streaming services and e-commerce websites.
