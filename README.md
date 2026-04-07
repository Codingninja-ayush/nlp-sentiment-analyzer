# nlp-sentiment-analyzer
Product Review Summarizer and Sentiment Analyzer using NLP
# 🧠 Product Review Summarizer & Sentiment Analyzer

![Python](https://img.shields.io/badge/Python-3.x-blue)
![NLP](https://img.shields.io/badge/NLP-NLTK-green)
![ML](https://img.shields.io/badge/ML-Naive%20Bayes-orange)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle%20Amazon%20Reviews-yellow)
![College](https://img.shields.io/badge/VIT-Bhopal-red)

> CSA4028 Natural Language Processing — Mini Project  
> VIT Bhopal | Winter Semester 2025-26

---

## 📌 Project Overview

A hybrid NLP pipeline that integrates **rule-based preprocessing** and 
**machine learning** to automatically analyze Amazon product reviews, 
extract pros and cons, and classify sentiment as Positive, Negative, 
or Neutral.

The project includes a **live interactive website** built with Flask 
and hosted via ngrok directly from Google Colab.

---

## 🌐 Features

- ✅ Real Amazon reviews dataset from Kaggle (500k+ reviews)
- ✅ VADER sentiment analysis (Positive / Negative / Neutral)
- ✅ Aspect extraction — automatically finds Pros and Cons
- ✅ Naive Bayes classifier with 83%+ accuracy
- ✅ Product summaries with Recommended / Not Recommended verdict
- ✅ Live interactive website with browser link
- ✅ 5-page dashboard — Overview, Products, Demo, Pipeline, About

---

## 👥 Team Members

| Name | Register Number |
|------|----------------|
| Atharw Dwivedi | 23BAI11373 |
| Ayushman Mishra | 23BAI11256 |
| Rana Talukdar | 23BAI10186 |
| Mohammad Kaif | 23BAI10510 |

---

## 🛠️ Technology Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| NLTK | Tokenization, POS tagging, VADER |
| Scikit-learn | Naive Bayes classifier, CountVectorizer |
| Pandas | Data manipulation |
| Flask | Web server |
| pyngrok | Public browser link |
| Kaggle | Amazon Reviews dataset |

---

## 🔄 NLP Pipeline
Raw Text
↓
Text Normalization (Regex)
↓
Tokenization (NLTK)
↓
Stopword Removal
↓
Stemming (Porter Stemmer)
↓
POS Tagging
↓
Bag of Words Vectorization
↓
Naive Bayes Classification
↓
Sentiment + Pros & Cons Output
---

## 📊 Results

| Metric | Score |
|--------|-------|
| Accuracy | 83.25% |
| Precision | 0.83 |
| Recall | 0.83 |
| F1-Score | 0.83 |
| Dataset Size | 3000 reviews (balanced) |
| Train Split | 80% — 2400 samples |
| Test Split | 20% — 600 samples |

---

## 🚀 How to Run

**Step 1 — Open in Google Colab**
- Download the `.ipynb` file from this repository
- Go to colab.research.google.com
- Click File → Upload Notebook → Select the file

**Step 2 — Get Kaggle API Key**
- Go to kaggle.com → Your Profile → Settings
- Scroll to Legacy API Credentials → Click Create Legacy API Key
- It downloads `kaggle.json` to your computer
- Upload it when Cell 2 asks

**Step 3 — Get ngrok Token**
- Go to dashboard.ngrok.com and sign up free
- Copy your authtoken from the dashboard
- Paste it in Cell 7 where it says PASTE_YOUR_TOKEN_HERE

**Step 4 — Run All Cells**
- Click Runtime → Run All
- Wait for all 7 cells to complete
- Copy the live website link printed by Cell 7
- Open the link in any browser

---

## 📁 Project Structure
---

## 📋 Cell Breakdown

| Cell | Description |
|------|-------------|
| Cell 1 | Install libraries and download NLTK data |
| Cell 2 | Upload Kaggle API key and download dataset |
| Cell 3 | Load, clean and prepare the dataset |
| Cell 4 | Train Naive Bayes model and evaluate accuracy |
| Cell 5 | VADER sentiment scoring and aspect extraction |
| Cell 6 | Build product summaries and prepare dashboard data |
| Cell 7 | Launch Flask website with ngrok public URL |

---

## ⚠️ Limitations

- Bag-of-Words model ignores word context and order
- Naive Bayes assumes feature independence
- Cannot handle sarcasm or idiomatic expressions
- ngrok link expires when Colab session ends

---

## 🔮 Future Scope

- Word2Vec and GloVe word embeddings for better context
- LSTM and Transformer based deep learning models
- Multi-language sentiment analysis support
- Permanent cloud deployment using Heroku or AWS
- Real-time product scraping from e-commerce sites

---

## 📚 References

1. Jurafsky, D., & Martin, J. H. — Speech and Language Processing
2. NLTK Documentation — https://www.nltk.org
3. Scikit-learn Documentation — https://scikit-learn.org
4. Amazon Fine Food Reviews — Kaggle Dataset by Snap Stanford
5. VADER: A Parsimonious Rule-based Model for Sentiment Analysis
6. Porter, M.F. — An Algorithm for Suffix Stripping (1980)
7. Tom Mitchell — Machine Learning (1997)

---

*Made with ❤️ by Team 
