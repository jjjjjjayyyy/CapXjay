# CapXjay

# Instructions to Run the Code:

Stock Movement Analysis Based on Social Media Sentiment

This project predicts stock movements based on sentiment analysis from social media data (Twitter). The following steps describe how to set up and execute the project.

---

Requirements
1. Python 3.8 or higher
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

# Steps to Run:

Scrape Data:

python scripts/scrape_twitter.py
This script will scrape tweets and save them to data/twitter_stock_data.csv.

Preprocess Data:

python scripts/preprocess_data.py
This will clean the data and save processed results to data/processed_stock_data.csv.

Train Model:


python scripts/train_model.py
The model will be trained, and evaluation metrics will be displayed in the terminal.

# Dependencies
The following libraries are used:

Tweepy
Pandas
Scikit-learn
NLTK
Matplotlib
