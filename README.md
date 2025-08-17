# Machine-Learning-lab-report3

# XOR MLP Neural Network

This project implements a **simple Multi-Layer Perceptron (MLP)** from scratch in Python using **NumPy**, capable of learning the XOR logic gate. It also includes evaluation metrics and plots the ROC curve.

---

## Features

* Custom MLP with **one hidden layer** (2-2-1 architecture)
* Supports **sigmoid** and **ReLU** activation functions
* Implements **forward pass**, **backpropagation**, and **gradient descent**
* Evaluates performance with:

  * Accuracy
  * Precision
  * Recall
  * F1-Score
* Plots **ROC curve** for binary classification

---

## Requirements

* Python 3.x
* NumPy
* Matplotlib

Install dependencies via pip:

```bash
pip install numpy matplotlib
```

---

## Usage

1. Clone the repository or download the script:

```bash
git clone https://github.com/Tajuddin80/Machine-Learning-lab-report3/
```

2. Run the script:

```bash
python mlp_xor.py
```

3. The output will display:

* Predictions on XOR inputs
* Accuracy, Precision, Recall, F1-Score
* ROC curve plot

---

## Example Output

```
Predictions: [0 1 1 0]
Accuracy: 1.0
Precision: 1.0
Recall: 1.0
F1-Score: 1.0
```

The ROC curve will also be displayed in a matplotlib figure.

---

## Customization

* Change activation function in MLP initialization:

```python
mlp = MLP221(act='relu')  # Options: 'sigmoid', 'relu'
```

* Adjust learning rate and epochs:

```python
mlp.fit(X, y, lr=0.5, epochs=5000)
```

---

## License

This project is **open source** and available under the MIT License.
