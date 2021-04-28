# HAM_or_SPAM
Deciding comments are HAM or SPAM

## FINAL ACCURACY --> % 97.98

## CONTENTS :
- Data preparation
- Word cloud 

![2021-04-28_20-51-38](https://user-images.githubusercontent.com/73308365/116450939-93838c80-a864-11eb-92b3-c2b38d89defe.png)
- Indicates how many times 1 word is
- Tokenization
- Predict the star rating

## REQUIRED MODULES : 
- from wordcloud import WordCloud
- import pandas as pd
- import numpy as np
- import scipy as sp
- from sklearn.model_selection import train_test_split
- from sklearn.feature_extraction.text import CountVectorizer, TfidfVectorizer 
- from sklearn.naive_bayes import MultinomialNB 
- from sklearn.linear_model import LogisticRegression
- from sklearn import metrics
- from textblob import TextBlob, Word
- from nltk.stem.snowball import SnowballStemmer
- import matplotlib.pyplot as plt
    - %matplotlib inline
- import seaborn as sns
- from wordcloud import WordCloud
- import nltk
