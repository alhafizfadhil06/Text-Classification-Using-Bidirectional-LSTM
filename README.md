# Text Classification Using Bidirectional LSTM
This repository contains the implementation of a text classification model using Bidirectional LSTM. The model is trained on a dataset of 20,000 text samples, which is divided into 16,000 samples for training and 4,000 samples for testing and validation.

The dataset consists of text samples labeled with 6 different emotions: Joy, Sadness, Anger, Fear, Love, and Surprise. Before training the model, the dataset undergoes text preprocessing to improve the quality of the input data. This includes deleting all non-alphabet characters, converting all the characters to lowercase, and removing stopwords using RegEx and the Natural Language Toolkit (NLTK).

To better represent the text data, the model uses pretrained Global Vector Embedding (GloVe). GloVe is a popular word embedding technique that captures the semantic meaning of words in a vector space. By using GloVe, the model can better understand the context of words and improve its accuracy.

The main component of the model architecture is the Bidirectional LSTM layer. This layer is a type of recurrent neural network that allows the model to process the text in both forward and backward directions. This helps the model to capture the long-term dependencies in the text and improve its ability to classify emotions accurately.

To evaluate the performance of the model, we use the validation accuracy metric. After training the model, we achieve a validation accuracy of 91%, which demonstrates the effectiveness of our approach.

Finally, this repository provides a visualization of the dataset to help users gain insights into the distribution of emotions in the dataset. Users can also modify the code and experiment with different hyperparameters to improve the accuracy of the model further.
