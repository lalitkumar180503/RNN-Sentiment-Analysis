# RNN-Sentiment-Analysis
RNN-based Sentiment Analysis using PyTorch and TF-IDF for binary text classification.
# RNN Sentiment Analysis using PyTorch

## Project Overview

This project performs sentiment analysis on movie reviews using a Recurrent Neural Network (RNN) implemented in PyTorch. The model predicts whether a review is Positive or Negative.

## Features

- Text Preprocessing
  - Remove URLs
  - Remove Stopwords
  - Stemming
- TF-IDF Feature Extraction
- RNN Model using PyTorch
- Binary Sentiment Classification
- Model Evaluation

## Technologies Used

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- NLTK

## Dataset

IMDB Movie Review Dataset

## Model Architecture

- RNN
- Hidden Size: 128
- Number of Layers: 1
- Output Layer: 1 Neuron (Binary Classification)

## Accuracy

Model Accuracy: **85.76%**

## Installation

```bash
pip install -r requirements.txt
```

## Run the Project

Open the notebook:

```
RNN_Sentiment_Analysis.ipynb
```

Run all cells in order.

## Future Improvements

- Replace RNN with LSTM or GRU
- Use Word Embeddings
- Deploy using Streamlit
- Improve accuracy with pretrained embeddings