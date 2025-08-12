---
layout: single
title: "Data Wrangling"
permalink: /data-wrangling/
author_profile: true
---

## 🧹 Data Wrangling Project #1 – Netflix Dataset (Kaggle)

**Overview:**  
This was my **first** data wrangling project, where I cleaned and wrangled the Netflix Movies and TV Shows dataset to uncover insights such as content trends, release patterns, and rating distributions. Focused on data preprocessing and storytelling. 

**Dataset:**  
- 📊 **Source:** [Netflix Movies & TV Shows – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows/data)  
- 📦 **Size:** ~8807 entries, 0 to 8806 titles, genres, release years, ratings, countries, and more.  

**Project Highlights:**  
- 🚀 **Why It’s Special:** This project introduced me to **data wrangling fundamentals**, from identifying missing values to standardizing inconsistent formats.  
- 🛠 **Skills Demonstrated:**  
  - Importing CSV data with **Pandas**.  
  - Handling **missing values** (imputation, removal).  
  - Parsing and standardizing **date formats**.  
  - Splitting and normalizing multi-valued fields (e.g., genres, countries).  
  - Removing duplicates and irrelevant entries.  
  - Preparing cleaned data for further analysis and dashboards.
  
**Tools & Technologies:**  
`Python`, `Pandas`, `NumPy`, `Jupyter Notebook`

**Workflow Overview:**  
1. **Load Dataset:** Import Netflix CSV file from Kaggle.  
2. **Initial Exploration:** Check dataset shape, column info, and missing value summary.  
3. **Data Cleaning:**  
   - Replace missing country values with placeholders.  
   - Standardize `date_added` into proper datetime format.  
   - Normalize genre and director columns.  
4. **Transformation:**  
   - Extract year from release dates.  
   - Create binary flags for movie vs. TV show.  
5. **Export:** Save final cleaned dataset as a new CSV file ready for visualization.  


🔗 [View Project on Kaggle Notebook](https://www.kaggle.com/code/jedidahwavinya/netflix-figures) 

💡 *Being my first data wrangling project, this was the perfect introduction to turning messy, raw datasets into clean, structured, and analysis-ready data.*  

---

🔙 [**Jump Back to Projects Categories**](/projects.md)

---
