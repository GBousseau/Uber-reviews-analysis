# Uber-reviews-analysis

Tags : Sentiment Analysis - NLP - Logistic Regression (95% accuracy) - Hyperparmeters tuning -  Data analysis - Time series - Data Visualization

The objective of this project was to provide insights to Uber on what people thought felt about their rides and explore what make a ride pleasant or on the contrary what makes it disappointing. To do so I analyzed the Google Play Store reviews of the company between the end of November and mid December. (I used a dataset from Kaggle : "Uber customer reviews dataset"). After preparing my data I proceeded to a snetiment analysis, a logostic regression, and finally interpreted my results.

The main conclusions are : 
- Uber customers are mostly satisfied about the service provided
- The evolution of sentiment repartition is pretty stable across time except a pic of positive comments in early December.
- The predominant factor in customers'sentiment is the driver, then comes the app
- Amongst the factors leading to negative comment we have : scams, paiment method, cancellation and delay
- People satisfied about their trip tend to focus on their feelings rather than their orgine
  
**Table of content**

1. **DATA PREPARATION**
- check data consistency
- removing all useless characters
- data optimization (dimensionality reduction)

2. **SENTIMENT ANALYSIS**
- vader score computation
- classification

3. **LOGISTIC REGRESSION**
- baseline model 
- hyperparameter tuning

4. **INTERPRETATION AND ANALYSIS**
- sentiment distribution
- sentiment VS time
- sentiment VS hour of a day
- Explaining sentiment : What stands out of the comments ? 
- Explaining sentiment : What made people so satisfied in early December ?

Hope you will enjoy !
