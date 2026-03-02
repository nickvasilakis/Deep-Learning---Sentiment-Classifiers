# Deep-Learning---Sentiment-Classifiers
This repository consists of 3 methods for sentiment classification on a Twitter dataset. This was done as a part of an NLP course at the University of Athens. The three methdods include building a Logistic Regression classifier, building a feedforward neural network for sentiment classification, and finally fine tuning a BERT and DistilBERT model.

## Project Stages
- Logistic Regression Model: Built using TF-IDF Text Representation and a simple Logistic Regression model. This was done as our baseline model, in order to see how (and if) more complicated models improve accuracy on sentiment classification
-  Feedforward Neural Network Model: Built using pre-trained word embeddings and is a much more complicated model compared to the simple Logistic Regression one. Optimization techniques such as Early Stopping and Dropout were used
- Fine-tuning BERT and DistilBERT models: Built by fine tuning two models based on the transformer architecture. This achieved by far the best results outperforming the previous two methods.
