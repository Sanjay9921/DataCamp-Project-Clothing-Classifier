# E-Commerce Clothing Classifier Model

## Description

The CNN-based image classifier model helps streamline inventory management and improves customer experience by categorizing clothing items into classes such as shirts, trousers, dresses, etc.

## Project Highlights

- Used FashionMNIST dataset with 10 clothing categories.
- Defined a small CNN with convolution, ReLU, max-pooling, flattening, and fully connected layers.
- Trained the model with cross-entropy loss and Adam optimizer.
- Evaluated using accuracy, precision, and recall metrics.
- Predicted classes on the test dataset and visualize results.

## Usage

1. Define the CNN model architecture.
2. Train on the training dataset with a few epochs.
3. Predict on the test dataset and calculate evaluation metrics.
4. Visualize performance with confusion matrix and misclassified samples.

## Metrics

- Accuracy
- Per-class Precision
- Per-class Recall

## Technologies

- PyTorch for model building and training
- torchvision for datasets and transformations
- torchmetrics for performance evaluation
- matplotlib and seaborn for visualizations

## Credits

Datacamp - project base and tutorial