#  Deep Learning - CNN on MNIST

A deep learning project that builds and compares two CNN models using different optimizers on the MNIST dataset.

##  Problem Description

This project explores how the choice of optimizer affects a CNN model's performance on image classification. Two identical CNN architectures are trained — one with **Adam** and one with **SGD** — and their results are compared.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

##  Dataset

- **Dataset:** MNIST Handwritten Digits
- **Link:** [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/)
- 60,000 training images / 10,000 test images
- 10 classes (digits 0–9)

##  Results

| Model | Optimizer | Accuracy | Loss |
|-------|-----------|----------|------|
| Model A | Adam | 99.13% | 0.0295 |
| Model B | SGD | 97.90% | 0.0675 |

 **Adam optimizer outperformed SGD** with higher accuracy and lower loss.

##  Model Architecture

```
Conv2D(32) → MaxPooling → Conv2D(64) → MaxPooling → Flatten → Dense(128) → Dropout(0.3) → Dense(10, softmax)
```

##  Instructions for Running the Project

1. Open `Deep_learing.ipynb` in **Google Colab** or Jupyter Notebook
2. Install dependencies:
```bash
pip install tensorflow numpy matplotlib
```
3. Run all cells in order
4. Results and plots will appear at the end of the notebook

##  Author

**Mariam Hany** — Computer Science Student, Badr University in Asyut
 mariam14720050@gmail.com
🔗 [GitHub](https://github.com/mariam14720050-ux)
