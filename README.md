# Twitter Sentiment Analysis

This project performs sentiment analysis on tweets to classify them as **hate speech (1)** or **non-hate (0)** using a deep learning approach with TensorFlow and Keras.

## 📁 Dataset

The dataset used is from [Kaggle: Twitter Sentiment Analysis for Hate Speech Detection][(https://www.kaggle.com/datasets/arkhoshghalb/twitter-sentiment-analysis-hatred-speech?select=train.csv]) and includes:
- `tweet`: The text of the tweet
- `label`: Sentiment label (0 = non-hate, 1 = hate)

## 🚀 Project Workflow

1. **Data Preprocessing**
   - Cleaning tweets (removing links, special characters, etc.)
   - Tokenization and padding sequences

2. **Model Architecture**
   - Embedding layer
   - LSTM or GRU (depending on configuration)
   - Dense output with sigmoid activation

3. **Training & Evaluation**
   - Train/test split using NumPy
   - Loss and accuracy tracking
   - Optional learning rate visualization

4. **Prediction**
   - Inference on new tweets with same preprocessing

## 📊 Requirements

- Python 3.x
- TensorFlow
- NumPy
- pandas
- matplotlib
- seaborn

Install all dependencies:
```bash
pip install -r requirements.txt
