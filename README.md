# Sentiment-Analysis-of-Tweets
Performing Sentiment Analysis on a database of tweets using various vectorizers and methods

The .ipynb file has been created using jupyter notebook and the first block of code needs to be adjusted for the path where the user has stored the database file

Count Vectorizer- It assigns every word with an index and maps it ti the word count
TD-IDF Vectorizer- It works on IDF(Inverse Document Frequency) values. This is because if a word occurs more number of times, it is of less significance. For example, the words 'the','is','an',etc are used frequently but provide nothing of importance about the subject of a document
Hashing Vectorizer- It works similar to Count vectorizer but it does not store the vocabulary set and so saves memory space and is especially useful for large datasets
