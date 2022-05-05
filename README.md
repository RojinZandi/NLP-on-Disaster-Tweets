# NLP-on-Disaster-Tweets
Twitter, with 330 million users from all over the world, is one of the most popular social media. Our dataset is a collection of tweets that contain words about disasters. 
Our goal is to distinguish whether there has been a disaster, or the tweet is metaphorically mentioning words related to a disaster, so this is a binary classification problem.


For preprocessing the twitter dataset, we have used NLTK library. We have removed the stop words,emojis, URLs, HTML tags, symbols, and then create a sequence of tokens that represent each tweet.

The code contains a baseline model (LSTM) and an RNN with Bidirectional layer and applying GloVe (Global Vector for Word Representation).

Finally, after comparing different implemented models, we have observed:

1.	In Natural Language Processing problems, the Preprocessing is one of the most important parts of solution.

2.	In feature extraction, Word Embedding helps the model to achieve higher accuracies.
	
2.	Generative methods, such as BI-LSTM, by allowing the model to have access to past and future state simultaneously, improve the model efficiency.
	
4.	GloVe is an unsupervised algorithm that finds words with similar meaning. This method outperforms other embedding techniques and saves time and computational power.
	
5.	In this problem and our model, early stopping regularization method is not suggested and does not improve the model. Notice that it changes in different models and problems.

We suggest applying TF-IDF preprocessing method and also fine tuning the model with BERT (Bidirectional Encoder Representations from Transformers) on this dataset. Also, the regularization methods can be improved, and they can help to obtain a better model. 

