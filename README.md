# SMS-Spam-Filter
In this project I will build a SMS Spam filter using Naive Bayes algorithm. The data set has been adapted from the SMS Spam collection: http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/.
I will be using the tm package in r to do the analysis.

The raw data will be transformed into  a representation known as **bag-of-words**: this representation ignores word order and simply provides a variable indicating whether the word appears at all. Such representation is particularly useful for spam filter where we are using the frequency of occurrence of particular words to predict whether a message is spam or ham. 

The following basic NLP steps would be followed:

* create Corpus
* standardize text
* Tokenize text
* Create Document Term Matrix
* Visualize Data
* Prediction!
