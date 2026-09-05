# 🛡️ TextShield: SMS Spam vs. Ham NLP Classification Pipeline

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-3.8-green)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white)

## 📌 Project Overview
This repository contains an end-to-end Natural Language Processing (NLP) and Supervised Machine Learning classification pipeline built during the **Devtown "NLP with Python" Bootcamp**.

The project focuses on detecting unwanted or malicious spam messages by preprocessing raw text data, extracting numerical features, and training machine learning models to accurately classify incoming text messages as either **Spam** or **Ham** (legitimate).

---

## 🚀 Features & Workflow

- **Text Preprocessing:** Tokenization, stop-word removal, and stemming using `NLTK`.
- **Feature Extraction:** Converting raw text messages into sparse vector representations using `TfidfVectorizer`.
- **Supervised Classification:** Model implementation using `LogisticRegression`, `MultinomialNB`, and `LinearSVC`.
- **Data & Model Analytics:** Class distribution bar charts and confusion matrix visualizations using `Matplotlib` and `Seaborn`.

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python 3
- **NLP Library:** `nltk`
- **Machine Learning:** `scikit-learn`
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`

---

## 🤝 Acknowledgments

Special thanks to **Devtown** and trainer **Jiya Jain* for hosting the 5-Day "NLP with Python" Live Bootcamp in collaboration with **GDG** On Campus and **Microsoft** Learn Student Ambassadors.

---

## 📂 Repository Structure

```text
├── notebooks/                 # Google Colab / Jupyter Notebooks
│   └── spam_classifier.ipynb
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation
