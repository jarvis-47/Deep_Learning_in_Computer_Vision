# Deep Learning Exploration with Convolutional Neural Networks on CIFAR-10

## Description:

This repository presents my comprehensive project on constructing and refining Convolutional Neural Networks (CNNs) to classify images from the CIFAR-10 dataset, written entirely in Python. The project is segmented into multiple phases, each focused on a critical aspect of CNN development and optimization.

## Key Components and Features:

**Convolutional Layer Development:** Starting with the basics, I implemented forward and backward passes for convolutional layers. This foundational work was crucial for understanding the mechanics behind CNNs.

**Optimized Layer Implementations:** To enhance computational efficiency, I integrated 'FastConv' and 'FastMaxPool' layers, leveraging PyTorch's advanced functionalities. This optimization was pivotal in handling the computationally intensive nature of deep CNNs.

**'Sandwich' Layer Construction:** Recognizing patterns in neural network architectures, I developed 'sandwich' layers, such as Conv-ReLU and Conv-ReLU-Pool, which streamline the assembly of common layer sequences.

**Three-Layer CNN Architecture:** I then applied these layers to construct a basic three-layer CNN, experimenting with this architecture to understand the nuances of layer interactions and network depth.

**Deep CNN with VGGNet Style:** Advancing further, I explored a deeper convolutional network architecture inspired by VGGNet. This phase involved handling more complex structures and understanding how deeper networks function.

**Kaiming Initialization:** To optimize the network initialization, I implemented Kaiming Initialization, addressing the issue of weight scaling in deep networks.

**Batch Normalization Techniques:** A significant portion of the project was dedicated to integrating batch normalization, both for fully connected and convolutional layers. This included spatial batch normalization, adapting the technique for the specificities of CNNs.

**Learning Rate and Batch Normalization Interaction:** The final experimental phase involved studying how batch normalization interacts with different learning rates, offering valuable insights into the training dynamics of deep networks.

**Model Evaluation and Visualization:** Throughout the project, I conducted extensive testing, including gradient checks and training performance assessments. Visualizing first-layer convolutional filters provided an intuitive understanding of the network's feature extraction.

## Project Outcomes and Learnings:

This project not only solidified my understanding of CNNs and their components but also provided hands-on experience in optimizing deep learning models. The successful application of these networks on the CIFAR-10 dataset highlighted the effectiveness of the implemented techniques and the importance of careful architectural design in deep learning.
