# MNIST Neural Network from Scratch

A fully connected neural network implemented entirely from scratch using only NumPy to classify handwritten digits from the MNIST dataset.

I built this project as a self-study exercise to deeply understand the mathematics and mechanics behind neural networks before using frameworks such as PyTorch or TensorFlow.

---

## Features

* Forward propagation
* ReLU and Softmax activation functions
* Cross-entropy loss
* Backpropagation 
* Gradient descent optimization
* MNIST dataset parsing from raw gzip files
* Training and test accuracy tracking
* Confusion matrix visualization
* Misclassified example analysis

---

## Model Architecture

Input Layer:

* 784 neurons (28×28 flattened image)

Hidden Layer:

* 128 neurons
* ReLU activation

Output Layer:

* 10 neurons
* Softmax activation

---

## Results

After 500 epochs of training:

* Test accuracy exceeded 90%
* The model successfully learned meaningful handwritten digit patterns
* Most classification errors occurred on visually ambiguous digits

The project also includes:

* training curves,
* confusion matrix visualization,
* misclassified image analysis.

---

## Project Structure

```text
mnist-neural-network/
├── data/
│   └── raw/
├── notebooks/
│   └── mnist_from_scratch.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone <https://github.com/AfonsoAzevedo/mnist-neural-network.git>
cd mnist-neural-network
```

Create and activate a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/mnist_from_scratch.ipynb
```

---

## Key Learning Outcomes

This project helped reinforce:

* matrix operations in neural networks,
* forward and backward propagation,
* gradient descent optimization,
* activation functions,
* numerical stability in softmax,
* and the mathematical relationship between softmax and cross-entropy loss.

Have fun exploring!
