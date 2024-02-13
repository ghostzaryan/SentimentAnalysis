# SentimentAnalysis
This project aims to perform sentiment analysis on text data using a Recurrent Neural Network (RNN) implemented with Keras. Sentiment analysis involves determining the sentiment expressed in a piece of text, such as positive, negative, or neutral.

## Working of the Model
The model is a Sequential model, which contains a linear stack of neural layers. The first layer is a simple RNN layer which consists of 50 neurons, whereas the second layer is a Dense layer with 6 neurons. Finally, the last layer is a softmax activation layer. After the neural network is ready, KerasCLassifier is used as the wrapper to help train the model with the training data.

## Usage
To use the model to determine sentiment of a text, the text string will first have to be tokenized and then padded. After storing that as a list, you can use the model to predict the sentiment
