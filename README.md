# NetFlix
Comprehensive analysis of Netflix’s global content library using Python, uncovering trends in movies vs TV shows, genre popularity, regional production, and content growth over time.

This project performs an end-to-end exploratory data analysis on Netflix titles data using Python. The analysis focuses on understanding content distribution, genre trends, country-wise production, and the evolution of movies and TV shows on the platform over time, providing insights into Netflix’s content strategy.

The Link to the dataset: https://www.kaggle.com/datasets/shivamb/netflix-shows
--
## 🎯 Objectives
- Explore Netflix’s global content library
- Analyse trends in movies vs TV shows
- Understand genre popularity and diversification
- Study country-wise content production
- Identify growth patterns over time
- Understanding the creator countries for Movies/ Series.

## 🗂 Dataset Description
- Total records: **8,000+ titles**
- Content types: **Movies & TV Shows**
- Key attributes:
  - Title, type (Movie / TV Show)
  - Release year
  - Date added to Netflix
  - Country of production
  - Genre (listed_in)
  - Duration
  - Rating
  - Director, Cast
  - Listed In
  - Description

📌 Dataset combines multiple dimensions, enabling **content, time-series, and regional analysis**.

---

## 🛠 Tools & Technologies
- **Python**
  - Pandas
  - NumPy
- **Visualization**
  - Matplotlib
  - Seaborn
- **Jupyter Notebook**

---

## 🔍 Data Understanding & Exploration
- Dataset shape and structure analysis
- Data type inspection
- Missing value assessment
- Unique values exploration for categorical columns

---

## 🔧 Data Cleaning & Preparation
Key cleaning steps performed:

- Handled missing values in:
  - Country
  - Rating
  - Duration
- Standardised column formats
- Parsed date fields for time-based analysis
- Split multi-value genre and country fields
- Removed unnecessary or redundant columns

---
## 📊 Exploratory Data Analysis

### 🔹 Content Type Analysis
- Movies vs TV Shows distribution
- Growth trend comparison over time

### 🔹 Genre Analysis
- Most common genres on Netflix
- Genre diversity across years
- Genre dominance by content type

### 🔹 Country-wise Analysis
- Top content-producing countries
- Regional contribution to Netflix library
- Country-level growth patterns
  
### 🔹 Time-based Trends
- Titles added per year
- Content expansion phases
- Shift in platform strategy over time

---

## 📈 Key Insights
- Netflix has increasingly focused on **TV shows** in recent years
- Certain genres dominate the platform, while others show emerging growth
- Content production is concentrated in a few key countries
- Rapid content expansion occurred during specific growth phases

---

## 📁 Project Structure
📦 NetFlix Titles
┣ 📂 data
┃ ┗ netflix.csv
  ┗ netflix_cleaned.csv
┣ 📂 Notebook
┃ ┗ Netflix.ipynb
┣ 📄 Insights.txt
┣ 📄 README.md
┣ 📄 requirements.txt
┗ 📄 .gitignore
