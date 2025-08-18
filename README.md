# Sentiment Analysis on Texts & Real-Time Tweets

This project performs Sentiment Analysis on both user input texts and real-time tweets from Twitter (X). It uses the VADER (Valence Aware Dictionary for Sentiment Reasoning) model to classify sentiments into Positive, Negative, and Neutral categories. Additionally, it fetches live tweets using the Twitter API (Tweepy) and visualizes sentiment distribution with a bar chart.

# Features

- Analyze any custom input text for sentiment polarity.

- Fetch the 10 most recent tweets based on a keyword or hashtag.

- Classify tweets into Positive, Negative, or Neutral sentiments.

- Visualize results in a bar chart for quick insights.

- Lightweight, fast, and easy to extend.

# Tech Stack


- Flask – Web framework

- VADER (NLTK-based) – Sentiment analysis engine

- Tweepy – Twitter API integration

- Matplotlib – Visualization

# Example Workflow

Enter a keyword (e.g., Python).

App fetches 10 latest tweets from Twitter using Tweepy.

Each tweet is analyzed using VADER SentimentIntensityAnalyzer.

Results are shown as:

- Positive

- Negative

- Neutral

A bar chart displays overall sentiment distribution.

# Use Cases

- Brand Monitoring: Track customer opinions about products or services in real time.

- Event Tracking: Understand public sentiment during live events, launches, or news.

- Market Research: Analyze audience perception about trends or competitors.

- Personal Insights: Check sentiment of your own written text before publishing.

- Social Media Analytics: Build dashboards for digital marketing teams.

# Future Enhancements

- Multilingual sentiment analysis support.

- Historical trend analysis of a keyword.

- Word clouds for common terms in tweets.

- Deployment on Heroku/AWS for live use.

- Responsive UI with modern chart libraries.

# Author

Pranav Swarnkar
Python Developer | Data Scientist | IoT Enthusiast

# Web Page

<img width="1920" height="948" alt="image" src="https://github.com/user-attachments/assets/31facd96-af9b-431d-9cdd-0ff13608a1a5" />
