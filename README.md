Statement - Predict the sentimens of tweets

Dataset link = https://www.kaggle.com/datasets/kazanova/sentiment140

Dataset Fields: 

target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)

ids: The id of the tweet ( 2087)

date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)

flag: The query (lyx). If there is no query, then this value is NO_QUERY.

user: the user that tweeted (robotickilldozr)

text: the text of the tweet (Lyx is cool)


Libraries/Tools: Jupyter Notebook/Collab, Pyspark, MlLib, and other libraries
first preprocess the dataset perform EDA the create a machine learning pipeline: tokenizer, hashtf, idf, label_stringIdx
and applied Logistic Regression on dataset which classified the sentiments accurately with accuracy of 85% with ROC curve.
