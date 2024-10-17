# Sentiment Analysis with Bidirectional LSTM 🌟
This project performs sentiment analysis on Twitter data using a Bidirectional LSTM model. The goal is to classify tweets into sentiments (positive, negative, neutral, irrelevant) 🐦💬.

### Overview 📊
The model uses a Bidirectional LSTM to capture context from both past and future word sequences in tweets. Key steps include:

Preprocessing: Lowercasing, removing links and stopwords, tokenization, and padding ✂️.
Model: Embedding -> Bidirectional LSTM -> Dropout -> GlobalMaxPooling1D -> Dense -> Softmax.

### Dataset 📚
The data consists of tweets with sentiment labels. We split it into training (80%) and validation (20%) 🔍.

### Usage ⚙️
Preprocess the tweets.
Train the model on the training data.
Evaluate performance on the validation set.

### Future Work 🚀
Try GRU or Transformer models.
Fine-tune hyperparameters for better accuracy or maybe increasing epochs can work too! :)
