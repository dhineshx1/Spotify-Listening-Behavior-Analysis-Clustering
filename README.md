# 🎵 Spotify Listening Behavior Analysis & Clustering

## 📌 Project Overview

This project is part of my **10 Projects in 30 Days ML Sprint**. It focuses on analyzing Spotify track playback behavior using clustering techniques to uncover listening patterns and engagement trends.

## 🚀 Key Objectives

- Analyze **Spotify playback data** to understand track interactions.
- Apply **K-Means Clustering** to group tracks based on playback behavior.
- Evaluate cluster quality using **DB Index & Silhouette Score**.
- Derive insights for **personalized music recommendations**.

## 📊 Dataset


2. Kaggle Dataset Link :
   ```bash
   https://www.kaggle.com/datasets/sgoutami/spotify-streaming-history
    ```


The dataset contains track-related playback data, including:

- `platform` (Android, Web Player, etc.)
- `ms_played` (Duration played in milliseconds)
- `reason_start` & `reason_end` (How the track started and ended)
- `skipped`, `shuffle` (Playback behavior indicators)

## 🔥 Methodology

1. **Data Preprocessing**: Handling missing values, encoding categorical features.
2. **Feature Engineering**: One-hot encoding categorical variables, scaling 
numerical data.
3. - **PCA** Improve clustering with **dimensionality reduction**.
4. **Clustering**: Applying **K-Means**, determining the optimal **K** using the **Elbow Method**.
5. **Cluster Evaluation**: Using **Silhouette Score** & **Davies-Bouldin Index**.
6. **Insights & Visualization**: Understanding playback trends from clusters.

## 📈 Results & Insights

- Identified **distinct track interaction behaviors**.
- Found **clusters with high skip rates vs. long engagement**.
- Determined **key factors influencing playback duration**.

## 📌 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/dhineshx1/Spotify-Listening-Behavior-Analysis-Clustering
   ```
2. Run the notebook:
   ```bash
   jupyter notebook spotify_analysis.ipynb
   ```

## 🔥 Future Work

- Explore **user-based clustering** for better personalization.
- Build a **recommendation system** using cluster insights.

📢 **Let’s Connect!** If you found this useful, drop a ⭐ on the repo! 🚀
