For this project on "Sentiment Analysis Using Twitter Data" for Margdarshan 

First, we extracted Twitter data using keywords like "JEE Mains," "JEE Advanced," "JoSAA," and so on. 

These tweets were preprocessed by removing hyperlinks, URLs, special characters, emojis and then by using NLP techniques such as stopwords, and FuzzyWuzzy, similar tweets were removed. Also, words were reduced to their root form by stemming & lemmatization to improve search accuracy

By compiling a list of words for each classification category, such as "Postpone", "Counselling", "College", "Exam," etc., these preprocessed tweets were classified. N-grams were used to observe the most frequently occurring words in each category. The sentiment analysis was then applied to the classified tweets & was useful in determining the overall sentiment of each tweet.
