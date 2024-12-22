### Amazon Alexa Sentiment Analysis
##### Project Overview
This project aims to analyze customer reviews of Amazon Alexa products to determine their sentiment. Sentiment analysis helps in understanding customer opinions and improving product offerings. The goal is to classify reviews into positive, negative, or neutral sentiments using machine learning techniques.

##### Dataset
The dataset contains Amazon Alexa customer reviews, which include:

Source: Kaggle (Amazon Alexa Reviews dataset)

Number of Reviews: 3150 reviews

##### Data Attributes:

review_text: The text of the review

rating: The star rating given by the customer

date: The date of the review

variation: The product variation

##### Preprocessing Steps:

Analyse the data with univariate & byviariate techniques

Analyze Wordcloude

Removing punctuation and special characters

Converting text to lowercase

Removing stopwords

Used Count Vectorizer to create bag of words

##### Features:
Text Preprocessing: Cleaning and preparing the review text for analysis.

Sentiment Analysis: Classifying reviews into positive or negative sentiments using models like Random Forest Classifier

Visualization: Displaying results using charts and graphs.

Model Evaluation: Evaluating model performance using metrics like accuracy, precision, recall, and F1 score.

##### Model Performance:
Random Forest Classifier Train Data Accuracy: 99%
Random Forest Classifier Test Data Accuracy: 94%

##### Insights:

Positive reviews are more frequent than negative reviews.
Common themes in positive reviews include ease of use and voice recognition.
Negative reviews often mention issues with connectivity and device compatibility.
