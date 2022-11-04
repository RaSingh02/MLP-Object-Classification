# MLP Object Classification

Was tasked to implement an multilayer perceptron for object classification. The architecture was to be trained to be able to classify 10 different clothing items within the fashion MNIST dataset. The dataset can be found [here](https://www.tensorflow.org/datasets/catalog/fashion_mnist). Utilized the [TensorFlow](https://www.tensorflow.org/) framework to implement the MLP and Keras to build the model. The selected the number of layers and nodes in each layer. The input and output layers' nodes were determined based on the dataset. The test accuracy was required to be at least 70%. Hyperparameter tuning was also implmented to improve the accuracy of the model. A grid search was used to find the best hyperparameters. The best hyperparameters were then used to train the model. The best hyperparameter combination was found to be 85.11%. Utilizing these parameters, the final best accuracy was reported to be 85.47%. The final parameters were as follows:

- Hidden Layer: 256
- Node Value: 128
- Activation function: relu

There is some similarity between the training accuracy and validation accuracy as seen in the .ipynb file in the repository. The peaks as seen in the final graph can be attributed to the different activation functions at play. The similarity can be attributed to the fact that the training and validation data are from the same dataset.
