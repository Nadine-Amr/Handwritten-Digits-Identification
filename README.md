# Handwritten-Digits-Identification

Using Keras, a fully-connected neural network was used to classify handwritten digits from the MNIST dataset (http://yann.lecun.com/exdb/mnist/). 

The following variations of the neural network were tried out and the corresponding training and testing accuracies were recorded:
1. Number of Hidden Layers (HL): 2 vs 3
2. Gradient Descent Method (GD): Adam vs Stochastic Gradient Descent
3. Activation Function for Hidden Layers (AF): ReLU vs Sigmoid

The following choices were made:
• Number of nodes in configurations with 2 hidden layers: (600, 100)
• Number of nodes in configurations with 3 hidden layers (600, 50, 50)
• Adam Learning Rate: 0.001 (default)
• SGD Learning Rate: 0.01 (default)
• Number of Epochs: always started with 10, then increased as necessary
• Batch Size: 128
• Loss Function: Sparse Categorical Cross Entropy
• Metrics: Accuracy

Results can be summarized in the following 2 tables:

![image](https://user-images.githubusercontent.com/25527107/193187820-10f671a4-e0c1-4f06-8cbf-22e100d1d699.png)

![image](https://user-images.githubusercontent.com/25527107/193187848-78dcd580-2cdf-4426-ab32-ed9c55d4e9da.png)
