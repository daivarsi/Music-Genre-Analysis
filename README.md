# 🎧 Music Genre Analysis and Danceability Prediction
A data science project exploring the relationships between musical features (tempo, energy, acousticness, etc.) and genres, with a focus on predicting a song's danceability using regression analysis.

---

## 📁 Files Included

- `Data_Science_Project_ENGR_241.ipynb`: Main Jupyter Notebook (Google Colab)
- `data_science_project_engr_241.py`: Python script with key functions and analysis
- `Data Science Project.pdf`: Final report / slide deck (summary of results)

---

## 📊 Project Overview

**Objective**: Use machine learning and statistical modeling to explore:
- How musical features vary across genres
- What factors most influence how danceable a song is

**Dataset**: [Prediction of Music Genre – Kaggle](https://www.kaggle.com/datasets/vicsuperman/prediction-of-music-genre)

The dataset includes:
- Tempo
- Key & Mode
- Energy
- Danceability
- Acousticness
- Speechiness
- Instrumentalness
- Loudness
- Valence
- Genre (target)

---

## 🔍 Methodology

### ✅ Data Cleaning
- Handled missing values using median imputation (by genre)
- Removed or imputed outliers (using z-scores and IQR)

### 📊 EDA (Exploratory Data Analysis)
- Histograms of distributions
- Boxplots and bar graphs by genre
- Correlation heatmap
- Pivot tables and key-mode heatmap

### 📈 Regression Modeling
- Multiple linear regression using:
  - Energy
  - Valence
  - Loudness
- Used both `statsmodels` and `sklearn` for modeling
- Evaluated model performance with R², F-statistic, p-values

---

## 🔢 Sample Results

- **Danceability** is positively associated with **energy** and **valence**
- **R² ≈ 0.21 – 0.29**: modest predictive power
- Best predictors: `valence`, `energy`

---

## 📈 Visualizations

- Energy, Tempo, and Acousticness by genre
- Regression line plots for:
  - Energy vs Danceability
  - Valence vs Danceability
- Heatmap of correlation matrix

---

## 🧠 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy, Statsmodels, Scikit-learn
- Google Colab

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
