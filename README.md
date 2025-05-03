# IMDB Sentiment Analysis with Simple RNN (TensorFlow)

This project performs sentiment analysis on IMDB movie reviews using a Simple Recurrent Neural Network (RNN) built with TensorFlow and Keras. It classifies reviews as **Positive** or **Negative** based on the text content.

## 📌 Features

- Uses the IMDB dataset from `tensorflow.keras.datasets`
- A Simple RNN model trained for binary sentiment classification
- A Streamlit web app to input and classify your own movie reviews
- Custom preprocessing and text decoding
- Pre-trained model saved as `.h5` and loaded for predictions

## 🧠 Model Architecture

- Embedding Layer
- SimpleRNN Layer
- Dense Output Layer (Sigmoid activation for binary classification)
