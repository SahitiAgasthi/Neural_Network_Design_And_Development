# Neural_Network_Design_And_Development

The dataset consists of Movie reviews and corresponding sentiment negative or positive. The reviews.txt consists of reviews and the labels.txt consists of the sentiment i.e., if the review is positive or negative.
I have designed a neural network to find out what will happen when weights are initialized to zero.
My neural network consists of 2 input nodes and one hidden layer comprising two nodes and one output node with weights W1, W2, W3, W4, W5 and W6. The activation function for the two nodes in the hidden layer is taken as the Sigmoid activation function.

The neural network is as follows:

![image](https://user-images.githubusercontent.com/68881506/111374814-8b341100-866b-11eb-9f1c-476e1cbe9b55.png)


I developed the code from scratch without using any libraries.

The evaluation metric for this task is chosen as Accuracy.

Approach taken:
1. Initially predicted Movie reviews by applying Continuous Bag of Words(CBOW) approach.
2. Tried to utilize GPU's.
3. Later initiated weights to zero.

# Observations:
1. Weights increased by equal amounts at every epoch.
2. Since we initiated weights to zero, the network could not learn properly, so it is better to initiate weights to some value.

# The data description
The data set has two files: reviews.txt, labels.txt.
The reviews.txt has single column: text. text column has Movie reviews. The labels.txt has single column: target. target has the sentiment whether it is positive or negative.

# Evaluation Metrics
The evaluation metric for this task is taken as Accuracy.
Accuracy is an evaluation metric that allows you to measure the total number of predictions a model gets right.
Accuracy = (TN + TP)/ ( TN + TP + FN + FP)

