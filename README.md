# twitter_sentiment

> This repo was not inteded for market use, just as a proof of concept analysis using jupyter notebooks.

> The first part of the twitter_nlp.ipynb notebook consists preprocessing the dataset. Many implementations exists to using pretrained word embeddings but a model which was trained on a task specific dataset often outperforms a general purpose pretrained model. After training the model, we will predict the sentiment of the live stream of tweets by scrapping twitter using their API and the tweepy library. 

> Sentiment analysis is considered a lagging indicator. However, its possible to find the right parameters to optimize the algorithm and making gains from gathering any remaning alpha still in the data. Twitter is only a small subset of the population, increasing accuracy can be achieved by parsing websites such as Bloomberg, WSJ, stocktwits and others in a similar manner.

> This algorithm is slightly biased towards the upside, however this can be easily ammended by increasing the num_words hyperparameter in the vectorization fitting, using finance specific dataset and not just a general purpose one, another solution scaling by an appropriate factor the negative confidence calculated in the function confidence_func.

> Finally, while the last cell in twitter_nlp.ipynb updates sentiment in twitter_nlp.txt textfile, we can see the live results displaying in graphing_twitter_sentiment.ipynb
