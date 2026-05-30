# 🐦 Twitter Sentiment Analysis & Web Application

![Python](https://img.shields.io/badge/Python-3.8-blue)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![Dataset](https://img.shields.io/badge/Dataset-1.6M%20Tweets-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-76.98%25-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Overview
End-to-end NLP project analysing 1.6 Million tweets to classify 
sentiment as Positive or Negative using Machine Learning. 
Includes a live interactive web application built with Streamlit
featuring real-time tweet sentiment prediction.

## 🚀 Live Web Application
> **Deployment coming soon on Hugging Face Spaces**  
> Features: Live prediction, Word Clouds, Model Performance Dashboard

## 🛠️ Tools & Technologies
- **Language:** Python
- **NLP:** NLTK, TF-IDF Vectorization, Porter Stemmer
- **Machine Learning:** Logistic Regression, Naive Bayes
- **Web App:** Streamlit
- **Visualization:** Matplotlib, Seaborn, WordCloud
- **Statistics:** Scipy, Hypothesis Testing
- **Dataset:** Twitter Sentiment140 — 1.6M tweets

## 📊 Key Results
| Metric | Value |
|---|---|
| Total Tweets Analysed | 100,000 (sampled from 1.6M) |
| Model Accuracy | **76.98%** |
| Algorithm | Logistic Regression + TF-IDF |
| TF-IDF Features | 50,000 |
| Training Data | 80,000 tweets |
| Testing Data | 20,000 tweets |

## 🔍 Web App Features
- ✅ **Live Tweet Predictor** — Type any tweet and get instant result
- ✅ **Confidence Score** — Shows prediction confidence percentage
- ✅ **Batch Analysis** — Analyse multiple tweets at once
- ✅ **Word Clouds** — Visual representation of positive/negative words
- ✅ **Model Performance** — Confusion matrix and accuracy metrics
- ✅ **Interactive Charts** — Sentiment distribution visualizations
- ✅ **Statistical Analysis** — Hypothesis testing results

## 🧠 NLP Pipeline
Raw Tweet
↓
Lowercase Conversion
↓
Remove URLs, @mentions, Hashtags
↓
Remove Punctuation & Numbers
↓
Stopword Removal
↓
Porter Stemming
↓
TF-IDF Vectorization (50,000 features)
↓
Logistic Regression Model
↓
Sentiment Prediction + Confidence Score

## 📈 Analysis Sections
1. Data Loading & Sampling (100K from 1.6M)
2. Text Cleaning & Preprocessing
3. Sentiment Distribution Analysis
4. Tweet Length Analysis
5. Word Frequency Analysis
6. Word Cloud Generation
7. Statistical Hypothesis Testing
8. Machine Learning Model Building
9. Confusion Matrix & Model Evaluation
10. Live Sentiment Prediction
11. Streamlit Web Application

## 📉 Statistical Analysis
- **T-Statistic:** Check notebook
- **P-Value:** Check notebook
- **Result:** Significant difference found between positive and negative tweet lengths (p < 0.05)

## 📂 Project Structure
├── Twitter_Sentiment_Analysis.ipynb  # Main analysis notebook
├── app.py                            # Streamlit web application
├── requirements.txt                  # Python dependencies
├── sentiment_distribution.png        # Sentiment charts
├── tweet_length_analysis.png         # Length analysis
├── word_frequency.png                # Word frequency charts
├── wordcloud.png                     # Word cloud images
└── model_performance.png             # Model performance charts

## 📥 Dataset
Download the dataset from Kaggle:
https://www.kaggle.com/datasets/kazanova/sentiment140

## 👩‍💻 Author
**Shivani Sharma** — Data Analyst  
🎓 PG Certificate in Data Analytics & Generative AI — IIT Kanpur  
🔗 LinkedIn: linkedin.com/in/shivani-sharma-data  
💻 GitHub: github.com/shivani-sharma-data
