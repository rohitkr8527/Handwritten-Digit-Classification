# MNIST Digit Classification using a Neural Network

This project builds and trains a simple **neural network** using **TensorFlow/Keras** to classify handwritten digits from the **MNIST dataset**.

## Project Overview

- **Dataset:** MNIST — 70,000 grayscale images of handwritten digits (28x28 pixels).
- **Steps:**
  - Load and visualize the dataset.
  - Normalize and flatten the images.
  - Build a simple neural network.
  - Train the model on the training set.
  - Evaluate model performance on the test set.

## Technologies Used

- Python
- Numpy
- Matplotlib
- TensorFlow / Keras
- Scikit-learn

## Files

- **Notebook.ipynb**: Main Jupyter Notebook containing the complete workflow from data preprocessing to model evaluation.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Notebook 1.ipynb` and run all the cells.

## Requirements

You can create a `requirements.txt` with the following content:

```
numpy
matplotlib
scikit-learn
tensorflow
```

## Results

- The model is able to predict handwritten digits with good accuracy after training for a few epochs.
- Performance is evaluated using **classification report** (precision, recall, f1-score).

## Acknowledgments

- MNIST dataset provided by Yann LeCun and others.
- TensorFlow and Keras libraries for building and training the neural network.

