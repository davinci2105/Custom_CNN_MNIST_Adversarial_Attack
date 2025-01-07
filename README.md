# **Custom_CNN_MNIST_Adversarial_Attack**

This project involves training a custom Convolutional Neural Network (CNN) on the MNIST dataset and implementing **targeted** and **non-targeted adversarial attacks**, while also visualizing layer-wise outputs for better interpretability.

---

## **Project Overview**
The project demonstrates:
1. Training a custom CNN for digit classification using the MNIST dataset.
2. Exploring adversarial attacks:
   - **Targeted Attack**: Forcing an input to be classified as a specific target label.
   - **Non-Targeted Attack**: Causing a misclassification into any incorrect label.
3. Visualizing intermediate layer outputs to understand the internal workings of the CNN.

The implementation is provided in a single Jupyter Notebook for simplicity and ease of reproducibility.

---

## **Contents**
This repository contains:
- **`README.md`**: Documentation of the project.
- **`custom_cnn_mnist_adversarial_attack.ipynb`**: A Jupyter Notebook that:
  - Loads and preprocesses the MNIST dataset.
  - Builds and trains the custom CNN.
  - Generates adversarial attacks (targeted and non-targeted).
  - Visualizes the effect of attacks on layer-wise outputs.

---

## **Prerequisites**
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Libraries:
  - TensorFlow or PyTorch (depending on the framework used in the notebook)
  - NumPy
  - Matplotlib

To install dependencies, run:
```bash
pip install tensorflow numpy matplotlib
