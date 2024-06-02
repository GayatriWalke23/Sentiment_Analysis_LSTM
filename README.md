# Sentiment_Analysis_LSTM
This repository contains the implementation of Long Short-Term Memory (LSTM) networks for sentiment analysis. The project focuses on classifying movie reviews as positive or negative using the Twitter Airline Dataset.
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

