# Mini Fashion MNIST Image Classifier

A beginner-friendly Convolutional Neural Network (CNN) built on the **Fashion MNIST** dataset.  
This project is designed for local Jupyter Notebook usage and focuses on the core concepts of deep learning with a simple, hands-on approach.

## Objectives

- Understand the structure of a CNN.
- Learn how to preprocess image data for deep learning.
- Train and evaluate a model on the Fashion MNIST dataset.
- Make predictions and visualize results.
- Explore basic model performance metrics.
- 
## Setup

## Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

### **`macOS`**
```BASH
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/bin/activate
  pip install --upgrade pip
  pip install -r requirements.txt
  ```
### **`WindowsOS`**
 For `PowerShell` CLI :

  ```PowerShell
  pyenv local 3.11.3
  python -m venv .venv
  .venv\Scripts\Activate.ps1
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```

  For `Git-Bash` CLI :

  ```
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/Scripts/activate
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```


## Optional Extensions

- Modify the CNN architecture (e.g., add/remove layers).
- Change the number of epochs to see its effect on training.
- Experiment with different datasets (e.g., MNIST digits, CIFAR-10).
- Implement data augmentation to improve model performance.

## Tips

- Fashion MNIST contains **10 categories** of clothing items (t-shirt, trouser, pullover, dress, etc.).
- Training on CPU is fast, but using a GPU will make it faster.
- Focus on understanding the workflow rather than achieving perfect accuracy.

### N.B. Do not clone a git repository inside another git repository! So please do the git clone ... command in a directory that is not already a git repository !