# Netflix Data Analysis 🎬📊

## 📌 Project Overview
This project analyzes the Netflix Movies and TV Shows dataset to uncover meaningful insights about content distribution, growth trends, genre popularity, country-wise contribution, ratings, and movie duration.  
The goal is to demonstrate an end-to-end data analytics workflow using **Python** , similar to real-world business analysis tasks.

---

## 🎯 Objectives
- Clean and preprocess raw Netflix data  
- Perform Exploratory Data Analysis (EDA)  
- Engineer useful features (year added, duration in minutes, main country, genre split)  
- Visualize trends and patterns  
- Derive business insights and recommendations
  
---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)  
- Data Visualization: Matplotlib, Seaborn
- Excel 
- Jupyter Notebook  
- GitHub  

---

## 📂 Dataset
- Source: Netflix Movies and TV Shows dataset (public dataset)  
- Columns include:  
  `show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description`

---

## 🔧 Data Cleaning & Feature Engineering
- Removed duplicates  
- Handled missing values (director, cast, country, rating, duration)  
- Converted `date_added` to datetime format  
- Extracted `year_added` and `month_added`  
- Extracted numeric `duration_minutes` for Movies  
- Extracted `main_country` from country column  
- Split multi-value `listed_in` (genres) for analysis  

---

## 📊 Key Analysis & Visualizations
- Movies vs TV Shows distribution  
- Content growth over time  
- Top content producing countries  
- Top 10 Movie genres & TV Show genres  
- Rating distribution  
- Movie duration distribution  
- Movies vs TV Shows trend by year  
- Seasonality analysis using month-wise heatmap  

---

## 🔎 Key Insights
- Movies dominate the Netflix catalog, while TV Shows are increasing over time  
- Rapid content growth after 2016 shows aggressive platform expansion  
- The US and India are major content contributors  
- Drama and International content are the most popular genres  
- Most content targets mature audiences (TV-MA, TV-14)  
- Most movies are between 80–120 minutes in duration  
- Increasing focus on TV Shows supports user retention and binge-watching  

---

## 💡 Business Recommendations
- Increase investment in international drama content  
- Continue expanding TV Shows to improve user retention  
- Diversify Kids & Family content to balance the catalog  
- Use seasonal trends to time major content releases  

---


