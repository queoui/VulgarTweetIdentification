# VulgarTweetIdentification

Team members: Duc Phan, Vishrut Sharma, Kavitha Jajula, Mahathi Mandelli, Nicholas Muller

Topic: Expressively vulgar
Programming Language: Python
Reference paper: https://aclanthology.org/C18-1248.pdf
Dataset: https://github.com/ericholgate/vulgartwitter

Description

The project aims to develop and train a model which can identify vulgar tweets from the provided dataset. The dataset consists of a large number of tweets from various users, and the number of vulgar words in each tweet is counted and grouped into the following categories: Very negative, Negative, Neutral, Positive, and Strongly Positive. The category with the highest number of words is taken as Majority. We will be training the model using 2 methods, the Multinomial Naive-Bayes Algorithm, and LSTM. We will then compare the results of these 2 methods.

For the Multinomial Naive-Bayes method we will be vectorizing the data of each tweet from text to numbers similar to the word2vec example, and then implement the Naive-Bayes algorithm to classify whether a tweet is vulgar or not. We aim to classify the tweets in the test set with good precision.

For the LSTM model, we will be taking the data. First, we check for any missing values in the test and train data. Then normalize the text data followed by Lemmatization which is the process of grouping together the different inflected forms of words so they can be analyzed as a single term. And then we remove the Stopwords Removal in the dataset. Post that we can proceed with Tokenization followed by padding. We aim to classify the tweets with good accuracy and precision.




//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


Data Pre-processing:
Include methods used to clean the data
The ratio of positive: negative tweets (for 100 samples, 97:3 respectively would be a reasonable classification)
The number of samples in both test and train sets.
Percentage of negative and positive tweets in both training and test sets.

Naive-Bayes Model:
Theory
Formula
Code snippets

LSTM:
Theory
Formula
Code snippets

Results:
Accuracy
Precision
Recall
Confusion matrix

Conclusion:
Comparison
Future scope
