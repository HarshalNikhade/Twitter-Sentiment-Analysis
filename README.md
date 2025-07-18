# 🧠 Twitter Sentiment Analysis Using NLP & Tweepy (May 2025)

This project uses the **Twitter API** and **Natural Language Processing (NLP)** techniques to perform sentiment analysis on retweeted tweets. Built with Python and Tweepy, the notebook fetches real-time tweets (or uses pre-collected data) and analyzes their sentiment using tools like **TextBlob**, **WordCloud**, and **NLTK**.

---

## 📌 Objective

The goal of this project is to:

* Collect tweets using the Twitter API
* Preprocess tweet text for analysis
* Perform sentiment analysis (Positive, Neutral, Negative)
* Visualize word clouds and sentiment distribution
* Identify trends in user engagement via retweets

---

## 📁 Dataset Source

Tweets are either:

* Collected using **Tweepy** with Twitter API credentials
* Or loaded from a pre-saved dataset (`.csv`) for analysis
  Each tweet includes metadata such as:
* Timestamp
* Content
* Location
* Likes & Retweet counts

---

## 🛠️ Libraries Used

* `tweepy` – Twitter API access
* `pandas`, `numpy` – Data manipulation
* `nltk`, `textblob` – NLP and sentiment classification
* `re`, `emoji` – Text preprocessing
* `wordcloud`, `matplotlib`, `seaborn` – Visualization
* `PIL` – Image masking for custom word clouds

---

## 🧪 Sentiment Analysis Approach

1. **Authentication:** Connect to the Twitter API using OAuth.
2. **Text Preprocessing:**

   * Remove mentions, links, emojis
   * Tokenization, lemmatization, stopword removal
3. **Sentiment Detection:**

   * Using `TextBlob` polarity scoring:

     * `> 0` → Positive
     * `= 0` → Neutral
     * `< 0` → Negative
4. **Visualization:**

   * Sentiment distribution using Seaborn
   * Word cloud generation by sentiment class

---

## 📊 Sample Insights

* Tweets related to **AI**, **Data Science**, and **Crypto** received high retweet volumes.
* Locations like **Brasil**, **Kerala**, and **Fresno** had active engagement.
* Sentiment breakdown showed majority of tweets were **neutral**, followed by **positive**.

---

## 📂 File Structure

```
TwitterSentimentAnalysis/
│
├── TwitterSentimentAnalysis.ipynb   # Main Jupyter Notebook
├── data/
│   └── twitter_retweets_may2025.csv
├── images/
│   └── sentiment_wordclouds.png
├── README.md
└── LICENSE
```

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/TwitterSentimentAnalysis.git
   ```

2. Open the notebook:

   ```bash
   jupyter notebook TwitterSentimentAnalysis.ipynb
   ```

3. Add your Twitter API credentials and run the notebook to fetch or analyze tweets.

---

## 🔮 Future Enhancements

* Add real-time dashboard (Power BI / Streamlit)
* Use VADER for better handling of social media tone
* Automate daily tweet sentiment logs

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

* Twitter Developer Platform
* Libraries: TextBlob, Tweepy, NLTK, Matplotlib, WordCloud


