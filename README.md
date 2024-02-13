This file is my part of a group project for Natural Language Processing where we tried to guess the right star value out of five possible star values for a review in the yelp review dataset: https://www.yelp.com/dataset

In this file, I use 4 different types of neural networks using Keras from Tensorflow, including simple RNN, LSTM, CNN, and GRU. The accuracy for predicting the exact star value was around 55% for all the models, while the simple RNN was around 50%. 
This might seem low on the surface, but it's actually very hard to predict the exact star value. If you look at the accuracy within 1 star of error, it's around 90%, which is much better. The difference between a 2 rating and a 3 rating can be very ambiguous, so judging the model on 
it's accuracy within 1 star gives a much better understanding of the model's performance. 
