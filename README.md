# Gradient Descent Workshop

## Group Information

**Group Name:** Group 1  

**Group Members:**
- Ce Chen (Student ID: 9007166)  
- Haibo Yuan (Student ID: 9010929)  
- Zhuoran Zhang (Student ID: 9048508)

---

## Workshop Description

This workshop focuses on understanding and implementing gradient descent across different deep learning frameworks, including PyTorch, TensorFlow, and Keras.

The main objective is to explore how models learn from data by minimizing loss using gradient-based optimization, and to compare different levels of abstraction provided by each framework.

---

## Summary of Work Completed

In this workshop, we completed the following tasks:

### 1. PyTorch (Manual Gradient Descent)
- Implemented gradient descent manually using PyTorch
- Computed predictions, loss, gradients, and parameter updates step by step
- Demonstrated understanding of autograd and manual optimization

---

### 2. TensorFlow (GradientTape Implementation)
- Implemented gradient descent using `tf.GradientTape`
- Computed gradients and updated parameters manually
- Extended the implementation by:
  - Adding noise to the dataset
  - Training using mini-batches with `tf.data.Dataset`
  - Tracking and plotting training loss over epochs

---

### 3. Keras High-Level API
- Built a simple linear regression model using Keras
- Used `model.compile()` and `model.fit()` for training
- Observed how Keras abstracts the gradient descent process

---

### 4. Keras Custom Training Loop
- Implemented a custom training loop using `GradientTape`
- Manually computed gradients and applied updates using an optimizer
- Demonstrated how Keras can be used in a lower-level, flexible way similar to TensorFlow

---

## Key Insights

- Gradient descent works consistently across frameworks, but the implementation style varies.
- PyTorch provides more transparency and control for learning purposes.
- TensorFlow allows flexible gradient computation through `GradientTape`.
- Keras simplifies model training with high-level APIs, but still supports custom training loops.
- Adding noise and using mini-batches makes training more realistic but less smooth.

---

## Conclusion

This workshop helped us understand both the theoretical and practical aspects of gradient descent. By implementing the same concept across multiple frameworks, we gained a deeper understanding of how modern machine learning models are trained.

