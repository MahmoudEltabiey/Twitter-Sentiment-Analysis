# Twitter Sentiment Analysis (NLP)

## Problem
Social media platforms like Twitter contain large amounts of user opinions and emotions.  
Manually analyzing this data is difficult and time-consuming.  

The goal of this project is to build a **machine learning model that automatically classifies tweets based on sentiment** (positive or negative) using Natural Language Processing (NLP).

---

## Approach
The project follows a standard NLP pipeline:

1. **Data Preprocessing**
   - Remove URLs, mentions, and special characters
   - Convert text to lowercase
   - Remove stopwords
   - Tokenization

2. **Feature Extraction**
   - Convert text into numerical features using **CountVectorizer**

3. **Model Training**
   - Train machine learning models to classify tweet sentiment.

---

## Models
The following machine learning models was used for sentiment classification:

- Multinomial Naive Bayes  

This model is commonly used in NLP classification tasks due to its efficiency and strong performance with text data.

---

## Results
The models were evaluated using accuracy and classification metrics.

 Accuracy |
|------|--------|

0.94

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Author
**Mahmoud Eltabiey**
