# 🎵 Spotify Smart Playlist Optimizer

> **End-to-End Data Engineering Pipeline and Content-Based Recommendation Engine.**

📌 [🔗 Click here to view the Project Presentation Slide Deck]([COLOQUE_SEU_LINK_AQUI](https://github.com/israelfilipe1987-ctrl/spotify-smart-playlist-optimizer/blob/main/presentation/spotify_smart_playlist_optimizer_sql_engine.pdf))

---

## 📌 1. Project Overview & Business Problem
Treating millions of distinct musical tracks as a flat, unindexed library leads to high search friction and session drop-offs. This project implements a production-grade relational pipeline to clean and index global tracks, utilizing a mathematical vector space engine to instantly generate context-aware smart playlists.

### Core Framework:
* Data Engineering Layer (SQL): Ingestion and relational feature engineering simulation inside an in-memory SQLite database.
* Business Intelligence: Dynamic multi-axis acoustic mapping using Plotly dark-theme dashboards.
* Mathematical Engine: Real-time Euclidean distance calculations to extract top-5 nearest matches within isolated rhythm cohorts.

---

## 2. Pipeline Architecture & Features

* Robust Data Ingestion: Automated encoding-safe pipeline handling international typography (utf-8-sig, latin-1, iso-8859-1).
* SQL Feature Engineering: Direct calculation of cross-platform Engagement_Rate and automated partitioning of tracks into structured Rhythm_Category bins (Slow/Chill, Medium/Dance, Fast/Upbeat) using database logic.
* Interactive Visualization: Dynamic scatter matrix mapping Danceability vs. Energy, scaled by total Stream counts.
* Vector Proximity Engine: Localized geometric proximity lookups using the Euclidean Distance formula.

---

## 3. Quick Start & Execution

### Prerequisites:
pip install pandas numpy plotly sqlite3

### Execution Steps:
* Clone this repository and place the raw spotify_dataset.csv file into the local directory.
* Run the pipeline segments sequentially inside the Jupyter Notebook.
* Call the recommendation engine with your target choice using the recommend_smart_playlist function.

---

## 4. Future Roadmap & Risks
* Vector Scaling Mitigation: Transition from sequential array lookups to an Approximate Nearest Neighbors (ANN) framework (FAISS / Annoy) to support millions of rows.
* Phase 2 Expansion: Build a Cross-Platform Competitive Audit module using advanced SQL window functions to evaluate streaming arbitrage between YouTube and Spotify metrics.
* Phase 3 Expansion: Implement predictive Machine Learning models to forecast hit probability based on pre-release acoustic metrics.
