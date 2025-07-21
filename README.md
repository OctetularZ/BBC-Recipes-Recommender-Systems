# 🍽️ Recipe Recommender & Taste Prediction System
**Data Analytics** 
*Web Scraping, Recommender Systems, and Predictive Modeling*

## 📌 Project Overview
This project focuses on developing a complete data-driven pipeline — from **web scraping** to building and evaluating **machine learning models** — using real-world recipe data.

The objective is to:
- Extract recipe data from BBC Food using `BeautifulSoup`
- Explore and preprocess a dataset of 5,000+ recipes
- Build and evaluate **recommender systems** using vector space and KNN models
- Implement a **predictive classifier** to determine whether a recipe is likely to be rated as tasty

---

## 🧠 Role of Machine Learning & AI

This coursework deeply integrates concepts from **Machine Learning (ML)**, a subfield of **Artificial Intelligence (AI)**. Here's how:

### 🤖 Artificial Intelligence (AI)
AI is the broader field concerned with making systems "intelligent" — capable of mimicking human decisions. This project touches on AI by enabling systems to make:
- **Recipe recommendations**
- **Tastiness predictions**

### 📊 Machine Learning Applications in This Project

| Component | ML Concept | Description |
|----------|------------|-------------|
| Recommender Engine (Vector Space Model) | Content-based Filtering | Uses feature similarity and cosine distance to suggest similar recipes |
| Recommender Engine (KNN) | Instance-based Learning | Uses K-Nearest Neighbours algorithm to suggest recipes based on proximity in feature space |
| Taste Predictor | Supervised Learning | Classifies recipes as “tasty” or “not tasty” using labelled data and models such as Logistic Regression or Decision Trees |

Machine Learning is essential to **learn from data** and drive intelligent outcomes in this project.

---

## ⚙️ Features Implemented

### 🔍 Web Scraping
- `BeautifulSoup` used to scrape individual recipe pages from BBC Food
- Extracted fields: title, ingredients, time, dietary tags, ratings, etc.
- Data stored in a structured `.csv` format for later use

### 📈 Data Preprocessing & Analysis
- Handled missing values and inconsistent formatting
- Exploratory analysis using plots (matplotlib/seaborn)
- Computed summary statistics and rating distributions
- Performed bootstrapping to generate confidence intervals

### 🤝 Recommender System (Content-Based)
- Combined relevant recipe features into a single text field
- Applied `CountVectorizer` and `cosine_similarity` to build a vector space
- Generated recipe recommendations using matrix-vector product

### 🧠 Recommender System (KNN-Based)
- Used K-Nearest Neighbours for similarity-based recommendations
- Evaluated system performance on 4 sample users
- Measured coverage and personalization

### 🧪 Taste Prediction Classifier
- Transformed average ratings into binary targets (tasty vs. not tasty)
- Built a supervised classifier (e.g. Logistic Regression)
- Evaluated model accuracy on filtered dataset

---

## 📂 Technologies Used
- `Python`
- `BeautifulSoup`
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`

---

## 📸 Sample Visualizations

<details>
  <summary>📊 Rating Distribution</summary>

  ![rating_distribution](assets/rating_distribution.png)

</details>

<details>
  <summary>🍽️ Top Rated Recipes</summary>

  ![top_recipes](assets/top_recipes.png)

</details>

---

## 📚 Learning Outcomes

- ✅ Mastered web scraping techniques with Python and `BeautifulSoup`
- ✅ Understood the full lifecycle of ML projects: from data collection to model evaluation
- ✅ Gained experience with both content-based and KNN recommender systems
- ✅ Practiced evaluating ML models using real-world metrics (accuracy, personalization, coverage)
- ✅ Reinforced Python skills in data handling, ML, and data visualization

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/recipe-recommender.git
   cd recipe-recommender
