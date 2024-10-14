# YelpFastTextAnalysis
1) Description:
    This project implements word analysis using FastText on Yelp's dataset, identifying similar and dissimilar words based on trained and pretrained FastText models.

2) Key Features:
  Data Preprocessing: Cleaned text, removed special characters, tokenized, lemmatized, filtered out stopwords.
  FastText Model:
  Trained on 1,000 Yelp reviews.
  Vector size: 100, Window size: 5.
  Nearest and Farthest Word Analysis:
  Found 10 nearest and farthest words for 20 random words using cosine similarity.
  Pretrained Model Comparison: Used the "fasttext-wiki-news-subwords-300" model for similar/dissimilar word analysis.

3) Programming Tools:
   Python, Gensim, NLTK, FastText.
