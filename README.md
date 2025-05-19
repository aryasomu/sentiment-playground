# Sentiment Analyzer Web App

This is a simple Flask-based web application that performs **sentiment analysis** on a user's input sentence and returns a basic interpretation of their current emotion (e.g., Happy, Sad, Neutral). It uses the `TextBlob` Python library for natural language processing and sentiment scoring.

---

## 🛠️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/sentiment-analyzer.git
cd sentiment-analyzer

python -m venv venv
source venv/bin/activate    # On Windows use: venv\Scripts\activate

pip install flask textblob nltk

python app.py

http://127.0.0.1:5000
