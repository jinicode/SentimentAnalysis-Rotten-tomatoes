# SentimentAnalysis-Rotten-tomatoes
Sentiment Analysis on Rotten Tomatoes dataset of 150,000 reviews .<br />
### Refer FinalMovieReview notebook
## 1->Tokenized the reviews <br />
## 2->Removed punctuations stopwords and duplicate reviews <br />
## 3->Used CountVectorizer and Tf-Idf transformation to convert reviews to word-vectors <br />
## 4->Created Pipeline for predictions <br />
## 5->Used vader for sentiment analysis which didn't performed well <br />
## 6->Used LinearSVC (accuracy  0.81) <br />
## 7->Used LogisticRegression (accuracy  0.80) <br />
## 8->Used RandomForestClassifier (accuracy  0.80) <br /> 
## 9-> Used LSTM for predicting exact rating between 1 to 5 but got accuracy of 0.43
