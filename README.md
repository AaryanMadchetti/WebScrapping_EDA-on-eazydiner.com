# WebScrapping_EDA-on-eazydiner.com

# 🍽️ Restaurant Data Analysis using Web Scraping & EDA

This project focuses on extracting restaurant details from EazyDiner using web scraping and performing exploratory data analysis (EDA) to uncover city-wise food trends, pricing, discounts, and cuisine preferences across major Indian cities.

## 📌 Objective

The goal of this project is to:
- Automate data extraction from EazyDiner across multiple cities
- Clean and preprocess raw HTML-based data
- Perform EDA to discover valuable insights about the restaurant industry
- Present findings through well-structured visualizations

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python  
- **Web Scraping:** `requests`, `BeautifulSoup`  
- **Data Manipulation:** `pandas`, `numpy`  
- **Visualization:** `matplotlib`, `seaborn`  
- **IDE:** Jupyter Notebook

---

## 🗺️ Cities Covered

- Mumbai  
- Pune  
- Bengaluru  
- Ahmedabad  

**Data Volume:**  
- 135 restaurants per city  
- Total of **540 restaurant records**

---

## 📊 Features Scraped

- Restaurant Name  
- Rating  
- Cuisine(s) Offered  
- Location  
- Approximate Cost for Two  
- Available Discount  

---

## 🧹 Data Cleaning Steps

- Parsed `approx` and `discount` fields into numerical values  
- Extracted city and area from combined location strings  
- Normalized inconsistent cuisine names  
- Handled missing, malformed, and inconsistent HTML structures  

---

## 🔍 Exploratory Data Analysis Highlights

- **Top-rated restaurants** by city and area  
- **Average dish price** and **discount comparison** across cities  
- **Most common cuisines** and **category breakdown**  
- **Bivariate analysis** of ratings vs price, discount vs price, etc.  

---

## 📌 Use Cases

- City-wise **food guides** for consumers  
- Insights for **food delivery startups** or **restaurant franchises**  
- Useful for **investor planning** and **location targeting**

---

## 📷 Screenshots / Visuals

📈 Included in the `EDAandDV.ipynb` notebook and project presentation.  

---

This project strengthened my practical understanding of:
- End-to-end data pipelines
- Real-world data extraction challenges
- The power of EDA in translating raw data into valuable insights

---

## 🗂️ Repository Structure

📦 Restaurant-WebScraping-EDA
├── 📄 restaurant_extraction.ipynb # Web scraping logic
├── 📄 rest_data_cleaning.ipynb # Data cleaning and processing
├── 📄 EDAandDV.ipynb # EDA and visualizations
├── 📄 restaurant_data.csv # Raw extracted dataset
├── 📄 rest_cleandata.csv # Cleaned dataset
├── 📄 myPPT.pptx # Project presentation
└── 📄 README.md # Documentation

---

## 🔗 Connect With Me

🔗 www.linkedin.com/in/aryanmadchetti1110

---
