### basic_mnist.ipynb: baseline classifier model for the MNIST numbers dataset
- 3 layers: flatten, linear, linear
- 91.21% accuracy
- runs on cpu

### tinyvgg_cnn_mnist.ipynb: more complex classifier model for the MNIST numbers dataset
- implements the tinyvgg convolutional neural network architecture from [here](https://www.learnpytorch.io/03_pytorch_computer_vision/#7-model-2-building-a-convolutional-neural-network-cnn](https://poloclub.github.io/cnn-explainer/))
- 97.97% accuracy
- runs on gpu if available

### cifar10_resnet18_cnn.ipynb: resnet18 model, cifar10 dataset
- resnet18 model from [this paper](https://arxiv.org/abs/1512.03385v1), cifar10 classification dataset
- 60.66% accuracy so far (because of gpu usage limits; accuracy increases as the number of epoch increases, so will continue to train on gpu with unlimited usage)

