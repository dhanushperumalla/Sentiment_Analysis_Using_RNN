# 🎬 IMDb Movie Review Sentiment Analysis

This project classifies IMDb movie reviews as positive or negative using a Recurrent Neural Network (RNN). Check out the live demo [here](https://sentimentanalysisusingrnn-8dohhnu33vece9pdwdw9zt.streamlit.app/).

## 📝 Project Overview
Sentiment analysis is the task of determining the sentiment or emotion expressed in a piece of text. In this project, we use an RNN to classify IMDb movie reviews into positive or negative sentiments.

## 📊 Dataset
The dataset consists of 50,000 IMDb movie reviews, split equally into 25,000 reviews for training and 25,000 reviews for testing.

## 🏗️ Model Architecture
- **Embedding Layer**: Converts input words into dense vectors.
- **LSTM Layer**: Captures long-term dependencies in the text.
- **Dense Layer**: Outputs the final classification.

## 📦 Requirements
- Python 
- TensorFlow==2.15.0
- Keras
- NumPy
- Pandas
- NLTK
- Scikit-learn
