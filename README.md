# 🧠 Perceptron From Scratch

> A clean, from-scratch implementation of the Perceptron algorithm — built to understand the math behind machine learning without relying on high-level libraries.

---

## 🚀 Project Overview

This project implements a **binary classifier (Perceptron)** entirely from scratch using only NumPy. It demonstrates how a model learns a linear decision boundary through iterative weight updates.

Unlike typical implementations using Scikit-learn, this project focuses on **understanding the internal mechanics** of learning.

---

## ✨ Key Features

* ✅ Pure NumPy implementation (no ML libraries)
* ✅ Bias + weight updates from first principles
* ✅ Loss tracking across epochs
* ✅ Training visualization (loss curve)
* ✅ Clean, modular, and readable code

---

## 🧠 How It Works

The perceptron computes:

```
z = w·x + b
```

Then applies a step activation:

```
if z ≥ 0 → 1
else → 0
```

Weights are updated using:

```
w = w + η * (y - y_pred) * x
b = b + η * (y - y_pred)
```

---

## 📊 Results

* The model successfully learns the AND logic gate
* Converges within a few epochs
* Loss decreases over time 📉

---

## 📈 Visualization

Training loss over epochs:

(Add your plot screenshot here)

---

## 📂 Project Structure

```
Perceptron-From-Scratch/
│
├── perceptron.py        # Core implementation
├── notebook.ipynb       # Experiment & visualization
├── README.md            # Documentation
└── requirements.txt     # Dependencies
```

---

## ⚙️ Installation

```bash
git clone https://github.com/AbrarYasir01/Perceptron-From-Scratch.git
cd Perceptron-From-Scratch
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the notebook or script:

```bash
python perceptron.py
```

Or open in VS Code / Jupyter Notebook.

---

## 🧪 Example Dataset

The model is tested on a simple AND gate:

| x1 | x2 | y |
| -- | -- | - |
| 0  | 0  | 0 |
| 0  | 1  | 0 |
| 1  | 0  | 0 |
| 1  | 1  | 1 |

---

## 🎯 What I Learned

* How perceptron updates weights mathematically
* Role of bias in shifting decision boundaries
* Importance of activation functions
* How loss evolves during training

---

## 🔮 Future Improvements

* 📊 Decision boundary visualization
* 🔁 Multi-class perceptron
* ⚖️ Comparison with Scikit-learn implementation
* 🎥 Training animation

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a PR.

---

## ⭐ Why This Project Matters

This project demonstrates **strong fundamentals in machine learning**, which are essential for:

* Internships 💼
* Research work 📚
* Deep learning understanding 🔬

---

## 📬 Contact

GitHub: [https://github.com/AbrarYasir01](https://github.com/AbrarYasir01)

---

⭐ If you found this helpful, consider giving it a star!
