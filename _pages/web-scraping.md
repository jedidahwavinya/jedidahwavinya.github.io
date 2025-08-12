## 🕸️ Web Scraping Project #1 – "Scrape This Site" Forms Page

**Overview:**  
This was my **first** hands-on web scraping project, where I set out to build a Python-based solution capable of **navigating a webpage**, **extracting structured table data**, and saving it into a clean, analysis-ready spreadsheet.  

**Project Highlights:**  
- 🌐 **Target Site:** [Scrape This Site – Forms Page](https://www.scrapethissite.com/pages/forms/)  
- 🚀 **Why It’s Special:** My entry point into web scraping — this project gave me the foundational skills I later applied to more advanced scraping tasks.  
- 🔍 **Skills Demonstrated:**  
  - Navigating multi-page form-based sites.  
  - Extracting tabular data with **BeautifulSoup** and **Requests**.  
  - Automating **pagination** to capture full datasets.  
  - Cleaning & structuring data before export.  
  - Saving clean datasets to **Excel/CSV** format.  
- 🛠️ **Tech Stack:**  
  - Python  
  - BeautifulSoup4  
  - Requests  
  - Pandas  

**Workflow Overview:**  
1. **Navigate the Page:** Load HTML structure via HTTP requests.  
2. **Extract Table Data:** Identify and retrieve team stats from HTML tables.  
3. **Handle Pagination:** Loop through multiple result pages automatically.  
4. **Data Cleaning:** Remove inconsistencies for uniform formatting.  
5. **Save Results:** Export final dataset to CSV/Excel for further analysis.  

**Sample Output:**  
| Team Name           | Year | Wins | Losses | OT Losses | Win % | Goals For | Goals Against | + / - |
|---------------------|------|------|--------|-----------|-------|-----------|---------------|-------|
| Boston Bruins       | 1990 | 44   | 24     | 12        | 0.61  | 299       | 264           | +35   |
| Chicago Blackhawks  | 1990 | 49   | 23     | 8         | 0.66  | 284       | 211           | +73   |
| ...                 | ...  | ...  | ...    | ...       | ...   | ...       | ...           | ...   |

📂 **Colab Notebook:**  
[▶ Open in Google Colab](https://colab.research.google.com/drive/YOUR_NOTEBOOK_ID_HERE)  

💡 *Being my first web scraping project, this one holds a special place — it was where I learned how to navigate complex HTML structures, automate data extraction, and prepare results for real-world use.*  
