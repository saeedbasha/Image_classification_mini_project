# Mini Fashion MNIST Image Classifier

A beginner-friendly Convolutional Neural Network (CNN) built on the **Fashion MNIST** dataset.  
This project is designed for local Jupyter Notebook usage and focuses on the core concepts of deep learning with a simple, hands-on approach.

## Objectives

- Understand the structure of a CNN.
- Learn how to preprocess image data for deep learning.
- Train and evaluate a model on the Fashion MNIST dataset.
- Make predictions and visualize results.
- Explore basic model performance metrics.

## Requirements

- Python 3.x
- Jupyter Notebook
- TensorFlow 2.x
- NumPy
- Matplotlib

Install dependencies using:

```
pip install tensorflow numpy matplotlib jupyter
```

## How to Run

1. Clone or download this repository.
2. Open `image_classifier.ipynb` in Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Run all cells sequentially.
4. Observe:
   - Model training and validation accuracy.
   - Predictions on test images.
   - Training history plots.

## Optional Extensions

- Modify the CNN architecture (e.g., add/remove layers).
- Change the number of epochs to see its effect on training.
- Experiment with different datasets (e.g., MNIST digits, CIFAR-10).
- Implement data augmentation to improve model performance.

## Tips

- Fashion MNIST contains **10 categories** of clothing items (t-shirt, trouser, pullover, dress, etc.).
- Training on CPU is fast, but using a GPU will make it faster.
- Focus on understanding the workflow rather than achieving perfect accuracy.
