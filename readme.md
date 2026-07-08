<div align="center">

# 🍽️ Zomato Geospatial & NLP Analysis

### SQL • Python • NLP • Geospatial Visualization • Business Intelligence

<p>
An end-to-end Exploratory Data Analysis (EDA) project on the Zomato Bangalore restaurant dataset using SQL, Python, Natural Language Processing (NLP), and Geospatial Analysis.
</p>

<img src="Screenshot/HeatMap Bengaluru.JPG" width="900"/>

</div>

---

# 📖 Project Overview

This project explores the **Zomato Bangalore Restaurant Dataset** to uncover valuable business insights using **Exploratory Data Analysis (EDA)**, **Natural Language Processing (NLP)**, and **Geospatial Visualization**.

The analysis investigates customer behavior, restaurant trends, review patterns, and geographical restaurant distribution to provide actionable insights for business decision-making.

---

# 🎯 Objectives

- Analyze restaurant ratings and online ordering trends
- Explore restaurant types across Bangalore
- Perform NLP on customer reviews
- Identify frequent words, bigrams, and trigrams
- Visualize restaurant density using Heatmaps
- Generate business insights from the collected data

---

## 📂 Dataset

The dataset used in this project is hosted on Kaggle due to GitHub's 100 MB file size limit.

You can download it here:

**Kaggle Dataset:** https://www.kaggle.com/datasets/pandyaparam/zomato-rawdata-geo-data

After downloading, place the SQLite database in the project root (or the `data/` folder, depending on your project structure).

---

# 🚀 Tech Stack

<table>
<tr>
<td><b>Language</b></td>
<td>Python</td>
</tr>

<tr>
<td><b>Database</b></td>
<td>SQLite</td>
</tr>

<tr>
<td><b>Libraries</b></td>
<td>

- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Geopy
- Folium

</td>
</tr>

<tr>
<td><b>IDE</b></td>
<td>Jupyter Notebook / Kaggle</td>
</tr>

</table>

---

# 📂 Project Structure

```text
zomato-geospatial-nlp-analysis/
│
├── screenshots/
│   └── HeatMap Bengaluru.JPG
│
├── zomato-geographical.ipynb
├── zomato_rawdata.sqlite
├── requirements.txt
├── LICENSE
└── README.md
```

---

# 📊 Analysis Performed

✔ Data Loading

✔ Data Cleaning

✔ Missing Value Analysis

✔ Online Ordering Analysis

✔ Restaurant Type Analysis

✔ Customer Review Preprocessing

✔ Word Frequency Analysis

✔ Bigram Analysis

✔ Trigram Analysis

✔ Geospatial Visualization

✔ Restaurant Density Heatmap

✔ Business Insight Generation

---

# 🧠 NLP Workflow

```text
Customer Reviews
        │
        ▼
Lowercase Conversion
        │
        ▼
Tokenization
        │
        ▼
Stopword Removal
        │
        ▼
Word Frequency
        │
        ▼
Bigrams
        │
        ▼
Trigrams
```

---

# 🌍 Geospatial Analysis

Restaurant locations were converted into latitude and longitude coordinates using **Geopy (Nominatim)** and visualized using **Folium**.

The heatmap highlights restaurant concentration across Bangalore, helping identify major food hubs and business hotspots.

---

# 📌 Key Insights

### 📈 Online Ordering

- Restaurants offering online ordering generally receive higher customer engagement.
- Digital ordering plays a significant role in restaurant popularity.

---

### 🍴 Restaurant Types

- Quick Bites dominate the Bangalore restaurant ecosystem.
- Casual Dining and Cafés are also highly represented.

---

### 💬 Customer Reviews

Most reviews focus on:

- Food Quality
- Taste
- Service
- Ambience
- Value for Money

---

### 🗺️ Geospatial Insights

Restaurant density is highest around:

- Koramangala
- Indiranagar
- Central Bengaluru
- JP Nagar
- MG Road

These regions represent major commercial food hubs.

---

# ⚠️ Note

This project uses the free **OpenStreetMap Nominatim API** for geocoding.

Since the service is rate-limited, geocoding requests may occasionally timeout. For production use, cached coordinates or commercial geocoding services are recommended.

---

# 📈 Future Improvements

- Sentiment Analysis using BERT
- Restaurant Recommendation System
- Interactive Dashboard using Streamlit
- Rating Prediction using Machine Learning
- Real-time Restaurant Analytics Dashboard

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/Param-Pandya/zomato-geospatial-nlp-analysis.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 👨‍💻 Author

### Param Pandya

AI/ML Engineer • Data Scientist • Python Developer

GitHub: https://github.com/Param-Pandya

LinkedIn: https://www.linkedin.com/in/parampandya

Portfolio: https://parampandya.vercel.app

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

</div>
