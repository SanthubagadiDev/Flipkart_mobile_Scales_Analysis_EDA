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

## 📊 RAM Distribution

This chart shows the distribution of mobile phone models based on their **RAM capacity** in the dataset.

### Key Insights

- **🔹 Dominant Choice:**  
  **8 GB RAM** is the most common configuration, representing **64.2%** of all devices.  
  This indicates that **8 GB has become the standard RAM configuration** for most smartphones.

- **🔹 Mid-Range Segment:**  
  - **12 GB RAM:** 12.5%  
  - **6 GB RAM:** 12.4%  

  These configurations represent the **upper-mid and lower-mid smartphone segments**.

- **🔹 Extreme Segments:**  
  - **4 GB RAM (9.6%)** – Typically found in **budget or entry-level smartphones**.  
  - **16 GB RAM (1.3%)** – A very small portion of the dataset, usually present in **high-end flagship or gaming smartphones**.

---

## 💾 ROM Distribution

This chart illustrates the distribution of **internal storage (ROM)** among the mobile phones in the dataset.

### Key Insights

- **🔹 Majority Storage Option:**  
  **128 GB** is the most common storage capacity, accounting for **52.5%** of the phones.

- **🔹 Premium Standard:**  
  **256 GB** follows closely with **43.8%** of the models.

  Together, **128 GB and 256 GB storage make up more than 96% of the dataset**, indicating that modern smartphones have largely standardized around these two storage capacities.

- **🔹 Rare Storage Segments:**  
  - **64 GB (3.3%)** – Becoming increasingly rare and mostly found in **budget smartphones**.  
  - **512 GB (0.4%)** – Extremely rare in this dataset and typically available only in **ultra-premium flagship devices**.
### pie chart
<img src="Screenshot 2026-03-13 161649.png" width="700">
---

## 📈 Summary

| Feature | Most Common Value | Percentage |
|-------|------------------|-----------|
| RAM | 8 GB | 64.2% |
| Storage (ROM) | 128 GB | 52.5% |
| Premium Storage | 256 GB | 43.8% |

These distributions highlight how **modern smartphones are converging toward standardized hardware configurations**, particularly **8 GB RAM and 128–256 GB storage**.

---
## 🔹 Bivariate Analysis
### Bar Chart

<img src="Screenshot 2026-03-13 161830.png" width="700">

A bar chart was created to compare the most expensive mobile model for each brand. This visualization helps analyze how selling price varies across different brands and identify which brand offers the highest priced smartphone.

---
## 🔹 Multivariate Analysis

<img src="Screenshot 2026-03-13 161911.png" width="700">

### Correlation Analysis

<img src="Screenshot 2026-03-13 161946.png" width="700">

A correlation heatmap was created to analyze relationships between multiple numerical variables such as price, RAM, ROM, ratings, and reviews. The heatmap helps identify how strongly different features are related to each other. For example, selling price has a strong correlation with original price, and the number of ratings is highly correlated with the number of reviews.

---

## 📈 Key Insights

- Most smartphones fall within the **mid-range price category**.
- Devices with **higher RAM and storage generally have higher prices**.
- Some brands offer **better specifications at competitive prices**.
- Most mobile phones maintain **high ratings above 4.0**.

