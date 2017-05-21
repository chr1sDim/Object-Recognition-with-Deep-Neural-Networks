# Image Recognition with Deep Neural Networks

The repository contains various neural network architectures created on Tensorflow for the image classification task on CIFAR-10/100 dataset. The paper (,pdf file) contains the literature and report of the experiments. 

## Advanced Deep CNN Neural Network Architectures

The advanced architectures and set of experiments included in Deep_CNN.py notebooks were implemented within the task of showing and alleviating the Degradation problem of deep neural networks. In order to prove, that the performance of Deep CNNs is degraded due to the complexity of the high dimensional parameter space, experiments with plain deep CNNs and the VGG architecture were conducted. This is proved experimentally and showed with error and accuracy figures.

The degraded performance of very deep convolutional neural networks is countered with three advanced architectures that exploit skip connections and dense stacks of layers. In paricular, ResNet, Highway Network and DenseNet architectures were implmented and proved to alleviate the degradation problem and show significant performance when the networks go as deep as over 50 layers. The experiments were followed by error and accuracy graphs.


## Simple Feedforward Neural Network Architectures

Simple_Deep_NN.py notebooks contain shallow neural networks with a plethora of experiments on different simple architectures such as Batch Normalization, Dropout and L2 regularization. The aim of the experiments was to find an optimal architecture using only simple feedforward neural networks. All of the experiments are followed by error and accuracy graphs. At the end the final model was tuned followed by its confusion matrix.

## References
[1] He, K., Zhang, X., Ren, S., \& Sun, J. (2016). \emph{Deep residual learning for image recognition}. In Proceedings of the IEEE  Conference on Computer Vision and Pattern Recognition (pp. 770-778).

[2] Huang, G., Liu, Z., Weinberger, K. Q., \& van der Maaten, L. (2016). \emph{Densely connected convolutional networks}. arXiv preprint arXiv:1608.06993.

[3] Srivastava, Rupesh Kumar, Klaus Greff, and Jürgen Schmidhuber. \emph{Highway networks}. arXiv preprint arXiv:1505.00387 (2015).
