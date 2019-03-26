# Neural_Network_Self_Implementation

Code for self implementation of a Neural Network : In this code I have worked on the MNIST(Database of Handwritten Digits)     dataset. The classification is done for the digits 1 and 7 as they look quite similar. 
Data Preprocessing : The training points for which the output is either 1 or 7 are selected from the complete MNIST database                        and stored in our dataframe. Next we split the data into training and testing data. All the input                              features are scaled using the  sklearn StandardScaler. 
Code Explanation: In this code I have considered 3 hidden layers with 20 units in hidden_layer1 , 10 units in hidden_layer2 ,                   15 units in hidden_layer3 and 1 unit in the output_layer. Forward propagation is performed to find the                         output and activation function used is the Sigmoid Function. The train function trains the neural network by                   reducing the error through BackPropagation and finds the best weights and biases.  

The predictions are made and a score of perfect 1 is obtained .
