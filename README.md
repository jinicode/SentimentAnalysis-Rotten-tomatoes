# SentimentAnalysis-Rotten-tomatoes
Sentiment Analysis on Rotten Tomatoes dataset .
1->Tokenized the reviews 
2->Removed punctuations stopwords and duplicate reviews 
4->Used CountVectorizer and Tf-Idf transformation to convert to word-vectors
5->Created Pipeline for predictions
6->Used vader for sentiment analysis which didn't performed well 
7->Used LinearSVC (accuracy  0.81)
8->Used LogisticRegression (accuracy  0.80)
9->Used RandomForestClassifier (accuracy  0.80)
