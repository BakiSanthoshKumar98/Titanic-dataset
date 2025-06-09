# Titanic-dataset

# 🚢 Titanic Data Visualization Project

This project explores the famous Titanic dataset using data visualization techniques such as **scatterplots**, **heatmaps**, and **pairplots** to uncover patterns related to passenger survival.

## 📁 Files Included

- `titanic_visualizations.ipynb` — Jupyter Notebook with all visualizations
- `titanic_scatter_heatmap_pairplot.png` — Exported visualization image
- `README.md` — Project description

## 📊 Visualizations

### 🔹 Scatterplot: Age vs Fare
- Shows distribution of passengers by age and ticket fare.
- Color-coded by survival status (`0 = No`, `1 = Yes`).

### 🔹 Heatmap: Feature Correlation
- Displays correlations between numerical variables such as age, fare, and survival.
- Helps identify which features may influence survival.

### 🔹 Pairplot
- Matrix of scatterplots and histograms for multiple numeric features.
- Reveals relationships and group separations by survival.

## 📦 Dataset

- **Source**: [Seaborn Titanic Dataset](https://github.com/mwaskom/seaborn-data)
- Contains passenger information: age, gender, class, fare, survival, etc.

## 📌 Requirements

```bash
pip install pandas matplotlib seaborn
