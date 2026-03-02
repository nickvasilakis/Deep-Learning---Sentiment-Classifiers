# Deep-Learning---Sentiment-Classifiers
This repository consists of 3 methods for sentiment classification on a Twitter dataset. This was done as a part of an NLP course at the University of Athens. The three methdods include building a Logistic Regression classifier, building a feedforward neural network for sentiment classification, and finally fine tuning a BERT and DistilBERT model.

## Repository Purpose
This repository serves the purpose of showcasing how the increased complexity of machine learning models can improve the accuracy of specific Natural Language Processing tasks. In our example, Logistic Regression and a simple Feedforward Neural Network achieve similar accuracy in the task of sentiment classification. However, as soon as a large pretrained model with a transformer architecture is included, accuracy significantly increases, demonstrating the capabilities of such architectures, as well as the importance of having an already pretrained large language model.

## Project Stages
- **Logistic Regression Model**: Built using TF-IDF Text Representation and a simple Logistic Regression model. This was done as our baseline model, in order to see how (and if) more complicated models improve accuracy on sentiment classification. Text preprocessing was the main focus for this project as it highly improved accuracy when specific preprocessing was made such as removing punctuations, URLs or correcting spelling mistakes.
- 
-  **Feedforward Neural Network Model**: Built using pre-trained word embeddings and is a much more complicated model compared to the simple Logistic Regression one. Optimization techniques such as Early Stopping and Dropout were used. Optimization techinques and fine tuning hyperparameters was the main focus of this project and it demonstrated how much dropout, early stopping and adding activation functions such as ReLU can improve the efficiency of a model.
-  
- **Fine-tuning BERT and DistilBERT models**: Built by fine tuning two models based on the transformer architecture. This achieved by far the best results outperforming the previous two methods. Fine tuning hyperparameters was the main difficulty in this task, as well as the long computation time compared to the other two projects. For the purpose of tuning hyperparameters, the tool 'Optuna' was used.

## Notes
- The datasets are not included in the repository
- The reports are exactly the ones submitted for academic evaluation
