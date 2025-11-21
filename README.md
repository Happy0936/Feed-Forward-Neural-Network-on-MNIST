MNIST Digit Classification using Feed Forward Neural Network (PyTorch)

This project implements a simple Feed Forward Neural Network (FFNN) using PyTorch to classify handwritten digits from the MNIST dataset. The dataset contains 28×28 pixel grayscale images stored in CSV format. The model is trained for 20 epochs and achieves high accuracy on the test set.


 Features

1. Preprocessing of MNIST CSV dataset

2. Normalization of pixel values

3. DataLoader for batching

4. FFNN with 2 hidden layers

5. Training + evaluation

6. Single image prediction

7. Achieves around 97–98% accuracy



Model Architecture

1. Input Layer: 784 features

2. Hidden Layer 1: 256 neurons + ReLU + Dropout

3. Hidden Layer 2: 128 neurons + ReLU

4. Output Layer: 10 classes (0–9)
