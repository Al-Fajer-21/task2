Sentimental analysis is performed on a dataset having 1600000 tweets from twitter.
This dataset contains 6 columns which are renamed as polarity, id, date, query, user, tweet.
For sentimental analysis, two columns polarity and tweet are mainly concerned.
Text cleaning is performed on tweet column and all the following things are removed to avoid any negative impact during analysis: HTML tags, URLs, emojis and stopwords.
Also all the words are converted to lowercase.
Moreover, stemming and tokenization is applied to all tweets.
After splitting dataset into train and test datasets, TF-IDF is used to convert text data into numerical data.
Multinimial Naive Bayes classifier is trained for model building.
Model's performance is evaluated using metrices like accuracy, precision, recall and F1-score. 
