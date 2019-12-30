# Tensorflow 2.0 Advanced Course: Transfer Learning: Project 1
## PROBLEM STATEMENT
 - Transfer learning is a machine learning technique in which intelligence (i.e.: weights) from a base artificial neural network is being transferred to a new network as a starting point to perform a specific task.
 - Transfer learning is a key skill to acquire as a data scientist since it can dramatically reduce the computational time required if the network is being trained from scratch (i.e.: starting from purely random weights).
 - In this project, we will apply Transfer learning to repurpose trained weights from ResNet 50, which is a famous deep network, to perform classification tasks on a new datasets.
 - A pre-trained ResNet50 model that has been trained on ImageNet will be repurposed and used to classify new images of cats and dogs
 - The new model will consist of two parts:
    - (1) "base" pre-trained network
    - (2) "new dense network classifier"
 - The feature maps that has been previously trained will be augmented with a new classifier (new Dense layers) so we do not have to train the model from scratch
 - Fine tuning can be performed by unfreezing the top layers (base) and slowly training the entire network so an improved performance can be achieved.
 - ResNet50 is a deep residual learning architecture that is widely used for image classification
 - The ResNet50 is trained using ImageNet which is an open source repository of images
 - Citations: Olga Russakovsky, Jia Deng, Hao Su, Jonathan Krause, Sanjeev Satheesh, Sean Ma, Zhiheng Huang, Andrej Karpathy, Aditya Khosla, Michael Bernstein, Alexander C. Berg and Li Fei-Fei. (* = equal contribution) ImageNet Large Scale Visual Recognition Challenge. arXiv:1409.0575, 2014.
  - Paper: https://arxiv.org/abs/1409.0575
  - Data Source: https://www.kaggle.com/tongpython/cat-and-dog
