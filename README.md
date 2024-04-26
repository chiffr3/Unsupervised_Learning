# Unsupervised_Learning

For this assignment, we are asked to locate a dataset for Exploratory Data Analysis and Unsupervised Learning, as part of the CU Boulder course, Unsupervised Algorithms in Machine Learning. We selected the Recipe Reviews and User Feedback dataset consisting of over 18,000 rows to conduct sentiment analysis of the website reviews. Since we also have rating scores, we will attempt Unsupervised and Supervised Learning methods on this data. The high star ratings will be flagged as a reviewer who "is a fan" of the recipe -- whereas, low star ratings will be considered "not a fan" of the recipe. This information can be useful for a company evaluating user reviews and providing a response based on the positive or negative assessment.

In order to check the accuracy of the models below, the data will be split into a train and test set where we can check the accuracy on a separate, test set of data. This segmentation will enable us to compare results across the models, as well as identify possible overfitting.

For our Unsupervised Learning methods, we will utilize:

- Clustering

- Non-negative Matrix Factorization (NMF)

For our Supervised Learning methods, we will utilize:

- Multinomial Naive Bayes

- Logistic Regression

To vectorize the text, we will utilize Gensim's Word2Vec and scikit-learn's CountVectorizer plus TfidfVectorizer. Additionally, we will use RandomizedSearchCV to help with our parameter tuning and, hopefully, improve our models.
