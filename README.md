# learnitgirl
# Personality Prediction from Tweets
It is the python code to predict personality from tweets. We use the big 5 traits to predict the traits. The big 5 traits are openess, conscientiousness, extraversion, agreeableness and neuroticism.
## Files
1. fileprocess.py - extracting tweets
2. tweetprocess.py - pre-processing the tweets
3. featureextraction.py - extracting relevant features for text classification
4. trainprocess.py - testing accuracy of the models of classificatio and regression and training
5. modelrun.py - fitting model to the data

Classification model used is stochastic gradient descent with 1000 iterations since it is best for text classification and natural language processing. The prediction accuracy of the model is found to be 53%. The training set consist of 70% of the tweets and remaining 30% is used in testing. The system's output consist of trait percentages as well as a bar graph showing the trait distribution.
