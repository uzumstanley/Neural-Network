# Neural-Network

# Machine Learning
Lab 5
In this tutorial, we'll build a supervised classification model that learns to identify digits from 
images. We'll use the well-known MNIST dataset to train and test our model. The MNIST 
dataset consists of 28-by-28 images of handwritten digits along with their corresponding 
labels.
A Conceptual Diagram of the Neural Network
We'll construct a neural network with one hidden layer to classify each digit image into its 
corresponding label. The figure below shows a conceptual diagram of the neural network we 
are about to build. The output layer consists of 10 units, where each unit corresponds to a 
different digit. Each unit computes a value that can be interpreted as the confidence value of 
its respective digit. The final classification is the digit with the maximum confidence value.
