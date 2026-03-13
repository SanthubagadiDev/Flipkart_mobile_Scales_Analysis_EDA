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

#### 🔹 Univariate Analysis
Analyzed individual variables to understand distributions.

Examples:
- Price distribution
- RAM distribution
- Brand frequency
- Ratings distribution

#### 🔹 Bivariate Analysis
Studied relationships between two variables.

Examples:
- Price vs Ratings
- RAM vs Price
- Brand vs Average Price

#### 🔹 Multivariate Analysis
## Correlation Analysis

<img src="Screenshot 2026-03-13 161946.png" width="700">


---

## 📈 Key Insights

- Most smartphones fall within the **mid-range price category**.
- Devices with **higher RAM and storage generally have higher prices**.
- Some brands offer **better specifications at competitive prices**.
- Most mobile phones maintain **high ratings above 4.0**.

