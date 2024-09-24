# Neural Network MNIST Classifier

This notebook implements a simple feed-forward neural network from scratch to classify handwritten digits from the MNIST dataset. The model is written in Python using NumPy and provides several features for training, testing, and visualization. The dataset was obtained from Kaggle

## Features
- **Training**: Uses gradient descent to minimize cross-entropy loss and optimize the network's parameters.
- **Activation Functions**: Includes ReLU and softmax functions for hidden and output layers, respectively.
- **Accuracy and Loss Tracking**: Displays real-time plots of loss and accuracy during training.
- **Visualization**: 
  - Visualizes learned weights from the first layer.
  - Displays confusion matrix for performance analysis.
  - Allows testing of individual handwritten digit predictions with visual feedback.
- **User Interaction**: Includes functionality to predict digits from custom-drawn images on a canvas.

## Usage
1. Train the network on MNIST using `gradient_descent`.
2. Test accuracy on a development set using `test_accuracy`.
3. Visualize the learned weights and confusion matrix.
4. Draw your own digits and see predictions in real-time.

This notebook serves as a base for further experimentation with neural networks.
