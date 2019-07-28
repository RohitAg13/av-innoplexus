### Innoplexus: Sentiment Analysis

[Analytics Vidhya](https://datahack.analyticsvidhya.com/contest/innoplexus-online-hiring-hackathon/)

My Approach:

It is ensemble of following two models:

1. Naive Bayes Logistic Regression.
	1. Using Tf-idf 
	2. Logistic Regression with class_weight = "balanced" turn out to be very important parameter.

2. Random Forest on feature engineered meta data about the text.

 Weighted average of both the models.
