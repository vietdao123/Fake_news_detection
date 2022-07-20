# Fake_news_detection
In this code, I solved the fake news detection problem using four machine learning classification algorithms: Linear regression, Decision Tree classification, gradient increasing classifier and random forest classification model.

Project for the purpose of detecting fake news, using sklearn we will build a TfidfVectorizer on our dataset. Then, initialize a passive classifier (PassiveAggressive) to fit the training model. Finally, to test the effectiveness of the model, we will use the accuracy score and confusion matrix to evaluate.

To continue this project, we need to learn about the term Tfidfvectorizer
TF: Term Frequency is the number of times the word appears in the text. Because texts can be of different short lengths, some words may appear more times in a long text than in a short text. A phrase with a higher TF value than others means that it appears more often than others.

IDF: Inverse Document Frequency calculates the importance of a word. When calculating TF, every word is equally important, but there are some words in English like "is", "of", "that",... appear quite a lot but are of little importance. Therefore, we need a method to offset words that appear many times and increase the importance of words that appear less often but have special meaning for some text.

TfidfVectorizer converts a set of raw documents into a matrix of TF-IDF features.
