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

## 🚀 How to Run

1. Clone the repository:
 ```
 git clone https://github.com/Saza-dev/Sentimental-Analysis-RNN-Streamlit.git
 ```
2. Navigate to the project folder:
  ```
    cd imdb-rnn-sentiment-analysis
  ```
3. Install the dependencies:
 ```
 streamlit run main.py
 ```
4. Make sure the trained model file simple_rnn_imdb.h5 is in the same directory.

5. Run the Streamlit app:
 ```
 streamlit run main.py
 ```
6. Enter a movie review in the app and click Classify to see the sentiment and confidence score.
