# IMDB Sentiment Classifier using RNNs and GloVe

This project implements a sentiment classification model for IMDB movie reviews.  
We experiment with multiple architectures:
- Vanilla RNN + GloVe embeddings
- LSTM + GloVe embeddings
- Vanilla RNN + on-the-fly embeddings
- LSTM + on-the-fly embeddings

The goal is to compare pre-trained embeddings vs. learned embeddings, and simple RNNs vs. LSTMs.

---

## 📂 Project Structure

Below is the structure of this project (screenshot attached for clarity):

[alt text](image.png)

---

## 📊 Dataset

We use the **IMDB Movie Reviews Dataset (50,000 samples)**.  
Source: [Kaggle - IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data)

---

## 🔤 Pre-trained Embeddings

We use **GloVe (6B, 100d)** embeddings, downloadable from:  
[Stanford GloVe Project](https://nlp.stanford.edu/projects/glove/)

Place the downloaded file in a `glove/` folder.

---
