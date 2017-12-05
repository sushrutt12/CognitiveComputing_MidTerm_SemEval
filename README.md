# CognitiveComputing_MidTerm_SemEval
Sentiment Analysis of SemEval Twitter data and news headlines using Keras for supervised learning
http://alt.qcri.org/semeval2017/task5/

### Following were the tasks performed (Not in the exact order) for News Headlines:
- Cleaning the data and converting everything to utf-8 format.
- Dividing the sentiments (labels) into 4 categories -1, -0.5, 0.5 and 1 as the values lie between -1 and 1
- We calculate the max length of features and then convert the data into numpy arrays
- We use a convolutional layer for experiment 1(Exp_1), LSTM for the experiment 2 (Exp_2) and convolutional layer along with embedding for the experiment 3 (New Exp 1)
- We use cosine similarity for measuring the performance
- We predict the scores for the training data using the model which we have trained (Accuracy mentioned under model)
- We predict the scores for the test data using the model and display the results


### Following were the tasks performed (Not in the exact order) for Twitter Data:
- Cleaning the data and converting everything to utf-8 format.
- Dividing the sentiments (labels) into 4 categories -1, -0.5, 0.5 and 1 as the values lie between -1 and 1 (Hidden you can refer to News Headline for code)
- We calculate the max length of features and then convert the data into numpy arrays
- We use a convolutional layer and LSTM for the experiment
- We use cosine similarity for measuring the performance
- We predict the scores for the training data using the model which we have trained (Accuracy mentioned under model)
- We predict the scores for the test data using the model and display the results
