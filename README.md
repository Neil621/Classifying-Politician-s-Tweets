# Objective
Classify Donald Trump, Jeremy Corbyn and Theresa May Tweets using Naïve-Bayes.

# Findings:
Using a very basic Naïve-Bayes word count model leads to a 60% accuracy in classifying tweets in test set. 

Both Donald Trump and Jeremy Corbyn tend to use the word "people" frequently.

"Trump uses "I" more frequently than others.

Both Theresa May and Trump use word "great" frequently.

# Classifying-Politician-s-Tweets
Classifying Tweets by Donald Trump, Theresa May and Corbyn Using Naive Bayes.

# Data
xlsx file of tweets classified by politician

# Methodology
Preprocess data by lowercasing words and removing stopwords.

Create count vector bag of words representation

Implement Naive-Bayes model using sklearn to categorise tweets by politican given word count

