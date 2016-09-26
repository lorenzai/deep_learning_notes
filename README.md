# Notes on Deep Learning

## from the Author

These are the notes that I left working through Nielson's [neural Net and Deep Learning book](https://neuralnetworksanddeeplearning.com). You can find a table of contents of this repo below.

## Table of Contents
### Chapter 1: Intro to Deep Learning
- [001 - sigmoid function](Ch1%20Intro%20to%20Deep%20Learning/001%20-%20sigmoid%20function.ipynb)
- [002 - training a single perceptron](Ch1%20Intro%20to%20Deep%20Learning/002%20-%20training%20a%20single%20perceptron.ipynb)
- [003 - use perceptrons to target arbitrary function](Ch1%20Intro%20to%20Deep%20Learning/003%20-%20use%20perceptrons%20to%20target%20arbitrary%20function.ipynb)
- [004 - optimize batch training](Ch1%20Intro%20to%20Deep%20Learning/004%20-%20optimize%20batch%20training.ipynb)

### Chapter 2: Intro to Tensorflow
- [005 - Tensorflow Intro](Ch2%20Intro%20to%20Tensorflow/005%20-%20Tensorflow%20Intro.ipynb)
- [006 - Tensorflow Softmax Regression](Ch2%20Intro%20to%20Tensorflow/006%20-%20Tensorflow%20Softmax%20Regression.ipynb)
- [007 - tensorflow API exploration](Ch2%20Intro%20to%20Tensorflow/007%20-%20tensorflow%20API%20exploration.ipynb)

### Chapter 3: Advanced Tensorflow with GPU AWS Instance and PyCharm Remote Interpreter.
- [MNIST Logistic Regression](Ch3%20Advanced%20Tensorflow/1%20-%20MNIST%20Logistic%20Regression.py)
- [MNIST Logistic Regression with L2 Regularization](Ch3%20Advanced%20Tensorflow/2%20-%20MNIST%20Logistic%20Regression%20L2%20Regularization.py)
- [MNIST 1 Hidden Layer with Perceptron](Ch3%20Advanced%20Tensorflow/3%20-%20MNIST%201%20Hidden%20Layer%20Perceptron.py)

### Project 1: Doing Particle Simulation with Tensorflow

- [Annealing A 2-Dimensional Electron Ensemble with Tensorflow]()

## Fun Highlights (Reverse Chronological Order)

### Particle Simulation with Tensorflow! (classical many body simulation 
for my quantum computing research)

<p align="center">
   <img width="300px" height="300px"
        alt="Electron Configuration During Simulation" 
        src="Proj_Molecular_Simulation/figures/Electron%20Configuration%20Animated%20(WIP)%20small.gif"/>
</p>

### Projecting MNIST into a 2-Dimensional Deep Feature Space

<p align="center">
    <img width="174.4px" height="140.2px" src="Proj_Centroid_Loss_LeNet/LeNet_plus/figures/MNIST%20LeNet++%20with%202%20Deep%20Features%20(PReLU).png"/>
</p>


### MNIST ConvNet with TensorFlow

This example does:
- uses different GPUs for training and evaluation
- persist network parameters in check files
- pushes loss and accuracy to summary, which can be visualized by tensorboard

![MNIST ConvNet Tensorflow](Proj_Centroid_Loss_LeNet/convnet_10_hidden/figures/Screenshot%202016-09-16%2011.29.47.png)

### A simple toy example
some of the figures can be found scattered in the folder (I believe in a flat folder 
structure). Like this one below, it shows how a simple network can be trained 
to emulate a given target function.

[![network trained to emulate function](trained%20neural%20net%20emulate%20a%20step%20function.png)](004%20-%20optimize%20batch%20training.ipynb)


## Todos (9/9/2016):

- [ ] MNIST Perceptron logging and visualization with tensorboard
[tensorboard doc](https://www.tensorflow.org/versions/r0.10/resources/faq.html#frequently-asked-questions) [2.0]
- [ ] LeNet training [ConvNet doc](https://www.tensorflow.org/versions/r0.10/tutorials/deep_cnn/index.html) [1.0]
- [ ] LeNet++ training [1.0]
- [ ] Adversarial Hardened LeNet++ [1.0]
- [ ] Adversarial Test of Hardened LeNet++ [1.0]
- [ ] L2 Regularization with Logistic Regression [1.0]

### More Deep Neural Net Learnings
- [ ] Feedforward Neural Network (Multilayer Perceptron)
- [ ] Deep Feedforward Neural Network (Multilayer Perceptron with 2 Hidden Layers O.o)
- [ ] Convolutional Neural Network
- [ ] Denoising Autoencoder
- [ ] Recurrent Neural Network (LSTM)
- [ ] Word2vec
- [ ] TensorBoard
- [ ] Save and restore net

### Done:

- [x] work on optimize batch training. (numpy neural net)
- [x] add summary MNIST example with Tensorflow
- [x] multi-GPU setup [tensorflow doc](https://www.tensorflow.org/versions/r0.10/how_tos/using_gpu/index.html) [0.5 - 1.0]
- [x] CFAR Example [4.0]

## More Useful Links:
- Useful examples: [@Aymericdamien's TensorFlow-Example](https://github.com/aymericdamien/TensorFlow-Examples)
- More useful examples: [@nlintz's TensorFlow-Tutorials](https://github.com/nlintz/TensorFlow-Tutorials)
