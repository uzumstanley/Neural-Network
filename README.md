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
![Screenshot 2024-09-16 at 13 57 59](https://github.com/user-attachments/assets/f51a0ffe-c71a-4f03-9d99-d6a2ff2efc95)

Figure 1: Conceptual diagram of the neural network. Each output unit corresponds to a digit 
and has its confidence value. The final classification is the digit with the maximum 
confidence value.
