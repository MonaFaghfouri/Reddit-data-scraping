# 🔍 Reddit Data Scraping with PRAW (Python Reddit API Wrapper)
This repository provides a simple and effective notebook for scraping Reddit data using the Reddit API and PRAW (Python Reddit API Wrapper). You can extract data from any subreddit using your own API credentials and analyze it in Google Colab.
# 📁 Repository Structure
| File           | Description                                     |
| -------------- | ----------------------------------------------- |
| `Reddit.ipynb` | Jupyter Notebook for scraping posts from Reddit |
| `README.md`    | Project instructions and setup guide            |
# 🚀 Getting Started
🔑 1. Create Reddit API Credentials
Visit https://www.reddit.com/prefs/apps

Click “Create App” and select “script”

Set:

name: any project name

redirect uri: http://localhost:8080

Save the Client ID and Client Secret

🔧 2. Set Your Credentials in Code
In Reddit.ipynb, define your credentials like this:

REDDIT_CLIENT_ID = "your_client_id"

REDDIT_CLIENT_SECRET = "your_client_secret"

REDDIT_USER_AGENT = "your_app_name"

# 📦 Requirements
Python 3.8+

praw, pandas

Works best in Google Colab

# ✅ Features
Scrape posts from any subreddit

Filter by keyword, date, or score

Export results to Excel/CSV for analysis

# 📌 Notes
Reddit’s API has rate limits. Avoid excessive requests.

Make sure your Reddit account has developer access.

# 👤 Author
Mona Faghfouri Azar
Data Analyst | NLP Researcher
GitHub: @MonaFaghfouri
