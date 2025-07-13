# 🕹️ PUBG Game Prediction

A machine learning project that predicts a player's **final winning percentage (`winPlacePerc`)** in PUBG using in-game statistics and a **CatBoost regression model**.  
This project involves comprehensive data preprocessing, feature engineering, visualization, and model training to understand and predict player performance.

---

## 📌 Project Highlights

- ✅ Built a regression model using **CatBoost Regressor** for accurate prediction of player ranking.
- 🧹 Cleaned and preprocessed real match data: removed outliers, handled nulls, and dropped irrelevant columns.
- ⚙️ Engineered gameplay-specific features like:
  - `headshotRatio`
  - `killsPerDistance`
  - `totalDistance`
  - `killStreakImpact`
- 📈 Visualized trends and correlations using **Seaborn** and **Matplotlib**.
- 📊 Achieved **R² score of 0.89+** and strong feature importance insights.
- 🚀 Optimized model using hyperparameter tuning for better generalization.

---

## 📂 Dataset

The dataset is sourced from [Kaggle - PUBG Finish Placement Prediction](https://www.kaggle.com/c/pubg-finish-placement-prediction).  
Due to size constraints, it is not included in this repo. Please download it manually and place it in the working directory.

---

## 🧰 Tech Stack

- **Languages**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `catboost`, `sklearn`
- **Tools**: Jupyter Notebook, Git, GitHub

---
