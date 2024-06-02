# Sentiment Analysis using LSTM
This project focuses on analyzing customer sentiments expressed in tweets about Virgin America airline. The dataset, sourced from Kaggle, contains 14,640 entries and 15 variables, including tweet content, sentiment expressed, and various user and tweet attributes. We implement and compare two models: a basic LSTM and an improved bidirectional LSTM, to determine their effectiveness in sentiment analysis.


### LSTM Architectures
## LSTM Architecture
- Input: Sequences of tokens (word indices)
- Embedding Layer: Converts input tokens to dense vectors (embedding_dim)
- LSTM Layer: Processes input sequence, maintains hidden state capturing context (hidden_dim, num_layers, dropout)
- Fully Connected Layer: Produces final output
  
## Improved LSTM Architecture
- Bidirectional LSTM: Processes input in both forward and backward directions simultaneously
- Embedding Layer: Converts input tokens to dense vectors
- Bidirectional LSTM Layer: Same parameters as LSTM layer with bidirectional=True
- Fully Connected Layer: Produces final output
  
## Code

You can find the code for the entire project in the Sentiment_Analysis_LSTM.ipynb file.
## Detailed Report

A comprehensive report detailing the model architecture, training process, evaluation metrics, and performance graphs is available in `report.pdf`.

For questions or feedback, please [email](mailto:gayatriwalke@gmail.com).

