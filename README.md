# Simple FakeNews Classifer
Sebuah model machine learning yang dapat membedakan apakah sebuah berita itu palsu atau tidak menggunakan teknik NLP

## Description
Dampak yang ditimbulkan adanya berita hoax akan sangat luar biasa antara lain, berupa dampak sosial,ekonomi, politik, keamanan dan yang lebih besar adalah bisa mengancam keutuhan negara. Penyebaran berita hoax sering terjadi di media sosial dan mempengaruhi pola pikir masyarakat.

*Fake news is a modern problem which requires modern solutions.*

## Dataset
Sumber dataset : https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

## Table of content
- Import library
- Load & EDA
  - Inspect shape
  - Inspect kolom
  - Inspect data kategorical
  - Check nilai null
  - Wordclouds
  - Counter NE
- Preprocessing
  - Lower - case
  - Expand - Contractions
  - Hapus punctuations (kata hubung)
  - Hapus URL's
  - Hapus *stopwords*
  - Hapus feature redundant
- Modelling
  - Split data
  - Vectorization & Fitting
    - CountVectorizer
    - TfidfVectorizer
- Evaluasi
  - Accuracy score
  - Confusion matrix
  - Classification report

## Dependencies
- Python 3.9.7
- Pandas
- Matplotlib
- Wordcloud
- Collections
- Spacy
- Seaborn
- NLTK
- Regex
- Scikit - learn
 
