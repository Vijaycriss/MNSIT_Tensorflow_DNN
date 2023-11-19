# MNSIT_Tensorflow_DNN
Deep Neural Network for MNIST Classification

The dataset is called MNIST and refers to handwritten digit recognition. You can find more about it on Yann LeCun's website (Director of AI Research, Facebook). He is one of the pioneers of what we've been talking about and of more complex approaches that are widely used today, such as covolutional neural networks (CNNs).

The dataset provides 70,000 images (28x28 pixels) of handwritten digits (1 digit per image).

The goal is to write an algorithm that detects which digit is written. Since there are only 10 digits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9), this is a classification problem with 10 classes.

Our goal would be to build a neural network with 4 hidden layers.

Shuffle_size = 10000
Batch_size = 1000
input_size = 784
output_size = 10
hidden_layers_size = 2000
hidden_layers = 4
Activation_function = 'relu'

Test loss : 0.07, Test accuracy: 97.97%



Deep Neural Network for Audiobooks_customer_classification

The goal is to write an algorithm that predicts wheather the customers will buy the audiobook again.

Batch_size = 100
input_size = 10
output_size = 2
hidden_layers_size = 50
hidden_layers = 2
Activation_function = 'relu'

Test loss : 0.36, Test accuracy: 81.70%



