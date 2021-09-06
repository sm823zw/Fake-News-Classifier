# Fake-News-Classifier

In this repo, four Fake News Classifier models have been trained. LSTMs and Bi-LSTMs were used for building the model and 100-D GloVe embeddings were used for embedding the words. The first model was trained using the training and test data consisting of just the title of the news article. In the second one, the model was trained using the actual content of news article. The third and fourth one uses Bi-LSTM models. Tensorflow, nltk, re libraries were used. The dataset was downloaded from [Kaggle](https://www.kaggle.com/c/fake-news/).

Confusion Matrix for the best performing Bi-LSTM model -

![image](https://user-images.githubusercontent.com/49569284/132258303-acb776a2-dba4-4d86-b794-2b96256799b6.png)

