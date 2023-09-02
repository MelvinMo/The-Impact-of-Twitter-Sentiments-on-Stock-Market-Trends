# The-Impact-of-Twitter-Sentiments-on-Stock-Market-Trends
This is a research paper named "The Impact of Twitter Sentiments on Stock Market Trends," which investigates the relationship between Twitter sentiments and stock market trends. The study was conducted by a team of five members led by me under the supervision of Prof. Dr. Mohammad Hossein Manshaei in the Department of Electrical and Computer Engineering at the Isfahan University of Technology.

The primary objective of the research was to understand the influence of Twitter sentiment on the trends of the top stock symbols in the S&P 500 index. We used the Twitter data over a three-month period, focusing on the volume, sentiment, and mentions of the top five S&P 500 stock symbols: Apple, Facebook, Tesla, Amazon, and Microsoft.

We utilized various machine learning and natural language processing techniques to perform this analysis. We implemented three algorithms: long-short-term memory (LSTM), Bernoulli-naive Bayes, and random forest.

The LSTM model, a type of recurrent neural network, was used due to its ability to learn from the temporal dynamics of sequences, which is vital when dealing with time-sensitive data like tweets and stock prices.

The Bernoulli Naive Bayes classifier, a probabilistic learning method, was chosen for its simplicity and efficiency, especially considering high-dimensional data.

Lastly, the Random Forest algorithm, an ensemble learning method that operates by constructing a multitude of decision trees, was employed due to its robustness against overfitting and its ability to handle a large feature space.

We also discussed Twitter data collection methods that were available for us to collect data, including the Twitter API, Tweepy, Twint, and preprocessed datasets. These tools provided real-time access to users' tweets, which were later used for sentiment analysis.

The methodology also involved data preprocessing, where the raw data was cleaned and transformed into a suitable format for further analysis. The data was then labeled for the supervised learning algorithms.

We calculated the bullishness variable by determining the ratio of positive tweets to negative tweets each day. This variable was then scaled by the corresponding stock return value on the following day, representing our financial data. Next, we assessed the potential influence of the tweets on the markets by analyzing the synchronous diagram of the bullishness and return variables. The findings of the research indicate a significant correlation between stock prices and Twitter sentiment.

So, our focus was to concisely illustrate an interdisciplinary approach combining computer science (machine learning, data mining, and natural language processing) and finance to predict stock market trends using sentiment analysis on Twitter data, which was successful in the end.

The codes and the pdf version of the research are both available in this repository.
