# Sentiment Analysis of Financial News Headlines
### Using Bidirectional GRU with GloVe Embeddings

## 📌 Project Overview
This project focuses on binary sentiment classification (Positive / Negative) of financial news headlines using a deep learning model based on Bidirectional GRU with pre-trained GloVe word embeddings.

## 🧠 Model Architecture
- Embedding Layer (GloVe – 100d)
- Bidirectional GRU (64 units)
- Bidirectional GRU (32 units)
- Dense + Dropout
- Sigmoid Output Layer

## 📂 Dataset
- 25 financial news headlines per day
- Headlines combined into a single text sequence
- Labels: Positive / Negative

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- Pandas, NumPy
- Scikit-learn
- GloVe Embeddings

## 📊 Results
- Final Test Accuracy: ~48%
- Identified limitations due to frozen embeddings and small sequence length

## 🚀 Future Improvements
- Unfreeze GloVe embeddings
- Increase MAX_LEN
- Tune learning rate
- Experiment with LSTM / Transformers

## 📥 GloVe Download
Download GloVe embeddings from:
https://nlp.stanford.edu/projects/glove/

Use: `glove.6B.100d.txt`

