# CNN-Image-Classifier

Using PyTorch, this Convolutional Neural Network (CNN) classifies images from the CIFAR-10 dataset.

## Model Architecture

5 convolutional layers with ReLU activation, batch normalization, and max pooling

## Data Preprocessing

Use 60,000 32x32 color images in 10 classes and transformed to PyTorch tensors and normalized the pixels

## Train

The model is trained using the Adam optimizer and cross-entropy loss.

## Evaluation

Overall Accuracy: ~79.49%
Plane: 78%
Car: 93.5%
Bird: 75.6%
Cat: 69.7%
Dog: 68.3%
Frog: 88.9%
Horse: 73.4%
Ship: 87.3%
Truck: 87.1%
