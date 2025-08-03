## 🎬 Movie Metadata Analysis
This project dives into a large dataset of movie metadata to explore patterns and trends across genres, budgets, revenues, IMDb scores, and more.  
Using Python and data analytics techniques, it demonstrates how movie industry data can be transformed into meaningful insights through visual storytelling.

## 📊 Overview
Using Python's data processing and visualization libraries, this project covers:
- Correlation between *budget* and *gross revenue*
- Genre and language distribution
- Analysis of *IMDb scores* across different variables
- Handling missing data and outliers
- Data preparation for potential *recommender systems*
  
## 📁 Dataset
- *Source*: IMDb-based public dataset  
- *Format*: CSV files  
- *Files Used*:
  - movie_metadata.csv — raw data
  - new_movie_metadata.csv — cleaned/preprocessed data

- *Key Columns*:
  - movie_title  
  - director_name  
  - actor_1_name, actor_2_name  
  - genres, language, country  
  - budget, gross, imdb_score  
  - duration, title_year

## 📌 Key Insights
✅ Strong positive correlation between *budget and gross revenue*  
✅ English movies dominate the dataset  
✅ Popular genres include *Drama, **Action, and **Comedy*  
✅ Some directors show consistent performance based on IMDb scores  
✅ Several missing values were found and treated in key numeric columns

## 🔧 Technologies Used
- *Python 3*
- *Pandas* for data manipulation  
- *Seaborn* & *Matplotlib* for visualization  
- *Scikit-learn* for preprocessing  
- *Jupyter Notebook* for workflow
  
## 📷 Sample Visuals
- 📈 Heatmap of numeric correlations  
- 📊 Bar chart of top genres by count  
- 🧮 Budget vs Revenue scatter plot  
- 📉 Boxplots for outlier detection
  
## 🧠 Skills Applied
- Data cleaning and null handling  
- Outlier removal using statistical techniques  
- Exploratory Data Analysis (EDA)  
- Grouping, filtering, and visual comparison  
- Preparing structured data for future ML tasks

## 🚀 How to Run
1. Clone the repo:
```bash
git clone https://github.com/Krrishu321/Movie-Metadata-Analysis.git
2. Open the notebook:
cd Movie-Metadata-Analysis
jupyter notebook movie_metadata_analysis.ipynb

📂 Project Structure
Movie-Metadata-Analysis/
├── movie_metadata.csv
├── new_movie_metadata.csv
├── movie_metadata_analysis.ipynb
├── README.md

💬 Conclusion
This project highlights how industry datasets can be cleaned, visualized, and interpreted using Python.
It serves as a solid example of how data analytics can uncover insights in entertainment and business strategy.
---

👤 Author: Krishna Singh
