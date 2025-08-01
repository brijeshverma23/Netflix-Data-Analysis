# 🎬 Netflix Movie Data Analysis

This project analyzes a dataset of movies using Python and Jupyter Notebook. It explores various trends in movie ratings, revenue, genres, and more to extract meaningful insights about popular movies.

---

## 📁 Project Files

- `Netflix_DataAnalysis.ipynb` — Jupyter Notebook containing all the analysis and visualizations.
- `mymoviedb.csv` — Dataset with information about movies including title, genre, ratings, revenue, and more.

---

## 📊 Dataset Overview

The dataset (`mymoviedb.csv`) includes information for several movies with the following features:

- `Title` – Name of the movie
- `Year` – Release year
- `Genre` – Movie genre(s)
- `Director` – Movie director
- `Actors` – Leading actors
- `Rating` – IMDb rating
- `Votes` – Number of votes
- `Runtime (Minutes)` – Duration of the movie
- `Revenue (Millions)` – Global box office revenue
- `Metascore` – Metacritic score

---

## 🧪 Analysis Performed

The notebook performs the following steps:

### 1. **Loading the Dataset**
- Used `pandas` to load and preview the dataset.

### 2. **Data Cleaning**
- Checked for null values.
- Handled missing data.
- Converted datatypes where necessary.

### 3. **Descriptive Statistics**
- Displayed basic info like:
  - Number of movies
  - Average rating
  - Average revenue and runtime

### 4. **Genre Analysis**
- Counted and visualized the most common genres using bar plots.

### 5. **Top Movies**
- Identified top 10 movies based on IMDb rating.
- Identified top revenue-generating movies.

### 6. **Rating vs Revenue**
- Created a scatter plot showing the relationship between ratings and revenue.

### 7. **Year-wise Trends**
- Plotted how movie ratings and counts have changed over the years.

### 8. **Correlation Analysis**
- Generated a heatmap to show correlation between numerical features like Rating, Revenue, Votes, etc.

---

## 📈 Visualizations Used

- Bar charts (most common genres)
- Scatter plot (Rating vs Revenue)
- Heatmap (correlation matrix)
- Histograms (Rating distribution, Revenue distribution)
- Line plots (Trends over years)

---

## 🛠 Requirements

Make sure the following libraries are installed:

```bash
pip install pandas matplotlib seaborn
