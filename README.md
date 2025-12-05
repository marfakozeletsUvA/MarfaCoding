# Semester 3 Coding Portfolio 🎓

A collection of data science projects covering APIs, NLP, regression, network analysis, and agent-based modeling.

---

## Projects

### 1. APIs & Scraping — *Mars Weather Postcards*
Used NASA's InSight Mars Weather API and Image Library to create "postcards from Mars" — combining real weather data (temperature highs/lows per Sol) with actual images from the InSight lander. Inspired by the show *For All Mankind*.

**Tech:** `requests`, `pandas`, `matplotlib`, `PIL`

---

### 2. NLP — *Bible Verse Topic Modeling*
Explored themes in Bible verses using BERTopic, then trained a Random Forest classifier to predict verse genre (Law, History, Poetry, Prophecy, Gospel, Epistle). Achieved ~90% accuracy. Key discriminating words: "saith", "jehovah", "jesus", "begat".

**Tech:** `BERTopic`, `sklearn (RandomForest, TF-IDF)`, `pandas`

---

### 3. Linear Regression — *Spotify Danceability Prediction*
Predicted song danceability using Spotify audio features. Linear regression performed poorly (R² = 8.4%), but Random Forest captured non-linear patterns much better (R² = 65%). Valence (happiness) was the strongest predictor. Bootstrap CI: [0.101, 0.104].

**Tech:** `sklearn`, `statsmodels`, `pandas`, `matplotlib`

---

### 4. Logistic Regression — *PCOS Diagnosis Prediction*
Built logistic regression models (homogeneous & heterogeneous) to predict PCOS diagnosis from demographic/lifestyle features. Model performed no better than random guessing (AUC ≈ 0.50) — discovered the dataset was synthetically generated with no real predictive signal. A lesson in data quality!

**Tech:** `sklearn`, `statsmodels`, `seaborn`

---

### 5. Social Network Analysis — *Epstein Email Network*
Analyzed the structure of Jeffrey Epstein's email network using centrality metrics and community detection. Found a classic hub-and-spoke structure with Epstein at the center (degree centrality = 0.89). Validated results against Gephi visualization.

**Tech:** `networkx`, `pandas`, `matplotlib`

---

### 6. Agent-Based Modeling — *Influence Spread Simulation*
Built an ABM simulating how influence spreads through the Epstein network. Agents transition through states (Normal → Influenced → Offender). Found a tipping point at p ≈ 0.2-0.3 where spread shifts from partial to near-complete. ~30 nodes remained "immune" due to network disconnection.

**Tech:** `networkx`, `matplotlib`

---

*Semester 3, 2024-2025*
