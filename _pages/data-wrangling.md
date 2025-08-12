## 🧹 Data Wrangling Project #1 – Netflix Dataset (Kaggle)

**Overview:**  
This was my **first** data wrangling project, where I explored, cleaned, and transformed the popular **Netflix Movies & TV Shows** dataset from Kaggle to prepare it for analysis and visualization.  

**Dataset:**  
- 📊 **Source:** [Netflix Movies & TV Shows – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- 📦 **Size:** ~6,200 entries of titles, genres, release years, ratings, countries, and more.  

**Project Highlights:**  
- 🚀 **Why It’s Special:** This project introduced me to **data wrangling fundamentals**, from identifying missing values to standardizing inconsistent formats.  
- 🛠 **Skills Demonstrated:**  
  - Importing CSV data with **Pandas**.  
  - Handling **missing values** (imputation, removal).  
  - Parsing and standardizing **date formats**.  
  - Splitting and normalizing multi-valued fields (e.g., genres, countries).  
  - Removing duplicates and irrelevant entries.  
  - Preparing cleaned data for further analysis and dashboards.  

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

**Sample Cleaned Data:**  
| Title                          | Type   | Country        | Release Year | Rating | Duration   | Genre               | Date Added  |
|--------------------------------|--------|----------------|--------------|--------|------------|---------------------|-------------|
| Breaking Bad                   | TV Show| United States  | 2008         | TV-MA  | 5 Seasons  | Crime, Drama, Thriller | 2020-11-01 |
| Inception                      | Movie  | United States  | 2010         | PG-13  | 148 min    | Action, Sci-Fi, Thriller | 2020-10-15 |
| ...                            | ...    | ...            | ...          | ...    | ...        | ...                 | ...         |

📂 **Colab Notebook:**  
[▶ Open in Google Colab](https://colab.research.google.com/drive/YOUR_NOTEBOOK_ID_HERE)  

💡 *Being my first data wrangling project, this was the perfect introduction to turning messy, raw datasets into clean, structured, and analysis-ready data.*  
