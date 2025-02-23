# IMDB-review-sentiment
Sentiment Analysis on the reviews on IMDB

The first part of the file has a classifier. I have splitted the database into 80% trainning and 20% testing. Bag-of-words model has been used to convert the reviews into vectors. Logistic regression model and a naive bayes model have been used and visualization techniques have been used to compare their accuracies. 


In the second part of the file TF-IDF have been used to convert the reviews into vectors. Logistic regression and naive bayes models on this as well, and a comparision is made on how the models are performing.


In the third part of the file a shallow single hidden layer, recurrent neural network model has been used to do the same thing. The  model will has three layers: one Embedding Layer with output shape 100 which will convert words to a 100-length vector, one dense layer with an output shape 10, and the final output layer (another dense layer) with output shape 1. As Sequential neural nets use word vectors, not sentence vectors that were used in previous two tasks. 

Pretrained GloVe embeddings has been used into an embedding layer. This embedding layer is my input layer, which will feed into hidden dense layer, and the output of dense layer will give a probability whether the review is positive or negative.
I have run it for 50 epochs and made comparisions with the models. 
