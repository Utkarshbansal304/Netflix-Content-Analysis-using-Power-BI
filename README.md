# 📊 Netflix Content Analysis using Power BI

## 📌 Overview
This repository contains a complete data analytics case study on Netflix movies and TV shows using **Power BI**.  
The project focuses on analyzing content trends, IMDb ratings, runtime patterns, and audience engagement over time through interactive visualizations.

---

## 🔗 Project Resources
- 📁 **Dataset:**  
  https://docs.google.com/spreadsheets/d/1oZSdr3oeHu1Y9bEAc4xneNEBYgWabpyd/edit?usp=sharing

- 📄 **Case Study Report (PDF):**  
  https://drive.google.com/file/d/1CcHsxw7fTSbXWF_DUxYUdUO4aPcr3GFs/view?usp=sharing

---

## 📁 Dataset Summary
- **Total Records:** 5,283
- **Content Types:** Movies and TV Shows
- **Time Period:** 1953 – 2022

### Key Columns
- `id` – Unique identifier  
- `title` – Content title  
- `type` – Movie / TV Show  
- `release_year` – Year of release  
- `runtime` – Duration in minutes  
- `imdb_score` – IMDb rating  
- `imdb_votes` – IMDb vote count  
- `age_certification` – Content rating  

---

## 🧹 Data Cleaning & Transformation
All data preparation was performed using **Power Query Editor** in Power BI:

- Removed unnecessary columns (`index`, `imdb_id`)
- Retained rows with missing IMDb votes while excluding them from vote-based analysis
- Created a custom weighted metric to combine rating quality and popularity:

