# Emotion-Recognition

This is a simple NLP project that can recognize the emotion of a sentence and classify it into one of six classes: sadness, anger, love, surprise, fear, and joy. The model architecture was customized using a bidirectional LSTM as the main layer, and global vector embeddings were used to improve the accuracy and efficiency of the model.

### Dataset
The dataset used to develop this model consists of  20,000 annotated texts. The dataset was preprocessed first, including tokenization and embedding so that it can be processed properly by the model. The training set contains 16,000 texts, the validation set contains 2,000 texts, and the test set contains 2,000 texts.

### Model Architecture
The model architecture consists of two bidirectional LSTM layer with 32 hidden units, followed by a dense layer and dropout layer and a softmax activation function at the output layer. The input to the model is a sequence of global vector embeddings, which were precomputed using the GloVe algorithm on a large corpus of text.

The model was trained using the Adam optimizer with a learning rate of 0.005, and the sparse categorical cross-entropy loss function. The training accuracy of the model is 97.6%, and the validation accuracy is 91.7%.
