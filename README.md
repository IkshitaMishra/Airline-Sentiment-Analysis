# Airline-Sentiment-Analysis
The dataset includes airline reviews scrapped from Twitter. People have tweeted positive, negative and neutral tweets on airlines. 
This project analyse the sentiments of the tweets using Term frequency - Inverse Document Frequency.
First, the tweets are preprocessed such as removal of hyperlinks, URLs, mentions(@), hashtags (#), emojies etc. Tweets undergo stopword removal, 
lemmatization and tokenization. A Document Term Matrix is created using Term frequency - Inverse Document Frequency Vectorizer.
The matrix, retweet feature along with class labels are fed into Machine Learning classifier. Classifier such as Decision Tree, Random Forest, k-Support Vector Machine and
k- Nearest Neighbours are trained to predict accurate sentiments. The models are trained and tested k-Fold times ( k = 5 ).
Performance is evaluated using Average Accuracy, Average Precision, Average Recall and F-Score across all k-Folds. 

## Conclusion:

Average Accuracy:

Decision Tree Claasifier : 67.46 % 

Random Forest Classifier: 73.04 %

kernal - Support Vector Machine:

k - Nearest Neighbour:

