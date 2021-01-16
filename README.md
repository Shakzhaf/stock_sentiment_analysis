# Stock Sentiment Analysis
Predict if a companies stock will increase or decrease based on news headlines using sentiment analysis.

## Sentiment Analysis 
Sentiment analysis is the measurement of neutral, negative, and positive language. It is a way to evaluate spoken or written language to determine if the expression is favorable (positive), unfavorable (negative), or neutral, and to what degree.

## Algorithms
- Decison Trees
- Naive Bayes

## The solution is divided into the following sections:
- Data understanding and exploration
- Data cleaning
- Data preparation
- Model building and evaluation

### Data Understanding and exploration
Since this is a timeseries data we have taken all data before date 2015/01/01 in train and data on and after date 2015/01/01 in test.

### Data cleaning
We have removed all punctuations and special characters from the data and all characters have been converted to lower cases.

### Data preparation
The sentences have been converted into bag of words using CountVectorizer.

### Model Building and Evaluation 
- Decision  Trees: 83 %
- Naive Bayes: 84.6 % 
