# multilayer-perceptron-mnist
# Multilayer Perceptron from Scratch: Manual Computation and MNIST Training

**Muhammad Yahya**  
**Roll No: 24i-2030**  
**National University of Computer and Emerging Sciences**  
**Email:** i242030@isb.nu.edu.pk

## 📋 Project Overview
This is my **MVC Project** where I built a Multilayer Perceptron (MLP) completely from scratch.

- **Tasks 1–6**: I did every single calculation **by hand** on a small 2-2-2-1 network (forward pass, MSE loss, backpropagation using chain rule, and gradient descent updates) for all three training samples.
- **Task 7**: I scaled the same logic to a real-size network (**784-128-64-10**) and trained it on the full MNIST dataset using **pure NumPy** (no deep learning libraries).

**Final Results**:
- Test Accuracy: **95.54%**
- Final Train Loss: **0.0689**
- Final Test Loss: **0.0759**

The project helped me understand exactly how neural networks work under the hood — from basic math to working code.

## 📁 Repository Contents
- **`MLP_MNIST_Task7.ipynb`** → Complete Jupyter Notebook with all code, training loop, loss curves, and sample predictions (all cells executed and outputs visible).
- **`MVC_Report_24i_2030.pdf`** → Full project report in Springer LNCS format (compiled from Overleaf).

## ✨ Features
- Pure NumPy implementation (no PyTorch or TensorFlow)
- Sigmoid activation + Mean Squared Error loss
- Mini-batch gradient descent (batch size = 32, learning rate = 0.1)
- 20 epochs of training
- Manual calculations matched perfectly with the code
- Loss curves and sample digit predictions saved automatically

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-GITHUB-USERNAME/multilayer-perceptron-mnist.git

2. Open the notebook
    ```bash
    jupyter notebook MLP_MNIST_Task7.ipynb
## 📊 Results
When you run the notebook, it automatically saves:

loss_curve.png → Training vs Test loss curve
sample_predictions.png → One sample image per digit (0-9) with predictions

📚 References

LeCun, Y., Bottou, L., Bengio, Y., Haffner, P.: Gradient-based learning applied to document recognition. Proc. IEEE 86(11), 2278–2324 (1998)
Rumelhart, D.E., Hinton, G.E., Williams, R.J.: Learning representations by back-propagating errors. Nature 323, 533–536 (1986)
