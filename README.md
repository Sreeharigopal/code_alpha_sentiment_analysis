

# IMDb Movie Review Sentiment Analysis

This project performs Sentiment Analysis on the IMDb movie reviews dataset, classifying text reviews into positive, negative, or neutral, and detecting specific emotions using NLP techniques and lexicon-based models.

---

##  Dataset Description

The dataset used is the IMDb Movie Reviews Dataset, a widely-used benchmark in sentiment classification. It consists of:

- 50,000 reviews:  
  - 25,000 labeled as positive  
  - 25,000 labeled as negative

Each review is a free-text user comment collected from the Internet Movie Database (IMDb). The dataset is balanced and does not contain neutral labels originally.

---

## Project Objectives

TASK 1: Classify text data into positive, negative, or neutral  
TASK 2: Use NLP lexicons to detect emotions (e.g., happy, angry, sad)  
TASK 3: Apply sentiment analysis techniques to IMDb reviews  
TASK 4: Understand public opinion through patterns  
TASK 5: Generate insights to support marketing, product development, or content strategy

---

## Tech Stack & Libraries

- Python
- Pandas, NumPy
- NLTK (VADER Sentiment)
- Text2Emotion / NRCLex (for Emotion Detection)
- scikit-learn (optional: ML model)
- Seaborn & Matplotlib (visualizations)

---

## How It Works

### 1. Load & Clean Data
- Remove HTML tags and special characters
- Convert reviews to lowercase

### 2. Sentiment Analysis
- Use VADER to get sentiment polarity scores
- Classify reviews into positive, negative, or neutral

### 3. Emotion Detection
- Use text2emotion or NRCLex to identify emotions like:
  - Happy
  - Sad
  - Angry
  - Fear
  - Surprise

### 4. Visualize Patterns
- Sentiment distribution plots
- Emotion distribution bar charts

---

##  Insights & Applications

- MarketingTarget audiences by sentiment/emotion
- Product Improvement: Understand negative feedback trends
- Public Opinion: Detect how audiences react to movie themes or storylines
- Recommendation Systems: Match movies with user emotions

---

## How to Run

1. Clone this repository
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook 
    
    ---

---

## Optional Enhancements

- Add a machine learning model (Logistic Regression, Naive Bayes)
-  Build a Streamlit dashboard
-  Perform time-based sentiment tracking
-  Extend to Amazon / Twitter / News data

---

## Files Included

- IMDB Dataset.csv – the dataset
- sentiment_analysis.py – main analysis script
- README.md– this file
- emotion_results.csv–  optional output
- notebook.ipynb– optional Jupyter notebook version

---

## Author

SREEHARI GOPAL  
Data Science | NLP | Python  
Email: therealsreeharigopal@gmail.com  
LinkedIn: 

---

## License

This project is for educational and research purposes only. Dataset © IMDb.










