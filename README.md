# Sentiment Dynamics and Topic Analysis of Greece’s Premier Summer Islands Destinations

---

# 📌 Project Overview

This project was developed as part of a short-term consulting collaboration between **Mentionlytics** and the **Big Blue Data Academy**.

The objective was to analyze social media conversations related to five of the most popular Greek summer destinations:

- 🏝 Santorini  
- 🌊 Mykonos  
- ☀️ Rhodes  
- 🌴 Crete  
- 🏖 Corfu  

The project focuses on understanding **how users discuss these destinations online**, identifying sentiment trends, discussion topics, and behavioral patterns across social media platforms.

By combining **Natural Language Processing techniques**, **data analysis**, and **interactive visualization**, the project aims to provide valuable insights into tourism perception and online engagement.

---

# 🎯 Project Goals

The primary goals of this project were:

- 📊 Collect, aggregate, and analyze social media data related to Greek tourism  
- 😊 Perform **sentiment analysis** on user-generated posts  
- 🧠 Identify **dominant topics and trends** using Natural Language Processing techniques such as **Latent Dirichlet Allocation (LDA)**  
- 🔍 Understand user behavior and preferences through sentiment dynamics  
- 📈 Build an **interactive Power BI dashboard** to present and explore the results  

---

# 🧰 Tools and Technologies

## 🐍 Python

Python served as the primary programming language for data analysis and preprocessing.

**Libraries used:**

- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- spaCy  
- Gensim  
- VADER  
- EmoLex  

These libraries supported the **data preparation, sentiment analysis, topic modeling, and visualization tasks**.

---

## 📊 Power BI

Power BI was used to develop an **interactive dashboard** that enables dynamic exploration of the analysis results and tourism metrics.

---

## 🌍 Translation Service

Because social media data contained multiple languages, the **Google Cloud Translate API** was used to automatically translate non-English posts into English.

This ensured:

- consistent analysis  
- compatibility with NLP tools  
- unified text processing across the dataset

---

# ⚙️ Methodology

The analytical workflow followed several structured stages designed to transform raw social media data into actionable insights.

---

## 📥 Data Collection

The dataset was collected using the **Mentionlytics platform**, which monitors and aggregates online discussions across multiple platforms.

The collected data included posts from:

- Twitter (X)  
- Facebook  
- Instagram  
- Blogs  
- Web sources  

Additionally, the project incorporated **official tourism statistics from the Bank of Greece**, including:

- tourist arrivals  
- tourism revenue  
- average cost per overnight stay  

These statistics covered the period **2005–2023** and provided important context for interpreting tourism trends.

---

## 🧹 Data Cleaning

Before performing analysis, the dataset underwent preprocessing steps including:

- removal of unnecessary characters and symbols  
- Unicode normalization  
- standardization of text formats  
- filtering irrelevant posts through exploratory data analysis  

This step ensured that the dataset contained only relevant content suitable for NLP analysis.

---

## 🌐 Content Translation

Because the dataset included posts written in multiple languages, the **Google Cloud Translation API** was used to translate non-English posts into English.

This enabled:

- consistent sentiment analysis  
- compatibility with NLP libraries  
- unified processing across all posts

---

## 🤖 Sentiment and Topic Analysis

After preparing the dataset, multiple NLP techniques were applied.

### 😊 Sentiment Analysis

Sentiment analysis was performed using **VADER**, which is specifically designed for analyzing social media text.

Each post received a sentiment score that allowed the classification of posts as:

- positive  
- neutral  
- negative

---

### 🧠 Named Entity Recognition (NER)

Using **spaCy**, entities such as:

- locations  
- organizations  
- individuals  

were extracted from social media posts.

This allowed linking sentiment trends to specific entities and destinations.

---

### 📚 Topic Modeling

**Latent Dirichlet Allocation (LDA)** was used to identify dominant themes in the dataset.

Topic modeling revealed the most common discussion topics related to Greek summer destinations.

---

# 📊 Dashboard Overview

The results of the analysis were presented through an **interactive Power BI dashboard** designed to facilitate exploration of the insights.

The dashboard includes a **custom Page Navigator**, allowing users to easily navigate across different analytical sections.

---

# 📈 General Information Dashboard

This page provides a high-level overview of tourism activity in Greece using official tourism statistics.

Key metrics displayed include:

- total tourist arrivals  
- tourism revenue  
- average cost per night  
- tourism trends between **2005–2023**

<img width="925" height="501" alt="image" src="https://github.com/user-attachments/assets/ee92207a-608e-438a-be5d-eec1cdc3dad2" />

# 🌐 All Platforms Analysis

The **All Platforms** page analyzes social media discussions across all monitored platforms.

The analysis focuses on:

- mention sources across platforms  
- daily mention activity  
- sentiment distribution  
- engagement metrics  

Engagement metrics include:

- likes  
- comments  
- shares  

The dashboard also analyzes **daily engagement rate**, which aggregates interactions and divides them by the follower count of the posting account.

<img width="925" height="515" alt="image" src="https://github.com/user-attachments/assets/8b5c6cf1-0570-4cf1-b161-7fb054e15b64" />

# 😊 Sentiment Analysis

The **Sentiment Analysis** page explores the emotional tone of social media discussions.

Key visualizations include:

- sentiment distribution  
- emotion analysis  
- sentiment score index (from -1 to 1)  
- word cloud visualization  

Users can filter the analysis by:

- destination  
- platform  
- entity type  
- topic  

<img width="925" height="516" alt="image" src="https://github.com/user-attachments/assets/bb5f5b79-a25d-4081-81ea-2ceb8a225175" />

# 🧠 Recognized Entities

The **Recognized Entities** page displays entities detected within the dataset and their associated sentiment scores.

Users can:

- explore the most mentioned entities  
- analyze sentiment scores related to each entity  
- compare sentiment across destinations  

Interactive filters allow deeper exploration of entity-level insights.

<img width="925" height="518" alt="image" src="https://github.com/user-attachments/assets/749073bf-2cea-43a8-829d-0fc7e5bde3e4" />


---

# 🎥 Project Presentation

A full presentation explaining the project methodology, analysis workflow, and dashboard insights is available below.

▶️ **Watch the presentation**

https://www.youtube.com/watch?v=b9suQJhGrlg&t=2s

---

# 📌 Conclusion

This project demonstrates how **social media analytics combined with Natural Language Processing** can generate valuable insights for tourism analysis.

By analyzing sentiment dynamics, identifying dominant discussion topics, and visualizing the results through an interactive dashboard, the project provides a deeper understanding of how travelers perceive Greece’s most popular summer destinations.
