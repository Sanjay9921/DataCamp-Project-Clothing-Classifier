# E-Commerce Clothing Classifier Model

## Description
Build a CNN-based image classifier to automate product tagging for an e-commerce clothing store. This model helps streamline inventory management and improves customer experience by categorizing clothing items into classes such as shirts, trousers, dresses, etc.

## Project Highlights
- Use FashionMNIST dataset with 10 clothing categories.
- Define a small CNN with convolution, ReLU, max-pooling, flattening, and fully connected layers.
- Train the model with cross-entropy loss and Adam optimizer.
- Evaluate using accuracy, precision, and recall metrics.
- Predict classes on the test dataset and visualize results.

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