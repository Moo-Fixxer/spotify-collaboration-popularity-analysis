# spotify-collaboration-popularity-analysis

🎧 Spotify Collaboration & Popularity Analysis

Analyzed 20K+ Spotify tracks to evaluate how artist collaborations influence popularity and musical features

Engineered features like is_collaboration and is_highly_popular; performed extensive EDA and hypothesis testing

Built and evaluated Decision Tree and Random Forest models to predict popularity (Random Forest R² = 0.50)

Found statistically significant differences in danceability and acousticness between solo and collaborative tracks

## 📌 Problem Statement
Explore how artist collaborations affect the popularity and musical attributes of songs using the Spotify dataset.

## 🧠 Approach
- Preprocessed Spotify dataset (cleaning, feature engineering)
- Created collaboration and popularity indicators
- Ran EDA (histograms, boxplots, correlation matrix)
- Ran t-tests on solo vs. collab tracks
- Built regression models:
  - Decision Tree (R² = 0.1, MSE = 446.66)
  - Random Forest (R² = 0.5, MSE = 246.51)

## ✅ Findings
- Collaborations increase danceability and reduce instrumentalness
- Popularity is influenced by energy and danceability, but not only by them
- Random Forest gave much better predictions than Decision Tree

## 🛠 Tools
Python · pandas · matplotlib · seaborn · scikit-learn · Jupyter

