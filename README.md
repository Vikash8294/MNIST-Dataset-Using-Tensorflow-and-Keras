# MNIST 

Simple experiments (MNIST.ipynb) using TensorFlow / Keras:

Steps
- Step 1: Manual flatten -> simple Dense output (no hidden) Using (reshape). Accuracy: 0.9172
- Step 2: Add hidden Dense layer(s). Accuracy: 0.9745
- Step 3: Use Keras Flatten layer + Dense. Accuracy: 0.9711

Quick run
1. Install: pip install tensorflow numpy
2. Open MNIST.ipynb and run all cells.
3. Copy the printed test accuracies here to replace placeholders.

Used sparse_categorical_crossentropy as the loss function for training the model to efficiently handle integer-labeled target classes in the MNIST dataset.
