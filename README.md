
# 🎬 Global YouTube Statistics — Data Science Analysis

> **Portfolio Project** | Python · Pandas · Plotly · Seaborn | Dataset: Top 995 YouTube Channels (2023)

---

## 📌 Overview

This project explores what separates the world's top YouTube channels from the rest. Using the [Global YouTube Statistics 2023](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023) dataset, I perform a full data science pipeline: cleaning, EDA, multi-angle analysis, and publication-ready visualizations.

**Key questions answered:**
- Which categories dominate in views *vs.* earnings? (spoiler: they're not the same)
- Which countries produce the most top creators?
- Do more subscribers always mean more money?
- When did the YouTube creator boom actually happen?

---

## 🔍 Key Findings

| Question | Finding |
|---|---|
| 🎵 **Best category for views?** | **Music** — 3.1 trillion total views, 2× more than Entertainment |
| 💰 **Best category for earnings?** | **Shows** & **Autos** — higher CPM despite fewer channels |
| 🌍 **Where are creators?** | **USA (31%)** and **India (17%)** dominate the top 1000 |
| 📈 **Subscribers vs. earnings?** | **Views matter more than subs** for revenue (r = 0.55 vs 0.39) |
| 🕐 **When to have started?** | Peak channel creation was **2012–2016** — the platform matures fast |

---

## 📊 Visualizations

### 1. Views vs. Earnings by Category
![Category Views vs Earnings](visuals/category_views_vs_earnings.png)
> Music dominates total views but "Shows" channels earn the most per channel on average — a higher CPM niche.

---

### 2. Correlation Heatmap — Key Metrics
![Correlation Heatmap](visuals/correlation_heatmap.png)
> Total views (r=0.55) is a stronger predictor of earnings than subscriber count (r=0.39).

---

### 3. Channel Creation Over Time
![Channel Creation Timeline](visuals/channel_creation_timeline.png)
> The creator boom peaked around 2012–2016. Most of today's top channels are 8–12 years old.

---

### 4. Subscriber Distribution by Category (Violin Plot)
![Violin Plot](visuals/violin_subscribers_by_category.png)
> Music and Entertainment show wide distributions — a few mega-channels skew the averages significantly.

---

### 5. Interactive Maps & Scatter (HTML)
Two interactive Plotly charts are available in `/visuals/`:
- `map_channels_by_country.html` — Choropleth world map of top channels per country
- `scatter_subscribers_earnings.html` — Subscribers vs. earnings, colored by category, sized by views

---

## 🗂️ Project Structure

```
global-youtube-analysis/
│
├── README.md
├── requirements.txt
├── notebooks/
│   └── analysis.ipynb        ← Full analysis notebook
├── data/
│   └── Global_YouTube_Statistics.csv
└── visuals/
    ├── category_views_vs_earnings.png
    ├── correlation_heatmap.png
    ├── channel_creation_timeline.png
    ├── violin_subscribers_by_category.png
    ├── map_channels_by_country.html
    └── scatter_subscribers_earnings.html
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/YOUR_USERNAME/global-youtube-analysis
cd global-youtube-analysis
pip install -r requirements.txt
jupyter notebook notebooks/analysis.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3.10**
- **Pandas** — data cleaning & manipulation
- **Matplotlib / Seaborn** — static visualizations
- **Plotly Express** — interactive charts & choropleth map
- **NumPy** — numerical computations

---

## 📁 Dataset

- **Source**: [Kaggle — Global YouTube Statistics 2023](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023)
- **Size**: 995 channels × 28 features
- **Features include**: subscribers, video views, earnings estimates, country, category, upload count, creation date, and macroeconomic country indicators

---

## 👤 Author

Made by **[Your Name]** as part of a Data Science portfolio.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/YOUR_PROFILE)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black)](https://github.com/YOUR_USERNAME)

# global-youtube-statistics-analysis
Data analysis project exploring the world's top YouTube channels using Python, Pandas, Plotly, and Seaborn.

