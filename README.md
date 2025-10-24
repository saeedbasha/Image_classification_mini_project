# Mini Fashion MNIST Coding Project

## Objectives
- Load and preprocess Fashion MNIST dataset
- Build your own Convolutional Neural Network (CNN)
- Train and evaluate the model
- Make predictions on test images
- Optional: experiment with architecture or training parameters

## Instructions
1. Open `starter_notebook.ipynb` in Jupyter Notebook
2. Complete the code in the TODO sections:
   - Build the CNN
   - Compile the model
   - Train the model
   - Evaluate performance and make predictions
3. Use only the provided libraries: TensorFlow, NumPy, Matplotlib
4. Submit the completed notebook

## Hints
- Use `layers.Conv2D`, `layers.MaxPooling2D`, `layers.Flatten`, and `layers.Dense`
- Compile with `optimizer='adam'` and `loss='sparse_categorical_crossentropy'`
- Train for 5 epochs and visualize training history
- Make predictions with `model.predict()`
- Optional: modify layer filters, activations, add dropout, or adjust epochs
