# Fake News Detector

A Python machine learning project that detects whether a news headline or article is real or fake using NLP techniques and Logistic Regression. It features a Streamlit web interface for real-time predictions.

## Features

- **Data Preprocessing:** Cleans text using NLTK (tokenization, stopword removal, lemmatization).
- **Feature Extraction:** Uses TF-IDF to convert text to numerical data.
- **Model Training:** Implements Logistic Regression for classification.
- **Web App:** Streamlit-based interface for easy use.

## Installation & Usage

1. **Clone the Repo:**
   ```bash
   https://github.com/srilatha-0/fake-news-detector
   cd fake-news-detector
Install Dependencies:

bash
Copy
Edit
pip install streamlit pandas nltk scikit-learn joblib
Run the App:

bash
Copy
Edit
streamlit run main.py

Project Structure
bash
Copy
Edit
fake-news-detector
├── name.py                   # Main Streamlit app
├── fake_news_model.pkl       # Saved model
├── tfidf_vectorizer.pkl      # Saved TF-IDF vectorizer
├── README.md                 # This file
Deploying Online
Deploy on Streamlit Cloud by connecting your GitHub repo and selecting the main file (e.g., name.py). This gives you a shareable public URL.

Dependencies
Python 3.x

Streamlit, Pandas, NLTK, Scikit-learn, Joblib

Author
Pamula Srilatha
[GitHub](https://github.com/srilatha-0) | [LinkedIn](https://www.linkedin.com/in/srilatha-p-47bb22357/)

pgsql
Copy
Edit

This version is more concise while still providing clear instructions and project details. Feel free to adjust it as needed!
