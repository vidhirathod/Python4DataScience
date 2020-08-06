# Sentiment Analysis & Recommender system 
## For Amazon’s Utility Product line

### 1.0 Project Scope:
The main aim of this project is to assist in building Machine learning model to classify a review as “good” or “bad” based on the words used. Further, recommendation engine will help to make data based factual suggestions to customers on the e-commerce page, in order to make their buying experience easy and seamless. This project has been built keeping in mind the growing e-commerce industry market.

### 1.1 Project Deliverables
o A python notebook with Review classification (Natural Language Processing)
o A python notebook with Recommendation Engine code (K Nearest Neighbor)
o A project report detailing the project methodologies, tools and data analysis, visualizations.

### 1.2 Project Objective:
Predicting customer sentiment polarity using data science techniques and Designing a Recommender system for Amazon's home and kitchen dataset.

### 1.3 Results Summary:


The Sentiment Analysis shows that Logistic classifier could classify the sentiments with best Accuracy post using SMOTE technique to balance the imbalance labels. Also Precision is highest as compared to all other models.
The Recommender system based on Collaborative filtering using KNN Algorithm on the sentiments helps recommend products to customers based on prior sentiments. Nearest neighbor algorithm is used to predict 3 similar items to a customer who has purchased an item. Training set comprising of 1255 items is used to build the model and items from testing bucket are searched within the training neighbors to find the 3 best Recommendations.

### 1.4 Summary & Overview

#### Sentiment Analysis:
Plan is to implement sentiment analysis using Python using:
• Dummy Classifier using TF-IDF vectorizer(baseline algorithm)
• Logistic regression with TFIDF vectorizer
• Logistic regression with TFIDF vectorizer and n-grams
• SVM classifier with TFIDF vectorizer and n-grams
• Naive Bayes with TFIDF vectorizer and n-grams 1.4.3 Metrics:
• Accuracy
• F1score
• Precision
• Recall
• Specificity
Note: As there is no response variable, I plan to use overall column to segregate and tag the sentiment as good /positive when rating is >=4 and as bad/ Negative when rating is <=2. I excluded ratings with overall rating value =3 as it shows neutrality.

#### Recommender System:
Collaborative Filtering Recommender System (K - nearest neighbors’ algorithm)
Build an item-based collaborative filtering system based on K - nearest neighbors to find the most similar products. Here, Amazon Home and Kitchen Product line is used.
Also, build K neighbors classifier model to predict overall review rating based on text reviews
Build Wordcloud for each rating(1-5) for visualization.

### 1.5 About the Data:
Online shopping is all over the internet. All our needs are just a click away. Amazon is known not only for its variety of products but also for its strong recommendation system. Here, I have tried to used Amazon Dataset from http://snap.stanford.edu/data/web-Amazon.html Or http://jmcauley.ucsd.edu/data/amazon/
Amazon product data [Home and Kitchen dataset] 1.5.1 Data Description: - • This dataset contains product reviews and metadata of ‘home and kitchen dataset’ category from Amazon, including 2.5 million reviews spanning May 1996 - July 2014. • Dimension of home and kitchen dataset: 551682, 9 • This dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand), and links
