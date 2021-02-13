# covid19-tweets-classification

---

**Summary** : 

This is a personal data science project launched to ty out :
- Keras text preprocessing oriented functionalities (tokenization, sequences padding, embeddings layer) 
- Pre-trained Glove embeddings integration

The goal of this project is to create a three-way polarity (positive, negative, neutral) classification system for tweets. We'll use the external dataset of Coronavirus tweets, pre-trained word embeddings vectors GLOVE and Keras Sequential model to create an engine capable of classifying each tweet as positive, negative or neutral. 

**Repo structure**

This repo includes the following files:

- The Jupyter notebook used for this project (notebook.ipynb);
- 'Models' directory containing trained models

**Used data**

1. External dataset of Coronavirus tweets, publicly available on Kaggle : 
    https://www.kaggle.com/datatattle/covid-19-nlp-text-classification  

The dataset includes two files :   
    - Corona_NLP_train.csv : This file contains ~41000 raw tweets, along with their polarity labels and some tweets characteristics such as location, time, user id. We'll use this file to train our classifier.  
    - Corona_NLP_test.csv : In the same format as the training csv, the file contains a smaller set of tweets, ~4000. We'll use it to test the predictions of our classifier.   

2. GLOVE pre-trained embeddings vectors, publicly available here : http://nlp.stanford.edu/data/glove.twitter.27B.zip  

We use vectors with 25 dimensions trained on Twitter data. 
