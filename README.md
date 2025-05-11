# HandwrittenDigit_FaceClassification_using_NeuralNetworks

This repository contains an implementation of a Multilayer Perceptron (MLP) neural network from scratch in Python to classify handwritten digits (MNIST dataset) and facial attributes (CelebA subset - glasses vs. no glasses). The project includes comparison with deep learning approaches using TensorFlow and Convolutional Neural Networks (CNN).

- nnScript.py: Implements the MLP with backpropagation, sigmoid activation, and regularization.
- facennScript.py: Adapts the MLP for binary classification on CelebA.
- deepnnscript.py: TensorFlow-based MLP implementation.
- cnnscript.py: Convolutional Neural Network using TensorFlow/Keras.
- params.pickle`: Serialized model weights and metadata.

## 📊 Results
### MNIST (10-class classification)
- Best accuracy: **94.88%** with 50 hidden units, λ=0.
- CNN accuracy: **98.4%**

### CelebA (binary classification)
- Best MLP accuracy: **85.38%** with 256 hidden units, λ=10.
- Deep Neural Network: **79.9%**
- CNN accuracy: **86.1%**

## ⚙️ Hyperparameter Tuning
- Regularization (λ): 0 to 60 in steps of 5 or 10.
- Hidden Units: 4 to 256.
- Evaluation based on validation accuracy and training time.
