# sentiment_analysis
Sentiment Analysis using Deep Learning

Used Sentiment140 1.6M tweets dataset to predict the sentiment

Performed text preprocessing by removing links, @'s and special chars and converting to lower text\

Used GloVe for Bidirectional-LSTM model and BERT embeddings for BERT model

Used warm=up and decay learning rate schedule and Adam's optimizer for effective update of weights

Compared the performace using MCC metric BERT : 0.68, LSTM : 0.52

Dataset link : https://www.kaggle.com/datasets/kazanova/sentiment140/code
