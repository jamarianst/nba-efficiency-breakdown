# nba-efficiency-breakdown
Analyze 2023–24 NBA advanced player stats using PCA and regression to uncover what drives player efficiency. Includes EDA, modeling, and insights on statistical archetypes.

# 🏀 NBA Player Efficiency Breakdown (2023–24)

## 📌 Overview
This project analyzes 2023–24 NBA advanced player stats to uncover what drives player efficiency and identify statistical archetypes using PCA and regression modeling.

## 📊 Data Source
- [Basketball Reference: 2023–24 NBA Advanced Stats](https://www.basketball-reference.com/leagues/NBA_2024_advanced.html)
- Data scraped using `pandas.read_html()` in Python

## 🔍 Key Features
- EDA: Correlation matrix, scatter plots, top players
- PCA: Visualized 2D clustering of player archetypes
- Regression: Predicted PER using TS%, USG%, BPM, and VORP
- Model explained 80% of PER variance (R² = 0.80)

## 💡 Insights
- TS% is the strongest driver of PER
- BPM and USG% contribute positively
- Some high-efficiency players fly under the radar
- PCA separates players by style and statistical impact

## 🛠 Tech Stack
- Python, Pandas, Scikit-learn, Seaborn, Matplotlib
- Jupyter Notebook

## 📁 Files
- `nba_efficiency_breakdown.ipynb` — main notebook
- `README.md` — this file

---

## 📌 Author
Built by Jah — aspiring data scientist and FAANG intern hopeful.

