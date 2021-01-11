# Sentiment-Analysis-of-Amazon-Alexa-Reviews

# Introduction
Background: The public relations department team has collected extensive data on their customers such as product reviews. Based on the reviews ( in text format), the team would like to predict whether their customers are satisfied with the product or not. 

Data: The dataset consists 3150 Amazon customers reviews for Alexa Echo, Firestick, Echo Dot etc.

# Methodology
Since this is a binary classification problem, I applied two classic NLP models, Naive Bayes classification and logistic classification. The primary metric would be the accuracy.

# EDA

The dataset includes 3150 rows and 5 columns, while the last column is the response variable. (Note: 1 indicates positive feedback)
![dataset](https://user-images.githubusercontent.com/64850893/104144804-c592e080-5392-11eb-8a1d-dcbf910bfe79.jpg)

As for the distribution of the feedbacks, most of them are positive feedbacks.
![feedback](https://user-images.githubusercontent.com/64850893/104144920-30dcb280-5393-11eb-9e34-ffa24da380e4.jpg)

Another straightforward way to check the overall sentiment is the WordCloud.
![cloud](https://user-images.githubusercontent.com/64850893/104144939-3d610b00-5393-11eb-813f-ee133a9552ce.jpg)



# Date Cleansing

1. Remove the punctuation   
2. Remove the stopwords
3  Perform count vectorization (tokenization) 

The clean dataset is a the following dataset with the shape of 3150 * 5228.

![clean](https://user-images.githubusercontent.com/64850893/104145301-6930c080-5394-11eb-856f-965ce9caa6a0.jpg)


# Model1 Naive Bayes Classifier



# Model2 Logistic Classifier



# Conclusion

# Future
