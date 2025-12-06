# 📊 Netflix Data Analysis & Visualization using Python

A complete exploratory data analysis (EDA) of the **Netflix Titles Dataset**, showcasing skills in **Pandas**, **NumPy**, and **Matplotlib**. This project includes data cleaning, transformation, insight generation, and visualizations.

---

## 📁 Project Structure

```
Netflix_Data_Analysis/
│
├── data/                          # Dataset folder
│     └── netflix_titles.csv
│
├── notebooks/                     # Jupyter notebooks
│     ├── netflix_data_analysis.ipynb
│     └── practice_matplotlib.ipynb
│
├── plots/                         # All generated charts
│     ├── movie_duration_histogram.png
│     ├── top_10_countries.png
│     ├── type_of_rating_pie.png
│     ├── release_year_scatter.png
│     ├── movies_vs_tv_shows.png
│     ├── movies_and_tv_shows_comparison.png
│     ├── matplotlib_charts.png
│     └── ...
│
└── README.md
```

---

## 📌 Project Overview

This project performs an in‑depth analysis of Netflix titles to uncover:

* Content distribution between **Movies** and **TV Shows**
* Trends in content release over time
* Most contributing countries
* Rating patterns
* Movie duration characteristics

It also demonstrates strong understanding of **EDA workflow**, **Matplotlib plotting**, and dataset handling.

---

## 🧹 Data Cleaning Steps

The dataset was cleaned using the following steps:

* Handling missing values
* Cleaning `duration` column (`"90 min" → 90`)
* Splitting multi-country entries
* Converting `release_year` to numeric
* Filtering Movies and TV Shows separately
* Standardizing rating categories

---

## 📈 Visualizations Included

### 1️⃣ Movie Duration Distribution

Histogram showing distribution of movie lengths.

### 2️⃣ Movies vs TV Shows Count

Bar chart showing total content by type.

### 3️⃣ Release Year Trend

Line plot & scatter plot showing growth of content over years.

### 4️⃣ Top 10 Content-Producing Countries

Horizontal bar chart.

### 5️⃣ Rating Distribution

Pie chart of rating categories.

### 6️⃣ Comparison of Matplotlib Plot Types

A 2×2 grid demonstrating line, bar, scatter, and pie charts.

---

## 🛠️ Technologies Used

| Library              | Purpose                        |
| -------------------- | ------------------------------ |
| **Pandas**           | Data cleaning and manipulation |
| **NumPy**            | Numerical computations         |
| **Matplotlib**       | Visualizations                 |
| **Jupyter Notebook** | Interactive analysis           |

---

## 🔍 Key Insights

* Netflix has **more Movies than TV Shows**.
* Movie duration typically falls between **80–120 minutes**.
* **USA and India** produce the most Netflix content.
* Ratings **TV-MA** and **TV-14** dominate the catalog.
* Netflix content production surged post‑2010.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Rakshit152/Netflix_Data_Analysis.git
cd Netflix_Data_Analysis
```

### 2️⃣ Install requirements

```bash
pip install pandas numpy matplotlib
```

### 3️⃣ Launch the notebook

```bash
jupyter notebook
```

---

## 📬 Contact

**Created by Rakshit Choubisa**

Add your profiles here:

* 🔗 GitHub: [https://github.com/Rakshit152](https://github.com/Rakshit152)
* 🔗 LinkedIn: [https://linkedin.com/in/rakshit-choubisa](https://linkedin.com/in/rakshit-choubisa)

##

---

If you want a more **stylish README with badges, banners, colors, or images inserted**, just say *"make it stylish"*! 🚀
