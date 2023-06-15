# Amazon-Customer-Review-Sentiment-Analysis

The dataset can be downloaded from : https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

Sentiment analysis is the process of analyzing digital text to determine if the emotional tone of the message is positive, negative, or neutral. It is an important business intelligence tool that helps companies across the world improve their products and services. 

In this project, using machine learning and text analytics, algorithms can categorize sentences into positive, negative, and neutral categories. Many companies, including Amazon and Twitter, use this sentiment analysis to analyze customer reviews on their products, and they will improve based on these results. An NLP Python package is called NLTK, or Natural Language Toolkit. With NLTK, a range of activities can be carried out, including tokenizing, stemming, parts of speech tagging, etc. NLTK helps the computer with text analysis, preprocessing, and comprehension. NLTK works on the principle of tokenization where the sentence to be analysed is converted to tokens. The stop words ( textual noise ) are then removed and submitted for further processing 

# Vader Sentiment Analysis

Text sentiment analysis is carried out using the VADER (Valence Aware Dictionary for Sentiment Reasoning) model, which is sensitive to both the polarity (positive/negative) and intensity (strength) of emotion. In addition to reporting on positivity and negativity scores, VADER also provides information about the sentiment of a statement. The Compound score in Vader is a measurement that adds together all lexical ratings that have been scaled between -1 (the most extreme negative) and +1. (most extreme positive).

# RoBERTa Model

RoBERTa is a transformers model that was self-supervised and pre-trained on a huge corpus of English data. This indicates that it was just pre-trained on the raw texts, without any human labeling, with an automatic procedure that uses the texts to produce inputs and labels. Roberta analyses a string and produces a dictionary of scores in three categories: Negative, Neutral, and Positive.

Execution : 
1. Launch the Jupyter Notebook either in your kernel or App.
2. In the Notebook Dashboard navigate to find the notebook. Open it in your browser.
3. Open the Jupyter Notebook file named: 'customer_review_sentiment_analysis.ipynb'.
4. You can run the notebook step by step by pressing shift+enter.

All the required libraries for Python 3 version can be installed by running the following command on Conda shell : 

pip3 install (library) , eg : pip3 install nltk
