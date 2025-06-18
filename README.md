# Recommender Systems Techniques

This repository contains various techniques and implementations used in building **Recommender Systems**, including:

- Content-Based Filtering
- Collaborative Filtering
- Hybrid Techniques
- Movie Recommendation Systems

Each notebook is self-contained and demonstrates a unique approach to building a recommender system using Python and popular data science libraries.

---

## 📁 Project Structure

```
├── content-based-recommendation-system.ipynb
├── movie-recommender-system-using-python.ipynb
├── nearest-neighbor-item-based-collaborative-filterin.ipynb
├── weighted-hybrid-technique-for-recommender-system.ipynb
```

---

## 📘 Techniques Implemented

### 1. Content-Based Filtering
- Recommends items based on item similarity.
- Uses features like genres, tags, and description.
- Utilizes cosine similarity on TF-IDF vectors or count vectors.

### 2. Collaborative Filtering (Nearest Neighbor Item-Based)
- Finds similar items based on user ratings.
- Builds a user-item matrix and uses cosine similarity to recommend items rated highly by similar users.

### 3. Hybrid Recommendation System
- Combines content-based and collaborative filtering scores.
- Assigns weights to each method and returns the final recommendation score.
- Visualizes movie popularity and ratings using bar plots and scatter plots.

### 4. Movie Recommender System Using Python
- Performs data cleaning, EDA, and movie recommendation based on vote averages and counts.
- Uses IMDb weighted rating formula for ranking.
- Visualizes the distributions of votes and ratings.

---

## 📊 Sample Outputs

- Bar charts showing most rated movies.
- Histograms of rating distributions.
- Heatmaps of cosine similarities between items.
- Scatter plots showing relationships between vote average and vote count.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔍 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ekaanshkhosla/Recommender_systems.git
   cd Recommender_systems
   ```

2. Open any notebook using Jupyter or VS Code.

3. Run the cells to explore and understand the logic behind each recommender technique.

---

## 📌 Author

[Ekaansh Khosla](https://github.com/ekaanshkhosla)

---

## ⭐️ Show your support

If you found this project helpful, consider giving it a ⭐️!
