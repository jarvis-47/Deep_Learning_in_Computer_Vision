# Modular Fully Connected Neural Network with CIFAR-10 Dataset

This repository features a Python-based, modular implementation of a fully connected neural network, applied to the CIFAR-10 dataset. The project is structured to explore various aspects of neural network design and optimization:

**Data Preprocessing:** The CIFAR-10 dataset is preprocessed into training, validation, and test sets using Torch tensors, preparing it for neural network training.

**Modular Network Design:** Each network layer, including the ReLU nonlinearity, is implemented with separate forward and backward functions, demonstrating a modular approach to building neural networks.

**Sandwich Layers:** A "Sandwich" layer pattern, where linear layers are followed by ReLU nonlinearities, is utilized to simplify common neural network structures.

**Loss Functions:** Both Softmax and SVM loss functions are integrated and numerically gradient checked for validation.

**Network Architectures:** The implementation includes a two-layer neural network and extends to a multilayer network with arbitrary hidden layers, showcasing scalability.

**Optimization Techniques:** Various optimization methods like SGD, SGD with Momentum, RMSProp, and Adam are implemented and compared, highlighting their impact on network performance.

**Dropout Implementation:** Dropout is incorporated as a regularization technique, and its effect on the network's performance is empirically analyzed.

**Numerical Gradient Checking:** Each component's implementation is verified using numerical gradient checking to ensure correctness.

The repository provides a detailed exploration of neural network components and their interactions, offering valuable insights into deep learning network design and optimization techniques.
