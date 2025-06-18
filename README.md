This project demonstrates how to build, train, and evaluate a simple deep neural network for handwritten digit recognition using the MNIST dataset. It also includes functionality to classify custom images using OpenCV.

Features:
Trains a feedforward neural network on the MNIST dataset (28x28 grayscale images).
Visualizes dataset samples and predictions.
Evaluates the model using accuracy and a confusion matrix heatmap.
Loads and classifies external digit images (e.g., PNGs) using OpenCV.

🛠️ Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib
Seaborn
OpenCV
Google Colab (for display and execution)

📂 Project Structure
Data Preprocessing: Normalizes pixel values.
Model: 3-layer neural network with ReLU and Softmax activations.
Evaluation: Prints test accuracy and confusion matrix.
Custom Prediction: Loads an external digit image, resizes, normalizes, and predicts the digit.

📸 Sample Results
Model Accuracy: ~98%
Confusion Matrix to visualize predictions
Custom image classification for real-world digit inputs

