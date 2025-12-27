# Twitter Sentiment Analysis

This project performs **sentiment analysis on tweets** using machine learning. It classifies tweets into three categories: **Positive**, **Negative**, and **Irrelevant**. The model leverages **TF-IDF vectorization** for feature extraction and **Logistic Regression** for classification.  

The goal of this project is to analyze Twitter data and predict the sentiment of tweets automatically, which can be useful for social media monitoring, brand analysis, and public opinion tracking.

---

## 🗂️ Project Structure

Use headings `##` for sections and list items with `-` or `*`.


---

## ⚡ Features

- **Data Cleaning:** Removes URLs, mentions, hashtags, punctuation, and extra spaces.  
- **Feature Extraction:** Converts text into numerical vectors using TF-IDF.  
- **Model:** Logistic Regression classifier with evaluation metrics.  
- **Evaluation:** Accuracy, classification report, confusion matrix, and visualizations.  
- **Prediction:** Predict sentiment for new tweets using a ready-to-use function.

---

## 📊 Model Performance

- **Accuracy:** 0.8655  

**Classification Report:**

| Class | Precision | Recall | F1-score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Negative)  | 0.86 | 0.92 | 0.89 | 266 |
| 1 (Irrelevant)| 0.91 | 0.73 | 0.81 | 171 |
| 2 (Positive)  | 0.86 | 0.90 | 0.88 | 277 |

**Weighted average:** Precision 0.87 | Recall 0.87 | F1-score 0.86  

---

## 📦 Installation

Use code blocks with triple backticks and language identifier (`bash`, `python`) for commands:

```bash
# Clone the repository
git clone https://github.com/yourusername/Twitter-Sentiment-Analysis.git
cd Twitter-Sentiment-Analysis

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook notebooks/sentiment_analysis.ipynb

