# Introduction
This project includes implementations of Convolutional Neural Networks (CNN) and Multi-Layer Perceptrons (MLP) algorithms for classifying the MNIST dataset. The MNIST dataset consists of 70,000 handwritten digits, which are labeled from 0 to 9. The dataset is commonly used for benchmarking image classification models.

# Dependencies
To run the CNN and MLP algorithms, you will need the following dependencies:

Python 3.6+
Pytorch
NumPy
Matplotlib
scikit-learn

# Usage
To use the CNN and MLP algorithms, you can follow these steps:

Download the MNIST dataset.
Install the dependencies listed above.
Clone this repository to your local machine.
Open the terminal and navigate to the directory where you cloned the repository.
Run python cnn.py to train and test the CNN algorithm, or run python mlp.py to train and test the MLP algorithm.
Note that both the CNN and MLP algorithms have default hyperparameters, which you can modify by changing the values in the hyperparameters dictionaries in the cnn.py and mlp.py files. You can also change the number of training epochs and batch size in the same files.


# Conclusion
In this project, we have implemented CNN and MLP algorithms for classifying the MNIST dataset. The CNN algorithm outperforms the MLP algorithm in terms of accuracy, but it requires more computational resources and training time. The MLP algorithm is simpler and faster to train, but it may not perform as well as the CNN algorithm on more complex image datasets.

