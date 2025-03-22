# 🧠 Neural Networks from Scratch - Educational Projects

Welcome to the **Neural Networks from Scratch** repository! This collection of Python notebooks and scripts is designed to provide hands-on learning and experimentation with core neural network concepts, building everything from basic neurons to full feedforward architectures for classification.

---

## 📂 Project Structure

This repo includes various stages of NN development:

### 1️⃣ Basic Single Neuron Model
- Implements forward and backward propagation manually
- Activation: ReLU
- Loss: Mean Squared Error (MSE)
- Target: Scalar output

### 2️⃣ MNIST Binary Classifier
- Dataset: MNIST
- Task: Detect digit '0' vs others
- Layers: Single neuron
- Activation: ReLU
- Performance: ~85-90% accuracy
- Output: Loss graph + accuracy

### 3️⃣ Multiclass MNIST Classifier (Softmax)
- Fully connected layer for 10-class digit recognition
- Activation: ReLU + Softmax
- Loss: Categorical Crossentropy
- Data: MNIST
- Input: Uploaded image prediction available

### 4️⃣ Hidden Layer Neural Network
- Architecture: Input -> Hidden (128) -> Output
- Activation: ReLU + Softmax
- Fully built from scratch with numpy
- Train & predict handwritten digits

### 5️⃣ Spiral Dataset Classifier
- Data: Spiral classification (3 classes)
- Layers: Dense + ReLU + Softmax
- Loss: Cross Entropy
- Great for visualizing decision boundaries

### 6️⃣ Custom Softmax & Loss Calculation
- Test softmax outputs with categorical targets
- Manual negative log-likelihood computation

### 7️⃣ Feedforward Neural Net with Sigmoid
- Layers: Input -> Hidden (64) -> Output (10)
- Activation: Sigmoid
- Backpropagation: Implemented

---

## 🔧 Technologies Used

- Python
- NumPy
- Matplotlib
- TensorFlow (for dataset only)
- PIL (image preprocessing)
- Google Colab compatible

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/neural-networks-from-scratch.git
   ```
2. Open any of the Python files or run them in Google Colab
3. Modify, experiment, and visualize results

---

## 🎯 Educational Value

This repo is perfect if you want to:
- Understand how forward/backward pass works
- Learn activation functions (ReLU, Softmax, Sigmoid)
- Code cross-entropy loss by hand
- Train simple digit classifiers without deep frameworks

---

## 📸 Sample Output

You can visualize predictions by uploading handwritten digit images (`28x28 grayscale`). The model predicts and displays results with accuracy.

---

## 🤝 Contributions

Feel free to fork, contribute, or extend with:
- More activation functions
- Batch processing
- Optimization techniques (SGD, Adam, etc.)
- Dropout, regularization, etc.

---

## 📬 Contact

Maintainer: [Vaishvik Patel](mailto:vaishvikofficial@gmail.com)

---

> "Code is divine when you understand the neurons behind it."

---

**Star this repo ⭐ if it helped you learn neural networks from scratch!**

