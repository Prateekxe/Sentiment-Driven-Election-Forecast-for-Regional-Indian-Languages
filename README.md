# Sentiment-Driven-Election-Forecast-for-Regional-Indian-Languages
 NLP-based sentiment analysis model to predict election outcomes using social media and news data.

Overview
This repository provides a series of notebooks for conducting sentiment analysis on election-related text data. The project is divided into multiple stages, starting from data cleaning and preprocessing, followed by different methods for sentiment prediction using machine learning techniques.

Files in this Repository
1. Indian_Election_Sentiment_Analysis_Data_Preprocessing.ipynb
Purpose: This notebook is dedicated to data cleaning and preprocessing. It prepares the election-related text data by:
Loading and inspecting the dataset
Cleaning the text (removing special characters, numbers, and unnecessary symbols)
Tokenizing the text into words
Removing stopwords to improve model performance
Performing stemming and lemmatization for normalization
2. Indian_Election_Sentiment_Analysis_method_1.ipynb
Purpose: This notebook uses Polarity and Sentiment Score methods to predict sentiment outcomes. It calculates the sentiment polarity score for each piece of text, classifies the sentiment as positive, negative, or neutral, and visualizes the sentiment distribution.
Techniques involved: Sentiment Polarity Calculation using libraries like TextBlob.
3. Indian_Election_Sentiment_Analysis_method_2.ipynb
Purpose: This notebook applies a Naive Bayes Classifier for sentiment prediction. It builds a model using the processed data and predicts sentiment categories (positive, negative, neutral) based on the training data.
Techniques involved: Naive Bayes algorithm (MultinomialNB).
4. Indian_Election_Sentiment_Analysis_method_3.ipynb
Purpose: This notebook uses Logistic Regression for sentiment prediction. It trains a Logistic Regression model on the preprocessed text data to classify sentiment based on election-related opinions.
Techniques involved: Logistic Regression classification.
5. Indian_Election_Sentiment_Analysis_method_4.ipynb
Purpose: This notebook applies the Support Vector Classifier (SVC) for sentiment classification. It builds and evaluates an SVC model to predict sentiments (positive, negative, neutral) from election-related text data.
Techniques involved: Support Vector Classifier.
