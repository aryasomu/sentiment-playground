# Sentiment Analyzer Web App

This is a simple Flask-based web application that performs **sentiment analysis** on a user's input sentence and returns a basic interpretation of their current emotion (Happy, Sad, Neutral). It uses the `TextBlob` Python library for natural language processing and sentiment scoring.

---

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/sentiment-analyzer.git
cd sentiment-analyzer
```

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate    # On Windows use: venv\Scripts\activate
```

### 3. Install dependencies 

```bash
pip install flask textblob nltk
```

## Running the App
Run 
```bash
python app.py
```
The project will be available at
```bash
http://127.0.0.1:5000
```

## Example Usage
Input:
```bash
I'm feeling a bit down today but hopeful things will improve.
```
Output:
```bash
Emotion: Sad 🙁
```
