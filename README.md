# Day 40 – Matrix Operations 
📌 Overview
This exercise demonstrates how to implement a simple linear transformation using NumPy with fully vectorized operations.
# The transformation follows the formula:
Y = X @ W + b
# Where:
X = Input matrix (samples × features)
W = Weight matrix (features × outputs)
b = Bias vector (1 × outputs)
Y = Output matrix (samples × outputs)
# 📂 Given Matrices
X shape: (3, 2)
W shape: (2, 3)
b shape: (3,)
# Matrix multiplication:
(3×2) @ (2×3) → (3×3)
Then bias is broadcasted across rows automatically.
# ⚙️ Implementation
Y = X @ W + b
 Uses matrix multiplication (@)
Uses NumPy broadcasting for bias
No loops used
# 📊 Output Shape Verification
X.shape: (3, 2)
W.shape: (2, 3)
b.shape: (3,)
Y.shape: (3, 3)
Final output matrix Y has shape (3, 3).
# 🧠 Key Concepts Demonstrated
Matrix multiplication using @
Linear transformation
Vectorization
NumPy broadcasting
Shape verification
