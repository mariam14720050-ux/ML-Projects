# ⚡ Neural Networks - Activation Functions Comparison

A deep learning project that compares the effect of different activation functions on a fully-connected neural network using the MNIST dataset.

## 📌 Problem Description

This project investigates how activation functions impact a neural network's learning and accuracy. Two models with identical architectures are trained — one using **ReLU** and one using **Tanh** — and their performance is analyzed and compared.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## 📂 Dataset

- **Dataset:** MNIST Handwritten Digits
- **Link:** [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/)
- 60,000 training images / 10,000 test images
- 10 classes (digits 0–9)

## 📊 Results

| Model | Activation Function | Accuracy | Loss |
|-------|-------------------|----------|------|
| Model A | ReLU | 98.22% | 0.0621 |
| Model B | Tanh | 97.46% | 0.0784 |

✅ **ReLU outperformed Tanh** with higher accuracy and lower loss on this dataset.

## 🏗️ Model Architecture

```
Dense(256, activation) → Dropout(0.3) → Dense(128, activation) → Dropout(0.3) → Dense(10, softmax)
```

## 🚀 Instructions for Running the Project

1. Open `Neural_Networks.ipynb` in **Google Colab** or Jupyter Notebook
2. Install dependencies:
```bash
pip install tensorflow numpy matplotlib
```
3. Run all cells in order
4. Results and comparison plots will appear at the end of the notebook

## 👩‍💻 Author

**Mariam Hany** — Computer Science Student, Badr University in Asyut
📧 mariam14720050@gmail.com
🔗 [GitHub](https://github.com/mariam14720050-ux)
