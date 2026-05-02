# Sentiment Analysis on Product Reviews

## Project Overview

This project focuses on analyzing customer reviews from an e-commerce dataset and classifying them into **Positive, Negative, or Neutral sentiments** using Natural Language Processing (NLP).

The goal is to automate the process of understanding customer feedback and extract meaningful insights that can help businesses improve their products and services.

---

## Problem Statement

E-commerce platforms receive thousands of reviews daily. Manually analyzing them is inefficient.
This project builds a system that:

* Reads product reviews
* Classifies sentiment
* Generates insights using data visualization

---

## Dataset

* Dataset used: Amazon Fine Food Reviews
* Source: Kaggle
* Rows used: First 5000 entries

---

## Tools & Technologies

* Python 3.14
* Jupyter Notebook
* Pandas
* TextBlob
* Matplotlib
* Seaborn
* WordCloud

---

## Project Workflow

### 1. Data Loading & Exploration

* Loaded dataset using Pandas
* Displayed initial rows
* Explored dataset structure

### 2. Data Cleaning

* Removed null and empty reviews
* Removed duplicate entries
* Selected relevant columns (`Text`, `Score`)

### 3. Sentiment Analysis

* Used TextBlob to calculate polarity
* Classified reviews:

  * Positive (score > 0)
  * Negative (score < 0)
  * Neutral (score = 0)

### 4. Visualization

* Bar chart of sentiment counts
* Pie chart of sentiment distribution
* Score vs Sentiment comparison
* WordCloud of negative reviews

---

## Key Insights

* Majority of reviews are **positive**, indicating good customer satisfaction
* Negative reviews mainly highlight:

  * Product quality issues
  * Packaging problems
* Some high-rated products still show negative sentiment
* Neutral reviews are very limited

---

## Recommendation

The business should focus on:

* Improving product consistency
* Enhancing packaging quality
* Addressing recurring complaints from negative reviews

---

## Project Structure

```
SentimentAnalysis_YourName/
│
├── analysis.ipynb
├── Reviews.csv
├── summary.pdf
├── charts/
│   ├── bar_chart.png
│   ├── pie_chart.png
│   ├── score_vs_sentiment.png
│   ├── wordcloud.png
```

---

## How to Run

1. Install required libraries:

   ```
   pip install pandas matplotlib seaborn textblob wordcloud
   python -m textblob.download_corpora
   ```
2. Open `analysis.ipynb` in Jupyter Notebook
3. Run all cells

---

## Author
Ankit Kumar

---

## Note

This project was completed as part of an internship to demonstrate skills in data analysis, NLP, and visualization.
