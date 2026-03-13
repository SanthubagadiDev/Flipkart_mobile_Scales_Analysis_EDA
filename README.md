# 📱 Flipkart Mobile Sales Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Web Scraping](https://img.shields.io/badge/Web%20Scraping-BeautifulSoup-green)
![EDA](https://img.shields.io/badge/Data%20Analysis-EDA-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project focuses on collecting and analyzing mobile phone data from Flipkart using web scraping techniques.  
The goal of the project is to extract product information and perform **Exploratory Data Analysis (EDA)** to understand pricing patterns, brand distribution, and relationships between mobile specifications and ratings.

This project demonstrates practical skills in:

- Web Scraping
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization

---

## 🛠️ Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Dataset Features

The scraped dataset contains the following attributes:

| Feature | Description |
|------|------|
| Brand | Mobile brand name |
| Model | Mobile model name |
| Color | Mobile color |
| RAM | RAM capacity |
| ROM | Internal storage |
| Selling Price | Discounted price |
| Original Price | Actual price before discount |
| Ratings | Customer rating |
| Reviews | Number of reviews |

---

## ⚙️ Project Workflow

### 1️⃣ Web Scraping
- Sent HTTP requests to Flipkart product pages.
- Parsed HTML using BeautifulSoup.
- Extracted mobile specifications, prices, and ratings.

### 2️⃣ Data Cleaning
- Removed special characters from price fields.
- Converted price and rating columns into numeric values.
- Handled missing values and duplicates.

### 3️⃣ Exploratory Data Analysis

## 🔹 Univariate Analysis


## 🔹 Bivariate Analysis
### Bar Chart

<img src="
Screenshot 2026-03-13 161830.png" width="700">

A bar chart was created to compare the most expensive mobile model for each brand. This visualization helps analyze how selling price varies across different brands and identify which brand offers the highest priced smartphone.

---
## 🔹 Multivariate Analysis
### Correlation Analysis

<img src="Screenshot 2026-03-13 161946.png" width="700">

A correlation heatmap was created to analyze relationships between multiple numerical variables such as price, RAM, ROM, ratings, and reviews. The heatmap helps identify how strongly different features are related to each other. For example, selling price has a strong correlation with original price, and the number of ratings is highly correlated with the number of reviews.

---

## 📈 Key Insights

- Most smartphones fall within the **mid-range price category**.
- Devices with **higher RAM and storage generally have higher prices**.
- Some brands offer **better specifications at competitive prices**.
- Most mobile phones maintain **high ratings above 4.0**.

