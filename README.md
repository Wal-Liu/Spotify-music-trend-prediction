# Global Music Trend Analysis & Prediction (Spotify Data 2025)

## 📌 Project Overview
This project analyzes and predicts **global music trends** using Spotify’s top songs dataset. By applying data analysis and machine learning techniques, we aim to understand **listener behavior, hit-making factors, and trend evolution** across more than 70 countries.

Dataset source: [Top Spotify Songs (Daily Updated, 73 Countries) – Kaggle](https://www.kaggle.com/datasets/asaniczka/top-spotify-songs-in-73-countries-daily-updated)

---

## 🎶 Dataset
- **Size:** ~554,812 records (H1 2025)  
- **Key Features:**
  - **Song Metadata:** `spotify_id`, `name`, `artists`, `album_name`, `album_release_date`
  - **Ranking & Popularity:** `daily_rank`, `daily_movement`, `weekly_movement`, `popularity`, `country`, `snapshot_date`
  - **Audio Features (Spotify API):** `danceability`, `energy`, `valence`, `acousticness`, `instrumentalness`, `tempo`, `loudness`, `speechiness`, `duration_ms`, `is_explicit`, etc.

---
## Download 2025 Songs Data
To download 2025 songs data, run the `download_data.ipynb` notebook.


## 🎯 Project Objectives
1. **Cluster Global Music Trends**  
   - Discover global “music trend groups” via **K-Means & LDA**.  
   - Identify differences across countries and cultural preferences.

2. **Analyze Features vs Popularity**  
   - Use **Linear Regression, XGBoost** to model popularity.  
   - Find out what audio features make a song successful.

3. **Hit Prediction (Top 10 / Top 50 Classification)**  
   - Build classifiers (**SVM, Random Forest**) to predict hit potential.  
   - Understand factors distinguishing global hits from others.

4. **Trend Forecasting (Rank Movement)**  
   - Predict song movements (**up/down/stable**) using **Logistic Regression, MLP**.  
   - Explore lifecycle patterns of hit songs over time.

---

## 📊 Evaluation Metrics
- **Regression:** RMSE, MAE, R²  
- **Classification:** Accuracy, Precision, Recall, F1-score, ROC-AUC  
- **Clustering:** Silhouette Score, Visualizations  

---

## 🛠️ Methods & Tools
- **Clustering:** K-Means, LDA, PCA  
- **Regression:** Linear Regression, Decision Trees, XGBoost  
- **Classification:** SVM, Random Forest  
- **Trend Prediction:** Logistic Regression, MLP  
- **Visualization:** Matplotlib, Seaborn, Plotly  

---

## 👥 Team Members (Group 16)
| Member       | Task | Main Methods |
|--------------|------|--------------|
| **Nguyễn Quốc Huy** | Clustering music trends | K-Means, LDA, PCA |
| **Lưu Vĩnh Tường** | Regression: Popularity prediction | Linear Regression, XGBoost |
| **Nguyễn Nam Hy** | Classification: Hit prediction | SVM, Random Forest |
| **Nguyễn Minh Quang** | Rank movement forecasting | Logistic Regression, MLP |

---

## 🚀 Expected Outcomes
- Clusters of global music trends & cultural comparisons.  
- Insights on audio features that drive popularity.  
- A classification system for hit detection (Top 10/Top 50).  
- Models predicting lifecycle & rank evolution of songs.  


