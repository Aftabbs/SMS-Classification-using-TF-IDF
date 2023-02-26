# SMS Message Classification using TF-IDF and Multinomial Naive Bayes
In this project, we will be building a machine learning model to classify SMS messages as spam or not spam (also known as ham).
We will be using the TF-IDF technique to extract features from the messages and a Multinomial Naive Bayes classifier to train our model.

## TF-IDF Technique
TF-IDF stands for Term Frequency-Inverse Document Frequency. It is a technique used in natural language processing to quantify the relevance of a term in a document or corpus. The TF-IDF score represents how important a word is to a document in a corpus. It is calculated as follows:

## Term Frequency (TF): The frequency of a term in a document.
Inverse Document Frequency (IDF): The log of the ratio of the total number of documents to the number of documents containing the term.
TF-IDF is a commonly used technique in text classification tasks as it helps in identifying the most important words in a document or corpus.

## Multinomial Naive Bayes
Multinomial Naive Bayes is a probabilistic algorithm used for text classification. It is based on the Bayes theorem and assumes that the features (in our case, the TF-IDF scores) are independent of each other. The algorithm calculates the probability of each class (spam or ham) given the feature values and selects the class with the highest probability as the output.

## Dataset
The dataset used in this project is Sms.tsv.this Data consists 5572 rows and 2 columns, It contains a collection of SMS messages labeled as spam or ham. The dataset is split into a training set and a testing set.

## Advantages of TF-IDF and Naive Bayes
The TF-IDF technique is advantageous because it helps in identifying the most important words in a document or corpus. This can be helpful in text classification tasks as it allows us to focus on the words that are most relevant to the classification task.

The Multinomial Naive Bayes algorithm is advantageous because it is simple, fast, and effective. It can be trained on a relatively small amount of data and still produce accurate results. Additionally, it is resistant to overfitting, which can be a problem with more complex algorithms.

## Use Cases in Industries
The TF-IDF technique and Naive Bayes algorithm can be used in a variety of industries for text classification tasks. For example:

In the financial industry, they can be used to classify news articles as positive or negative for trading decisions.
In the healthcare industry, they can be used to classify patient records as normal or abnormal for diagnosis.
In the e-commerce industry, they can be used to classify customer reviews as positive or negative for product improvement.

## Conclusion
In this project, we have learned about the TF-IDF technique and the Multinomial Naive Bayes algorithm for text classification. We have also seen how they can be applied in various industries for different text classification tasks.




