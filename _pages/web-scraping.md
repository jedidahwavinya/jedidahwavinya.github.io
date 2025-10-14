---
layout: single
title: "Web scraping"
permalink: /web-scraping/
author_profile: true
---

## 🕸️ Web Scraping Project #1 – "Scrape Site" Forms Page

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

📂 **Colab Notebook:**  
[▶ Open in Google Colab](https://colab.research.google.com/drive/1MkBh0lAY3_n9aZcyuKesQRCM3gIt3INr?usp=sharing)


💡 *Being my first web scraping project, this one holds a special place — it was where I learned how to navigate complex HTML structures, automate data extraction, and prepare results for real-world use.*  

---

## 🕸️ Web Scraping Project #2 – Largest U.S. Companies by Revenue

**Overview:**  
Scraped tabular data from **Wikipedia**’s *List of largest companies in the United States by revenue* to collect business information for analysis.

**Target URL:**  
[Wikipedia – Largest Companies in the U.S. by Revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)  

**Data Extracted:**  
- Rank  
- Name  
- Industry  
- Revenue (USD millions)  
- Revenue growth  
- Employees  
- Headquarters  

**Key Tasks:**  
- Retrieved HTML table using **Requests** and **BeautifulSoup**.  
- Parsed and structured the dataset with **Pandas**.  
- Exported clean data to **CSV** for further analysis.  

**Tools:**  
Python, BeautifulSoup, Requests, Pandas  

📂 **Colab Notebook:**  
[▶ Open in Google Colab](https://colab.research.google.com/drive/1lF3hQ3bzoS6ymfLodDtCCjDWNG_8_hlN?usp=sharing) 

---

### 🕸️ Web Scraping Project #3 – NFL Teams Stats Data  

**Overview:**  
Scraped detailed **team statistics data** from the **NFL official website** to analyze team performance metrics for the current season.

**Target URL:**  
NFL – Teams Statistics Page  

**Data Extracted:**  
- Team Name  
- Wins  
- Losses  
- Points Scored  
- Points Allowed  
- Passing Yards  
- Rushing Yards  
- Turnovers  

**Key Tasks:**  
- Sent HTTP requests to retrieve the webpage content using **Requests**.  
- Parsed and extracted relevant statistics using **BeautifulSoup**.  
- Cleaned and organized the dataset into a structured format with **Pandas**.  
- Exported the final dataset to **CSV** for further visualization and analysis.  

**Tools:**  
Python, Requests, BeautifulSoup, Pandas  

📂 **Colab Notebook:**  
▶ [Open in Google Colab](https://colab.research.google.com/drive/1stQ0EJB_Eq4_Fdvv1jFCgtvsPPafgZf9?usp=sharing) – View my third project where I scraped and analyzed team stats data from the NFL website.

---

# 🗞️ Web Scraping Project #4 – Global News Aggregator

---

## 📘 Overview
With so many different news channels popping up, it has become increasingly difficult to keep track of all kinds of news that highlight relevant happenings worldwide.  
This project aims to build a **customized one-stop solution** that scrapes and consolidates the latest global news from multiple trusted sources into one central platform.

---

## 🎯 Objective
To collect, clean, and organize global news data from various news websites using **web scraping** techniques and display them in a unified format for analysis or personalized viewing.

---

## 🌐 Target News Sources
You can customize your preferred websites or RSS feeds, such as:
- [BBC News](https://www.bbc.com/news)
- [Reuters](https://www.reuters.com)
- [The Guardian](https://www.theguardian.com)
- [Al Jazeera](https://www.aljazeera.com)
- [CNN](https://edition.cnn.com)

---
!pip install newspaper3k feedparser beautifulsoup4 requests lxml python-dateutil tqdm

---

🔙 [**Jump Back to Projects Categories**](/projects.md)

---
